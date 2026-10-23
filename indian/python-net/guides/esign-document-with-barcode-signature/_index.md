---
title: "बारकोड हस्ताक्षर के साथ दस्तावेज़ को ई-साइन करें"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह लेख बताता है कि GroupDocs.Signature for Python via .NET के साथ दस्तावेज़ पृष्ठ पर बारकोड हस्ताक्षर कैसे जोड़ें, जिसमें बारकोड प्रकार, बारकोड टेक्स्ट, स्थिति, संरेखण और अन्य दृश्य सेटिंग्स जैसी विभिन्न विकल्प शामिल हैं।"
type: docs
url: /hi/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

एक **barcode** या **bar code** डेटा को दृश्य, मशीन-पठनीय रूप में प्रस्तुत करने का तरीका है। सामान्यतः, बारकोड एक आयताकार छवि है जिसमें विभिन्न चौड़ाइयों वाली समानांतर काली रेखाएँ और सफ़ेद अंतराल होते हैं।
बारकोड विभिन्न क्षेत्रों में उपयोग किए जाते हैं जहाँ तेज़ पहचान आवश्यक होती है - जैसे रिटेल स्टोर्स में खरीद प्रक्रिया का हिस्सा, वेयरहाउस में इन्वेंट्री ट्रैक करने के लिए, और इनवॉइस में लेखा‑जोखा में सहायता के लिए, तथा कई अन्य उपयोगों में।

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

बारकोड उत्पाद‑संबंधी डेटा जैसे निर्माण और समाप्ति तिथियाँ, निर्माता का नाम, मूल देश, और उत्पाद मूल्य संग्रहीत करने की अनुमति देते हैं। आजकल कई प्रकार के बारकोड उपलब्ध हैं क्योंकि विभिन्न कंपनियाँ अपनी आवश्यकताओं के अनुसार संख्याओं और बारों के विभिन्न संयोजन का उपयोग करती हैं। दस्तावेज़ हस्ताक्षर के दृष्टिकोण से, Barcode में विभिन्न अक्षर (अक्षर, अंक, या प्रतीक) हो सकते हैं और प्रकार व सेटिंग्स के आधार पर विभिन्न लंबाई और आकार हो सकते हैं, जिससे हस्ताक्षर जानकारी, शीर्षक, विषय, या छोटा एन्क्रिप्टेड डेटा रखा जा सकता है।

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Barcode हस्ताक्षर के विभिन्न विकल्प निर्दिष्ट करने के लिए GroupDocs.Signature for Python via .NET **[BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions)** क्लास प्रदान करता है। मुख्य फ़ील्ड हैं:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

GroupDocs.Signature for Python via .NET API का उपयोग करके बारकोड हस्ताक्षर के साथ दस्तावेज़ को ई‑साइन करने के चरण इस प्रकार हैं:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

यह उदाहरण दिखाता है कि Python का उपयोग करके PDF दस्तावेज़ पर बारकोड हस्ताक्षर कैसे करें:

{{< tabs \"sign_with_barcode_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # एन्कोड करने के लिए टेक्स्ट के साथ बारकोड हस्ताक्षर विकल्प बनाएं
        options = BarcodeSignOptions("John Smith")

        # बारकोड प्रकार सेट करें
        options.encode_type = BarcodeTypes.CODE128

        # बारकोड की स्थिति और आकार सेट करें
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # दस्तावेज़ पर हस्ताक्षर करें और परिणाम सहेजें
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"signed_barcode.pdf\" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

आप अतिरिक्त विकल्पों के साथ बारकोड हस्ताक्षर को और अनुकूलित कर सकते हैं: संरेखण और मार्जिन, बार रंग, एन्कोडेड टेक्स्ट की स्थिति, आंतरिक मार्जिन, पृष्ठभूमि, बॉर्डर और पारदर्शिता:

{{< tabs \"sign_with_barcode_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # कन्स्ट्रक्टर को टेक्स्ट और बारकोड प्रकार पास करें
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # बारकोड को पृष्ठ के नीचे दाएँ कोने में रखें
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # बार रंग, बारों के नीचे एन्कोडेड टेक्स्ट, बॉर्डर के अंदर का स्थान
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # पृष्ठभूमि, बॉर्डर और पारदर्शिता
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"signed_barcode_advanced.pdf\" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature विभिन्न बारकोड प्रकारों का समर्थन करता है। प्रत्येक प्रकार अपने अक्षरों और लंबाइयों का सेट स्वीकार करता है, इसलिए प्रकार से मेल खाने वाला टेक्स्ट चुनें। यह उदाहरण एक कॉल में विभिन्न प्रकार के चार बारकोड के साथ दस्तावेज़ पर हस्ताक्षर करता है:

{{< tabs \"sign_with_different_barcode_types\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # प्रत्येक बारकोड के लिए एक साइन विकल्प ऑब्जेक्ट, एक के नीचे एक रखा गया
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"signed_barcode_types.pdf\" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
यह गाइड दर्शाता है कि कैसे [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) का उपयोग करके दस्तावेज़ों में बारकोड-आधारित हस्ताक्षर जोड़े जा सकते हैं। यह विभिन्न बारकोड प्रकारों और अनुकूलन विकल्पों के समर्थन के साथ बारकोड हस्ताक्षर बनाने, कॉन्फ़िगर करने और लागू करने को कवर करता है। आगे की खोज के लिए, दस्तावेज़ जानकारी और उन्नत साइनिंग तकनीकों पर संबंधित गाइड देखें।

## More Resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

बारकोड बनाने और/या अपने फ़ाइलों को मुफ्त में बारकोड के साथ साइन करने के लिए, आप ऑनलाइन ऐप [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode) का उपयोग कर सकते हैं।

PDF, Word, Excel, PowerPoint और अन्य दस्तावेज़ों को साइन करने के लिए आप **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** के अन्य ऑनलाइन ऐप्स का उपयोग कर सकते हैं।
