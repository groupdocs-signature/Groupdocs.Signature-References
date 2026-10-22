---
title: "BarcodeSearchOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "बारकोड सिग्नेचर के लिए एब्स्ट्रैक्ट सर्च विकल्पों को दर्शाता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

बारकोड सिग्नेचर के लिए एब्स्ट्रैक्ट सर्च विकल्पों को दर्शाता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [BarcodeSearchOptions()](#BarcodeSearchOptions--) | डिफ़ॉल्ट मानों के साथ SearchBarcodeOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | SearchBarcodeOptions क्लास का नया उदाहरण एन्कोड प्रकार मान के साथ प्रारंभ करता है। |
| [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | SearchBarcodeOptions क्लास का नया उदाहरण एन्कोड प्रकार और टेक्स्ट मानों के साथ प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | बारकोड खोजने के लिए Encode Type प्रॉपर्टी निर्दिष्ट करता है। |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | बारकोड खोजने के लिए Encode Type प्रॉपर्टी निर्दिष्ट करता है। |
| [getText()](#getText--) | यदि खोजा और मिलान किया जाना चाहिए तो Barcode Signature टेक्स्ट निर्दिष्ट करता है। |
| [setText(String value)](#setText-java.lang.String-) | यदि खोजा और मिलान किया जाना चाहिए तो Barcode Signature टेक्स्ट निर्दिष्ट करता है। |
| [getMatchType()](#getMatchType--) | Barcode टेक्स्ट Match Type खोज को प्राप्त या सेट करता है। |
| [setMatchType(int value)](#setMatchType-int-) | Barcode टेक्स्ट Match Type खोज को प्राप्त या सेट करता है। |
| [getReturnContent()](#getReturnContent--) | दस्तावेज़ पृष्ठ पर सिग्नेचर की Barcode इमेज सामग्री को प्राप्त करने के लिए फ़्लैग को प्राप्त या सेट करता है। |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | दस्तावेज़ पृष्ठ पर सिग्नेचर की Barcode इमेज सामग्री को प्राप्त करने के लिए फ़्लैग को प्राप्त या सेट करता है। |
| [getReturnContentType()](#getReturnContentType--) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो Barcode सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | जब ReturnContent प्रॉपर्टी सक्षम हो, तो Barcode सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


डिफ़ॉल्ट मानों के साथ SearchBarcodeOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


SearchBarcodeOptions क्लास का नया उदाहरण एन्कोड प्रकार मान के साथ प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode एन्कोड प्रकार निर्दिष्ट करता है। |

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


SearchBarcodeOptions क्लास का नया उदाहरण एन्कोड प्रकार और टेक्स्ट मानों के साथ प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode एन्कोड प्रकार निर्दिष्ट करता है। |
| पाठ | java.lang.String | Barcode सिग्नेचर का टेक्स्ट सेट करें। |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


बारकोड खोजने के लिए Encode Type प्रॉपर्टी निर्दिष्ट करता है। यदि यह मान सेट नहीं है, तो सभी समर्थित Barcode प्रकारों के लिए खोज प्रक्रिया चलती है।

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


बारकोड खोजने के लिए Encode Type प्रॉपर्टी निर्दिष्ट करता है। यदि यह मान सेट नहीं है, तो सभी समर्थित Barcode प्रकारों के लिए खोज प्रक्रिया चलती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


यदि खोजा और मिलान किया जाना चाहिए तो Barcode Signature टेक्स्ट निर्दिष्ट करता है।

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


यदि खोजा और मिलान किया जाना चाहिए तो Barcode Signature टेक्स्ट निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Barcode टेक्स्ट Match Type खोज को प्राप्त या सेट करता है। यह केवल तब उपयोग किया जाता है जब Text प्रॉपर्टी सेट हो।

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Barcode टेक्स्ट Match Type खोज को प्राप्त या सेट करता है। यह केवल तब उपयोग किया जाता है जब Text प्रॉपर्टी सेट हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


दस्तावेज़ पृष्ठ पर सिग्नेचर की Barcode इमेज सामग्री को प्राप्त करने के लिए फ़्लैग को प्राप्त या सेट करता है। यदि यह फ़्लैग true सेट किया जाता है, तो Barcode सिग्नेचर इमेज सामग्री आवश्यक फ़ॉर्मेट ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)) द्वारा कच्चा इमेज डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प निष्क्रिय है।

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


दस्तावेज़ पृष्ठ पर सिग्नेचर की Barcode इमेज सामग्री को प्राप्त करने के लिए फ़्लैग को प्राप्त या सेट करता है। यदि यह फ़्लैग true सेट किया जाता है, तो Barcode सिग्नेचर इमेज सामग्री आवश्यक फ़ॉर्मेट ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)) द्वारा कच्चा इमेज डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प निष्क्रिय है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तो Barcode सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से इसे Null पर सेट किया गया है। इसका अर्थ है कि Barcode छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी। यह इमेज फ़ॉर्मेट BarcodeSignature.Format पर निर्दिष्ट है ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) संभावित समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो Barcode छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


जब ReturnContent प्रॉपर्टी सक्षम हो, तो Barcode सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से इसे Null पर सेट किया गया है। इसका अर्थ है कि Barcode छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी। यह इमेज फ़ॉर्मेट BarcodeSignature.Format पर निर्दिष्ट है ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) संभावित समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो Barcode छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

