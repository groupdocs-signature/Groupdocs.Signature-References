---
title: "इमेज सिग्नेचर के साथ eSign दस्तावेज़"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह लेख दिखाता है कि .NET के माध्यम से Python के लिए GroupDocs.Signature के साथ दस्तावेज़ पृष्ठ पर सिग्नेचर इमेज कैसे जोड़ें।"
type: docs
url: /hi/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

**image** को सिग्नेचर के रूप में उपयोग करना प्रस्तुत डेटा को दृश्य रूप में रखने का एक वैकल्पिक तरीका है। यह इलेक्ट्रॉनिक सिग्नेचर प्रकार कंपनी के लोगो, प्रेषक के आद्याक्षर, नाम आदि के साथ कस्टम इमेज बनाने की अनुमति देता है।

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

दस्तावेज़ पृष्ठ पर इमेज सिग्नेचर बनाने के चरण इस प्रकार हैं:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

यह उदाहरण दिखाता है कि Python का उपयोग करके इमेज सिग्नेचर के साथ PDF दस्तावेज़ पर कैसे साइन करें:

{{< tabs \"sign_with_image_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # इमेज फ़ाइल के साथ इमेज सिग्नेचर विकल्प बनाएं
        options = ImageSignOptions("signature.jpg")

        # सिग्नेचर की स्थिति और आकार सेट करें
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # दस्तावेज़ पर हस्ताक्षर करें और परिणाम सहेजें
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) क्लिक करें।

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

आप अतिरिक्त विकल्पों के साथ इमेज सिग्नेचर को और अनुकूलित कर सकते हैं: संरेखण और मार्जिन, घुमाव, पारदर्शिता और बॉर्डर। जब संरेखण सेट किया जाता है, तो यह `left` या `top` निर्देशांक को प्रतिस्थापित करता है, और `margin` सिग्नेचर को पृष्ठ किनारे से दूर करता है।

{{< tabs \"sign_with_image_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # सिग्नेचर को पृष्ठ के नीचे दाएँ कोने में रखें
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # इमेज को घुमाएँ और इसे 20% पारदर्शी बनाएँ
        options.rotation_angle = 10
        options.transparency = 0.2

        # इमेज के चारों ओर डैश्ड बॉर्डर बनाएं
        border = Border()
        border.color = Color.dark_green
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border

        result = signature.sign("signed_image_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) क्लिक करें।

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

आप सिग्नेचर इमेज को स्ट्रीम से भी लोड कर सकते हैं। `sign` लौटने तक स्ट्रीम को खुला रखें:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # स्ट्रीम से हस्ताक्षर छवि लोड करें
        with open("signature.jpg", "rb") as image_stream:
            options = ImageSignOptions(image_stream)
            options.left = 100
            options.top = 400
            options.width = 120
            options.height = 100

            result = signature.sign("signed_image_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) क्लिक करें।

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
यह गाइड दर्शाता है कि कैसे [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) का उपयोग करके दस्तावेज़ों में इमेज-आधारित हस्ताक्षर जोड़े जा सकते हैं। यह दस्तावेज़ लोड करने, इमेज हस्ताक्षर की गुणों (जैसे आकार, स्थिति, और पारदर्शिता) को कॉन्फ़िगर करने, और हस्ताक्षरित दस्तावेज़ को सहेजने को कवर करता है। उन्नत अनुकूलन विकल्प, जैसे इमेज की उपस्थिति को समायोजित करना और हस्ताक्षर को संरेखित करना, भी चर्चा किए गए हैं। आगे की जानकारी के लिए, संबंधित दस्तावेज़ हस्ताक्षर संसाधनों का अन्वेषण करें।

## More Resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

इमेज हस्ताक्षर बनाने और/या अपने फ़ाइलों को मुफ्त में उनके साथ साइन करने के लिए, आप [Generate Image](https://products.groupdocs.app/signature/generate/image) ऑनलाइन ऐप का उपयोग कर सकते हैं।

PDF, Word, Excel, PowerPoint और अन्य दस्तावेज़ों को साइन करने के लिए आप **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** के अन्य ऑनलाइन ऐप्स का उपयोग कर सकते हैं।
