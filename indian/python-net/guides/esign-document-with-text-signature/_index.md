---
title: "टेक्स्ट हस्ताक्षर के साथ eSign दस्तावेज़"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह लेख समझाता है कि GroupDocs.Signature for Python via .NET API का उपयोग करके टेक्स्ट हस्ताक्षर के साथ दस्तावेज़ पर कैसे हस्ताक्षर किया जाए। Python में प्रोग्रामेटिक रूप से PDF में डिजिटल हस्ताक्षर जोड़ना सीखें।"
type: docs
url: /hi/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

एक **Text** इलेक्ट्रॉनिक हस्ताक्षर वह मनमाना टेक्स्ट है जो दस्तावेज़ में मूल रूप से जोड़ा जाता है, दस्तावेज़ के प्रकार पर निर्भर करता है। GroupDocs.Signature टेक्स्ट हस्ताक्षर सुविधा प्रदान करता है और फ़ॉन्ट नाम, आकार और रंग से लेकर संरेखण, बॉर्डर, शैडो इफ़ेक्ट आदि तक विभिन्न सेटिंग्स को अनुकूलित करने की अनुमति देता है। यह एक टेक्स्ट हस्ताक्षर का उदाहरण है:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

आइए Python का उपयोग करके प्रोग्रामेटिक रूप से PDF में टेक्स्ट हस्ताक्षर जोड़ने का प्रयास करें।

टेक्स्ट हस्ताक्षरों को प्रोग्रामेटिक रूप से संभालने के लिए [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) क्लास प्रदान करता है और पूरा कार्यप्रवाह इस प्रकार सरल है:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

यह उदाहरण दिखाता है कि Python का उपयोग करके दस्तावेज़ में टेक्स्ट हस्ताक्षर कैसे जोड़ा जाए:

{{< tabs "sign_with_text_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # टेक्स्ट हस्ताक्षर विकल्प बनाएं
        options = TextSignOptions("John Smith")

        # सिग्नेचर की स्थिति और आकार सेट करें
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # टेक्स्ट का रंग और फ़ॉन्ट सेट करें
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # दस्तावेज़ पर हस्ताक्षर करें और परिणाम सहेजें
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

आप अतिरिक्त विकल्पों के साथ टेक्स्ट हस्ताक्षर को और अनुकूलित कर सकते हैं: संरेखण और मार्जिन, फ़ॉन्ट शैली, पृष्ठभूमि, बॉर्डर, घुमाव और पारदर्शिता। जब संरेखण सेट किया जाता है, तो यह `left` या `top` निर्देशांक को प्रतिस्थापित करता है, और `margin` हस्ताक्षर को पृष्ठ किनारे से दूर करता है।

{{< tabs "sign_with_text_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # सिग्नेचर को पृष्ठ के नीचे दाएँ कोने में रखें
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # फ़ॉन्ट शैली और टेक्स्ट रंग
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # पृष्ठभूमि, बॉर्डर, घुमाव और पारदर्शिता
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # टेक्स्ट को छवि के रूप में रेंडर करें, जो PDF पृष्ठों पर बॉर्डर भी बनाता है
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"signed_text_advanced.pdf\" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
यह गाइड समझाता है कि कैसे दस्तावेज़ों में टेक्स्ट‑आधारित हस्ताक्षर जोड़ें [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). यह फ़ॉन्ट, रंग, आकार और स्थिति जैसी टेक्स्ट प्रॉपर्टीज़ को कॉन्फ़िगर करने, और दस्तावेज़ पर टेक्स्ट हस्ताक्षर लागू करने को कवर करता है। फिर साइन किया गया दस्तावेज़ जोड़े गए टेक्स्ट हस्ताक्षर के साथ सहेजा जाता है।

## More Resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

PDF, Word, Excel, PowerPoint, और अन्य दस्तावेज़ों पर हस्ताक्षर करने के लिए आप ऑनलाइन ऐप्स **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** से उपयोग कर सकते हैं।
