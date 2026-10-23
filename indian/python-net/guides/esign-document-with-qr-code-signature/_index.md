---
title: "QR कोड हस्ताक्षर के साथ eSign दस्तावेज़"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह लेख बताता है कि कैसे दस्तावेज़ पृष्ठ पर QR कोड के रूप में इलेक्ट्रॉनिक हस्ताक्षर के साथ दस्तावेज़ों पर साइन किया जाए, GroupDocs.Signature for Python के माध्यम से .NET API का उपयोग करके।"
type: docs
url: /hi/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR कोड (या क्विक रिस्पॉन्स कोड) दो-आयामी [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) का एक प्रकार है जो सफ़ेद पृष्ठभूमि पर वर्ग ग्रिड में व्यवस्थित काली वर्गों से बना होता है। QR कोड को स्मार्टफ़ोन कैमरों या विशेष उपकरणों द्वारा पढ़ा जा सकता है जो QR पढ़ने के लिए समर्पित होते हैं - हाथ में पकड़े स्कैनर, हैंडी टर्मिनल, डेस्कटॉप स्कैनर, एम्बेडेड स्कैनर आदि। आमतौर पर QR कोड में डेटा होता है जो वेबसाइट या एप्लिकेशन, ईमेल, फ़ोन नंबर, उत्पाद पहचानकर्ता या ट्रैकर की ओर संकेत करता है। इसलिए QR कोड के उपयोग का दायरा सामान्य मार्केटिंग और वस्तु पहचान से लेकर दस्तावेज़ प्रबंधन तक विस्तृत है।

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec कोड | DataMatrix कोड | GS1 DataMatrix | GS1 QR कोड | QR |
| --- | --- | --- | --- | --- | --- |
| **Application** | * परिवहन और टिकटिंग;<br> * एयरलाइन उद्योग में इलेक्ट्रॉनिक बोर्डिंग पास के लिए;<br> * रेल में ऑनलाइन बेचे गए टिकट और ग्राहकों द्वारा प्रिंट किए गए या मोबाइल फ़ोन स्क्रीन पर दिखाए गए टिकट। कोड को ऑन-ट्रेन स्टाफ या टर्नस्टाइल पर हैंडहेल्ड स्कैनर द्वारा टिकट की वैधता जांचने के लिए स्कैन किया जाता है।<br> * दवा - रोगी पहचान ब्रेसलेट और इकाई-प्रयोग दवाओं के लेबल आदि। | * लेबल और पत्रों जैसी मुद्रित मीडिया;<br> * औद्योगिक इंजीनियरिंग उद्देश्यों - घटकों को चिह्नित करना आदि;<br>  * खाद्य उद्योग - खाद्य उत्पादों को गलत पैकेजिंग और तिथि लगाने से रोकने के लिए; | उपयोग किया जाता है<br> * स्वास्थ्य देखभाल;<br> * सरकार;<br> * औद्योगिक.<br> वस्तु की अतिरिक्त जानकारी को एन्कोड करता है, जैसे:<br> * वजन;<br> * समाप्ति तिथि;<br> * बैच नंबर;<br> * निर्माण तिथि;<br> * आदि। | मार्केटिंग में पैकेज पर अतिरिक्त वस्तु जानकारी एन्कोड करने के लिए उपयोग किया जाता है | ऑटोमोटिव उद्योग और मोबाइल अनुप्रयोगों में व्यापक रूप से उपयोग किया जाता है। बड़े मात्रा में डेटा अक्षरों और विशिष्ट URLs को एन्कोड करने में उपयोगी है। |
| **Length** | 3067 अल्फ़ान्यूमेरिक,<br> 3832 संख्यात्मक,<br> 1914 बाइट्स | 2335 अल्फ़ान्यूमेरिक,<br> 3116 संख्यात्मक | 2335 अल्फ़ान्यूमेरिक,<br> 3116 संख्यात्मक,<br> 1556 बाइट्स | 7089 अल्फ़ान्यूमेरिक,<br> 4296 संख्यात्मक,<br> 2953 बाइट्स | 4296 अल्फ़ान्यूमेरिक,<br> 7089 संख्यात्मक,<br> 2953 बाइट्स |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

जब एक दस्तावेज़ में QR कोड इलेक्ट्रॉनिक हस्ताक्षर जोड़ा जाता है, मुख्य सेटिंग्स एन्कोड किए जाने वाले टेक्स्ट और वह [QR कोड का प्रकार](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) होती हैं, जिसे [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) क्लास के माध्यम से निर्दिष्ट किया जाना चाहिए।

यहाँ QR कोड हस्ताक्षर के साथ एक दस्तावेज़ को eSign करने के चरण दिए गए हैं:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

नीचे दिया गया कोड स्निपेट दिखाता है कि Python का उपयोग करके QR कोड हस्ताक्षर के साथ PDF दस्तावेज़ पर कैसे साइन किया जाए:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # एन्कोड करने के लिए टेक्स्ट के साथ QR कोड हस्ताक्षर विकल्प बनाएं
        options = QrCodeSignOptions("John Smith")

        # QR कोड प्रकार सेट करें
        options.encode_type = QrCodeTypes.QR

        # QR कोड की स्थिति और आकार सेट करें
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # दस्तावेज़ पर हस्ताक्षर करें और परिणाम सहेजें
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "signed_qr_code.pdf" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

ऊपर की तालिका से अन्य QR कोड प्रकार भी उसी तरह सेट किए जाते हैं, उदाहरण के लिए `QrCodeTypes.AZTEC` या `QrCodeTypes.DATA_MATRIX`।

### Advanced QR Code Options

यहाँ एक उदाहरण दिया गया है जो दिखाता है कि अतिरिक्त अनुकूलन के साथ अधिक जटिल QR कोड हस्ताक्षर कैसे बनाया जाए: संरेखण और मार्जिन, मॉड्यूल रंग, पृष्ठभूमि और सीमा:

{{< tabs "sign_with_qr_code_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # पाठ और QR कोड प्रकार को कंस्ट्रक्टर में पास करें
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # पृष्ठ के निचले दाएँ कोने में QR कोड रखें
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # मॉड्यूल रंग, पृष्ठभूमि, और अंदर कुछ जगह के साथ बिंदुदार सीमा
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab "signed_qr_code_advanced.pdf" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
यह गाइड दर्शाता है कि दस्तावेज़ों में QR कोड हस्ताक्षर कैसे जोड़ें, [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) का उपयोग करके। इसमें QR कोड हस्ताक्षर उत्पन्न करने, उसके आकार और एन्कोडिंग जैसे गुणों को कॉन्फ़िगर करने, और इसे दस्तावेज़ पर लागू करने के चरण शामिल हैं। QR कोड हस्ताक्षर का उपयोग हस्ताक्षरित दस्तावेज़ की त्वरित सत्यापन के लिए किया जा सकता है।

## More Resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

QR कोड उत्पन्न करने और/या अपने फ़ाइलों को मुफ्त में QR कोड से हस्ताक्षर करने के लिए, आप ऑनलाइन ऐप [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode) का उपयोग कर सकते हैं।

PDF, Word, Excel, PowerPoint और अन्य दस्तावेज़ों को साइन करने के लिए आप **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** के अन्य ऑनलाइन ऐप्स का उपयोग कर सकते हैं।
