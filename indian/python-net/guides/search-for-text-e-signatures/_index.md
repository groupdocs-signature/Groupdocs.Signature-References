---
title: "टेक्स्ट ई-सिग्नेचर खोजें"
linkTitle: "Texts"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह विषय समझाता है कि .NET API के माध्यम से Python के लिए GroupDocs.Signature का उपयोग करके दस्तावेज़ पृष्ठों में टेक्स्ट इलेक्ट्रॉनिक सिग्नेचर कैसे खोजें।"
type: docs
url: /hi/python-net/guides/search-for-text-e-signatures/
is_root: false
weight: 90
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) class to specify different options for searching Text electronic signatures within documents.

GroupDocs.Signature API का उपयोग करके टेक्स्ट ई-सिग्नेचर खोजने के चरण इस प्रकार हैं:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) object according to your requirements and specify additional search options (if needed).
* Call the [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass a list with the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) to it. The `signatures` property of the returned [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult) holds the found [TextSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignature) objects.

यह उदाहरण दिखाता है कि Python का उपयोग करके दस्तावेज़ में टेक्स्ट ई-सिग्नेचर कैसे खोजें। प्रत्येक सिग्नेचर की `signature_implementation` प्रॉपर्टी बताती है कि इसे दस्तावेज़ में कैसे जोड़ा गया: पृष्ठ सामग्री (`NATIVE`) के रूप में, एक एनोटेशन, एक फॉर्म फ़ील्ड आदि।

{{< tabs "search_text" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_text():
    with Signature("signed.pdf") as signature:
        result = signature.search([TextSearchOptions()])

        print(f"Found {len(result.signatures)} text signature(s)")
        for text_signature in result.signatures:
            print(f"{text_signature.signature_implementation.name} text signature '{text_signature.text}' "
                  f"on page {text_signature.page_number} at ({text_signature.left}, {text_signature.top}), "
                  f"size {text_signature.width}x{text_signature.height}")

if __name__ == "__main__":
    search_text()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"search-text.txt\" >}}
```text
Found 3 text signature(s)
ANNOTATION text signature 'Approved' on page 1 at (50, 480), size 90x22
FORM_FIELD text signature 'John Smith' on page 1 at (50, 530), size 190x22
NATIVE text signature 'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text/search-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Advanced Search Options

यहाँ एक उदाहरण है जो अधिक उन्नत खोज विकल्पों के उपयोग को दिखाता है: खोजने के लिए एक पृष्ठ, उसके साथ मिलाने के लिए पाठ जिसका [TextMatchType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textmatchtype), और खोजने के लिए [TextSignatureImplementation](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignatureimplementation)।

{{< tabs \"search_text_with_filters\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

def search_text_with_filters():
    with Signature("signed.pdf") as signature:
        options = TextSearchOptions()
        # केवल पहला पृष्ठ खोजें (पृष्ठ संख्याएँ 1 से शुरू होती हैं)
        options.all_pages = False
        options.page_number = 1
        # केवल उन टेक्स्ट सिग्नेचर को लौटाएँ जिनमें \"John\" शामिल है...
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS
        # ...और जो पृष्ठ सामग्री का हिस्सा हैं
        options.signature_implementation = TextSignatureImplementation.NATIVE

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching text signature(s)")
        for text_signature in result.signatures:
            print(f"'{text_signature.text}' on page {text_signature.page_number} "
                  f"at ({text_signature.left}, {text_signature.top}), "
                  f"size {text_signature.width}x{text_signature.height}")

if __name__ == "__main__":
    search_text_with_filters()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"search-text-with-filters.txt\" >}}
```text
Found 1 matching text signature(s)
'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text_with_filters/search-text-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## More Resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

PDF, Word, Excel, PowerPoint, और अन्य दस्तावेज़ों पर हस्ताक्षर करने के लिए आप ऑनलाइन ऐप्स **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** से उपयोग कर सकते हैं।
