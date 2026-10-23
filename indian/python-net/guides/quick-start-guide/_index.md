---
title: "त्वरित प्रारंभ गाइड"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "एक वर्चुअल एनवायरनमेंट सेट करें, groupdocs-signature-net स्थापित करें, और तीन न्यूनतम उदाहरण चलाएँ: टेक्स्ट हस्ताक्षर के साथ PDF पर हस्ताक्षर करें, उसमें हस्ताक्षर खोजें, और उन्हें सत्यापित करें।"
type: docs
url: /hi/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


यह गाइड एक त्वरित अवलोकन प्रदान करता है कि GroupDocs.Signature for Python via .NET को कैसे सेट अप करें और उपयोग शुरू करें। यह लाइब्रेरी कुछ पंक्तियों के कोड से PDF, Word, Excel, PowerPoint, OpenDocument और इमेज फ़ाइलों में इलेक्ट्रॉनिक हस्ताक्षर जोड़ती, खोजती, सत्यापित करती, अपडेट करती और हटाती है।

## Prerequisites

आगे बढ़ने के लिए, सुनिश्चित करें कि आपके पास है:

1. एक कॉन्फ़िगर किया गया वातावरण जैसा कि [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/) विषय में वर्णित है। Linux और macOS पर इसमें कुछ सिस्टम पैकेज शामिल हैं।
2. वैकल्पिक रूप से, सभी उत्पाद सुविधाओं का परीक्षण करने के लिए एक [Temporary License](https://purchase.groupdocs.com/temporary-license/)। बिना लाइसेंस के लाइब्रेरी मूल्यांकन मोड में काम करती है: यह दो पृष्ठों तक के दस्तावेज़ों को प्रोसेस करती है और प्रत्येक पृष्ठ पर एक मूल्यांकन पंक्ति जोड़ती है जिसे वह हस्ताक्षर करती है। देखें [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/)।

## Set Up Your Development Environment

सर्वोत्तम प्रथाओं के लिए, निर्भरताओं को प्रबंधित करने हेतु वर्चुअल एनवायरनमेंट का उपयोग करें। अधिक जानकारी के लिए [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) गाइड देखें।

### Create and Activate a Virtual Environment

एक वर्चुअल एनवायरनमेंट बनाएं:

{{< tabs "create-venv">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

इसे सक्रिय करें:

{{< tabs "activate-venv">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs "install-package">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

संस्करण पिन करने और PyPI तक पहुँच के बिना स्थापित करने के लिए देखें [Installation](/signature/python-net/guides/installation/)।

## Example 1: Sign a PDF with a Text Signature

एक दस्तावेज़ खोलें, हस्ताक्षर को [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/) के साथ वर्णित करें, और हस्ताक्षरित प्रति सहेजें।

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # दस्तावेज़ खोलें; with-block समाप्त होने पर फ़ाइल को रिलीज़ करता है
    with Signature("sample.pdf") as signature:
        # पहले पृष्ठ के बाएँ और ऊपर किनारों से 100 पिक्सेल दूर एक टेक्स्ट सिग्नेचर
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # साइन करें और परिणाम को नई फ़ाइल में सहेजें; स्रोत अपरिवर्तित रहता है
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

दस्तावेज़ में पहले से मौजूद सिग्नेचर खोजें। `search` खोज विकल्पों की एक सूची लेता है, प्रत्येक सिग्नेचर प्रकार के लिए एक, और उन्हें `result.signatures` में लौटाता है।

{{< tabs "search_document_for_signatures">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # हर पृष्ठ पर टेक्स्ट सिग्नेचर खोजें
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

जाँचें कि दस्तावेज़ में वह सिग्नेचर है जिसकी आप अपेक्षा करते हैं। सत्यापन तब सफल होता है जब बिल्कुल इस टेक्स्ट वाला टेक्स्ट सिग्नेचर पाया जाता है।

{{< tabs "verify_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

प्रत्येक उदाहरण को उसके अपने `.py` फ़ाइल में सैंपल फ़ाइलों के बगल में सहेजें। आपका फ़ोल्डर इस तरह दिखना चाहिए:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

उस फ़ोल्डर से एक उदाहरण चलाएँ:

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

जब आप समाप्त कर लें, तो `deactivate` चलाकर या शेल बंद करके वर्चुअल एनवायरनमेंट को निष्क्रिय करें।

## Apply a License

`GROUPDOCS_LIC_PATH` पर्यावरण वेरिएबल को अपनी लाइसेंस फ़ाइल के पूर्ण पथ पर सेट करें, और लाइसेंस स्वचालित रूप से लागू हो जाता है जब `groupdocs.signature` इम्पोर्ट किया जाता है। कोड की आवश्यकता नहीं है। वैकल्पिक रूप से, इसे कोड में एक बार लागू करें, किसी भी अन्य कॉल से पहले:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

यह [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) विषय दोनों तरीकों और मीटर लाइसेंस को कवर करता है।

## Next Steps

बुनियादी बातें पूरी करने के बाद, अतिरिक्त संसाधनों का अन्वेषण करें:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
