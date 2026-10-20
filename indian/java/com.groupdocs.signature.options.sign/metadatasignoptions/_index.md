---
title: "MetadataSignOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "मेटाडाटा हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

मेटाडाटा हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | डिफ़ॉल्ट मानों के साथ SignMetadataOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Metadata के साथ SignMetadataOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | हस्ताक्षर की Metadata प्राप्त करता है या सेट करता है। |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | हस्ताक्षर की Metadata प्राप्त करता है या सेट करता है। |
|
|  | [getDataEncryption()](#getDataEncryption--) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है। |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है। |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | प्रदान किए गए आर्ग्युमेंट्स के साथ नया PdfMetadataSignature बनाता है और इसे संग्रह में जोड़ता है। |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | प्रदान किए गए आर्ग्युमेंट्स के साथ नया ImageMetadataSignature बनाता है और इसे संग्रह में जोड़ता है। |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | मौजूदा MetadataSignature इंस्टेंस को संग्रह में जोड़ें। |
|
|  | [validate()](#validate--) | विकल्प पैरामीटरों को मान्य करने के लिए आंतरिक विधि। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


डिफ़ॉल्ट मानों के साथ SignMetadataOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Metadata के साथ SignMetadataOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Metadata Signatures का संग्रह [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


हस्ताक्षर की Metadata प्राप्त करता है या सेट करता है।


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


हस्ताक्षर की Metadata प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है।


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


प्रदान किए गए आर्ग्युमेंट्स के साथ नया PdfMetadataSignature बनाता है और इसे संग्रह में जोड़ता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | Metadata हस्ताक्षर वस्तु का नाम |
|
|  | मान | java.lang.Object | Metadata हस्ताक्षर का मान |
|
|  | टैग | java.lang.String | Metadata हस्ताक्षर का उपसर्ग टैग |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


प्रदान किए गए आर्ग्युमेंट्स के साथ नया ImageMetadataSignature बनाता है और इसे संग्रह में जोड़ता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | आईडी | int | छवि Image Metadata Signature नाम का अद्वितीय पहचानकर्ता। संभावित id मानों के लिए Exif टैग विनिर्देशों के संदर्भ देखें। |
|
|  | मान | java.lang.Object | Metadata मान |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


मौजूदा MetadataSignature इंस्टेंस को संग्रह में जोड़ें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | जो मौजूदा MetadataSignature इंस्टेंस जोड़ा जाना है |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


विकल्प पैरामीटरों को मान्य करने के लिए आंतरिक विधि।


### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
