---
title: "डिजिटल हस्ताक्षर के साथ दस्तावेज़ साइन करें"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिजिटल हस्ताक्षरों का उपयोग करके दस्तावेज़ों को सुरक्षित रूप से साइन करने के लाभों के बारे में जानें। चरण-दर-चरण निर्देशों के साथ पाइथन में प्रोग्रामेटिक रूप से डिजिटल हस्ताक्षर जोड़ना कैसे है, खोजें।"
type: docs
url: /hi/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

आज के डिजिटल युग में, इलेक्ट्रॉनिक दस्तावेज़ों की प्रामाणिकता और अखंडता सुनिश्चित करना अत्यंत महत्वपूर्ण है। इसे प्राप्त करने का एक अत्यधिक प्रभावी तरीका डिजिटल हस्ताक्षरों का उपयोग है। इस गाइड में, हम डिजिटल हस्ताक्षरों की दुनिया का अन्वेषण करेंगे, यह समझाते हुए कि वे क्या हैं, क्यों आवश्यक हैं, और आप GroupDocs.Signature for Python via .NET का उपयोग करके अपने दस्तावेज़ों को सहजता से eSign कैसे कर सकते हैं।

## What is a Digital Signature?

डिजिटल हस्ताक्षर एक क्रिप्टोग्राफ़िक तंत्र है जो इलेक्ट्रॉनिक दस्तावेज़ों की प्रामाणिकता और अखंडता की पुष्टि करता है। यह मजबूत आश्वासन देता है कि दस्तावेज़ ज्ञात प्रेषक से आया है और अनधिकृत स्रोतों द्वारा छेड़छाड़ नहीं की गई है। डिजिटल हस्ताक्षर आमतौर पर प्रमाणपत्रों द्वारा दर्शाए जाते हैं जिनमें निजी (हस्ताक्षर के लिए) और सार्वजनिक (पुष्टि के लिए) कुंजियाँ होती हैं। विभिन्न सार्वजनिक कुंजी क्रिप्टोग्राफी मानक, जैसे PFX फ़ॉर्मेट, इस उद्देश्य के लिए सामान्यतः उपयोग किए जाते हैं।
नीचे की तस्वीर दिखाती है कि डिफ़ॉल्ट रूप से PDF दस्तावेज़ पृष्ठ पर डिजिटल हस्ताक्षर कैसे दिखता है।

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

समाप्त और अभी-अभी मान्य नहीं हुए प्रमाणपत्रों को अस्वीकार किया जाता है: `sign` [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) को इस तरह का संदेश उत्पन्न करता है जैसे "The signing certificate expired on ..."। ऐसे प्रमाणपत्र के साथ भी साइन करने के लिए, `allow_expired` या `allow_not_yet_valid` को `True` सेट करें।

### Follow these steps to sign your documents with a digital signature

1. pip का उपयोग करके GroupDocs.Signature पैकेज स्थापित करें:
```bash
pip install groupdocs-signature-net
```

2. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) क्लास का नया इंस्टेंस बनाएं और स्रोत दस्तावेज़ पथ को कंस्ट्रक्टर पैरामीटर के रूप में पास करें।
3. आवश्यक प्रमाणपत्र और उसके पासवर्ड के साथ [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) ऑब्जेक्ट को इंस्टैंशिएट करें।
4. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) क्लास इंस्टेंस की [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) मेथड को कॉल करें और उसमें [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) पास करें।

नीचे दिया गया उदाहरण दिखाता है कि पाइथन का उपयोग करके डिजिटल ई-हस्ताक्षर के साथ PDF दस्तावेज़ को कैसे साइन किया जाए। हम इसी तरह किसी भी अन्य समर्थित दस्तावेज़ फ़ॉर्मेट को साइन कर सकते हैं।

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # प्रमाणपत्र फ़ाइल के साथ डिजिटल हस्ताक्षर विकल्प बनाएं
        options = DigitalSignOptions("certificate.pfx")

        # प्रमाणपत्र पासवर्ड सेट करें
        options.password = "1234567890"

        # वैकल्पिक: एक छवि जो पृष्ठ पर हस्ताक्षर दिखाती है
        options.image_file_path = "signature.jpg"

        # हस्ताक्षर की स्थिति सेट करें
        options.left = 100
        options.top = 400

        # दस्तावेज़ पर हस्ताक्षर करें और परिणाम सहेजें
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` इस उदाहरण में उपयोग किया गया नमूना प्रमाणपत्र है (पासवर्ड `1234567890`)। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) क्लिक करें।

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) क्लिक करें।

{{< /tab >}}
{{< tab "signed_digital.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

आप अतिरिक्त विकल्पों के साथ डिजिटल हस्ताक्षर को और अनुकूलित कर सकते हैं: पृष्ठ पर हस्ताक्षर का आकार, तथा उसमें संग्रहीत संपर्क, कारण और स्थान।

{{< tabs "sign_with_digital_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # सर्टिफ़िकेट और अपीयरेंस इमेज को कन्स्ट्रक्टर में पास करें
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # पृष्ठ पर हस्ताक्षर दिखाएँ, इस स्थिति और आकार पर
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # हस्ताक्षर में संग्रहीत जानकारी
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` इस उदाहरण में उपयोग किया गया नमूना प्रमाणपत्र है (पासवर्ड `1234567890`)। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) क्लिक करें।

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) क्लिक करें।

{{< /tab >}}
{{< tab "signed_digital_advanced.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

आप प्रमाणपत्र को स्ट्रीम से भी लोड कर सकते हैं। `sign` लौटने तक स्ट्रीम को खुला रखें:

{{< tabs "sign_with_certificate_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # स्ट्रीम से प्रमाणपत्र लोड करें
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # सिग्नेचर की स्थिति और आकार सेट करें
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` इस उदाहरण में उपयोग किया गया नमूना प्रमाणपत्र है (पासवर्ड `1234567890`)। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) क्लिक करें।

{{< /tab >}}
{{< tab "signed_digital_stream.pdf" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
यह गाइड दर्शाता है कि कैसे [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) का उपयोग करके दस्तावेज़ों पर डिजिटल हस्ताक्षर किए जा सकते हैं। यह बताता है कि दस्तावेज़ कैसे लोड करें, प्रमाणपत्र-आधारित हस्ताक्षर कैसे कॉन्फ़िगर करें, और हस्ताक्षरित फ़ाइलों को सुरक्षित रूप से कैसे सहेजें। उन्नत सुविधाओं, जैसे हस्ताक्षर का रूप और हस्ताक्षर में संग्रहीत जानकारी, को भी कवर किया गया है। अतिरिक्त विवरण के लिए डिजिटल साइनिंग वर्कफ़्लो पर संबंधित संसाधनों को देखें।

## More Resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

PDF, Word, Excel, PowerPoint, और अन्य दस्तावेज़ों पर हस्ताक्षर करने के लिए आप ऑनलाइन ऐप्स **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** से उपयोग कर सकते हैं।
