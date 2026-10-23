---
title: "दस्तावेज़ पृष्ठों का पूर्वावलोकन उत्पन्न करें"
linkTitle: "Generate document pages preview"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह विषय बताता है कि GroupDocs.Signature for Python via .NET द्वारा विभिन्न विकल्पों के साथ दस्तावेज़ पृष्ठों का पूर्वावलोकन छवियों के रूप में कैसे प्राप्त किया जाए।"
type: docs
url: /hi/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
GroupDocs.Signature के साथ दस्तावेज़ पूर्वावलोकन उत्पन्न करने के चरण यहाँ हैं:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

create फ़ंक्शन द्वारा लौटाया गया स्ट्रीम पेज इमेज लिखे जाने के तुरंत बाद स्वचालित रूप से बंद हो जाता है: फ़ाइल बंद हो जाती है, और एक `io.BytesIO` पहले से ही पूर्ण इमेज रखता है। यदि आपको प्रत्येक समाप्त इमेज को प्रोसेस करना है या स्वयं संसाधनों को साफ़ करना है, तो एक रिलीज़ फ़ंक्शन को अतिरिक्त तर्क के रूप में पास करें (देखें [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/))।

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature प्रत्येक पृष्ठ के लिए create फ़ंक्शन को एक बार कॉल करता है और पेज इमेज को उस स्ट्रीम में लिखता है जो वह लौटाता है: एक लिखने योग्य फ़ाइल ऑब्जेक्ट, एक `io.BytesIO`, या एक .NET स्ट्रीम। `page_data` तर्क एक [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) ऑब्जेक्ट है जिसमें `page_number`, दस्तावेज़ का `file_name` और `preview_format` शामिल हैं।

पृष्ठ संख्याएँ 0-आधारित हैं: `page_data.page_number` दस्तावेज़ के पहले पृष्ठ के लिए `0` है।

```python
def create_page_stream(page_data):
    # 0-आधारित: preview_page_0.png पहला पृष्ठ है
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

जब आप एक अभिलेख का पूर्वावलोकन करते हैं, तो फ़ंक्शन उसके भीतर प्रत्येक दस्तावेज़ के पृष्ठों के लिए कॉल किया जाता है। पृष्ठ संख्याएँ प्रत्येक दस्तावेज़ के लिए फिर से `0` से शुरू होती हैं, इसलिए छवियों के नामकरण में `page_data.file_name` का भी उपयोग करें।

## ReleasePageStream delegate implementation

रिलीज़ फ़ंक्शन वही `page_data` और वही ऑब्जेक्ट प्राप्त करता है जो create फ़ंक्शन ने लौटाया था। जब इसे कॉल किया जाता है, तब इमेज पूर्ण हो चुकी होती है।

```python
def release_page_stream(page_data, page_stream):
    # page_stream वह ऑब्जेक्ट है जो create_page_stream ने लौटाया।
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs \"generate_document_preview\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # पृष्ठ संख्याएँ 0-आधारित हैं: preview_page_0.png पहला पृष्ठ है
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # प्रिव्यू विकल्प ऑब्जेक्ट बनाएं: प्रत्येक पृष्ठ के लिए एक PNG छवि
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # प्रिव्यू उत्पन्न करें
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "generate-document-preview-outputs.zip" >}}
```text
preview_page_0.png (75 KB)
preview_page_1.png (64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview/generate-document-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Generate document preview from stream with custom stream releasing delegate

यह उदाहरण दस्तावेज़ को एक स्ट्रीम से पढ़ता है और पृष्ठ छवियों को मेमोरी में रखता है: create फ़ंक्शन एक `io.BytesIO` लौटाता है, और release फ़ंक्शन इसे पूरी छवि से भरा हुआ प्राप्त करता है।

{{< tabs "generate_document_preview_from_stream" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # फ़ाइल लिखने के बजाय प्रत्येक पृष्ठ की छवि को मेमोरी में रखें
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # `page_stream` ऊपर लौटाए गए BytesIO है, जो पहले से पूरी छवि रखता है
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # दोनों फ़ंक्शनों के साथ प्रिव्यू विकल्प ऑब्जेक्ट बनाएं
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # प्रिव्यू उत्पन्न करें
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "generate-document-preview-from-stream.txt" >}}
```text
Page 0: 276044 bytes of JPEG
Page 1: 224194 bytes of JPEG
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_from_stream/generate-document-preview-from-stream.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate preview of particular pages

`page_numbers` सेट करें ताकि केवल कुछ पृष्ठों का प्रिव्यू हो। संख्याएँ 0-आधारित हैं, इसलिए `[1]` दूसरा पृष्ठ चुनता है।

{{< tabs "generate_document_preview_of_selected_pages" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}.png", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_of_selected_pages():
    with Signature("sample.pdf") as signature:
        preview_options = PreviewOptions(create_page_stream, release_page_stream)
        # पृष्ठ संख्याएँ 0-आधारित हैं: [1] दूसरा पृष्ठ है
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "preview_page_1.png" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

डिफ़ॉल्ट रिज़ॉल्यूशन 96 DPI है। रिज़ॉल्यूशन को [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/) के तीसरे तर्क के रूप में पास करें, या `resolution` प्रॉपर्टी सेट करें।

{{< tabs "generate_document_preview_with_resolution" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}_150dpi.jpg", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_with_resolution():
    with Signature("sample.pdf") as signature:
        resolution = 150
        # प्रिव्यू विकल्प ऑब्जेक्ट बनाएं: डिफ़ॉल्ट 96 के बजाय 150 DPI
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # प्रिव्यू उत्पन्न करें
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "generate-document-preview-with-resolution-outputs.zip" >}}
```text
preview_page_0_150dpi.jpg (495 KB)
preview_page_1_150dpi.jpg (425 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_with_resolution/generate-document-preview-with-resolution-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

PDF, Word, Excel, PowerPoint, और अन्य दस्तावेज़ों पर हस्ताक्षर करने के लिए आप ऑनलाइन ऐप्स **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** से उपयोग कर सकते हैं।
