---
title: "DocumentInfo"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ विवरण गुणों को परिभाषित करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

दस्तावेज़ विवरण गुणों को परिभाषित करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DocumentInfo()](#DocumentInfo--) | एक नया उदाहरण प्रारंभ करता है [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) वर्ग का। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPageCount()](#getPageCount--) | दस्तावेज़ पृष्ठों की गिनती। |
| [setPageCount(int value)](#setPageCount-int-) | दस्तावेज़ पृष्ठों की गिनती। |
| [getPages()](#getPages--) | दस्तावेज़ पृष्ठ विवरणों का संग्रह। |
| [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | दस्तावेज़ पृष्ठ विवरणों का संग्रह। |
| [getWidthForMaxHeight()](#getWidthForMaxHeight--) | अधिकतम पृष्ठ ऊँचाई के लिए चौड़ाई निर्दिष्ट करता है। |
| [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | अधिकतम पृष्ठ ऊँचाई के लिए चौड़ाई निर्दिष्ट करता है। |
| [getMaxPageHeight()](#getMaxPageHeight--) | अधिकतम पृष्ठ ऊँचाई निर्दिष्ट करता है। |
| [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | अधिकतम पृष्ठ ऊँचाई निर्दिष्ट करता है। |
| [getFileType()](#getFileType--) | फ़ाइल फ़ॉर्मेट प्रकार। |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | फ़ाइल फ़ॉर्मेट प्रकार। |
| [getSize()](#getSize--) | बाइट्स में दस्तावेज़ आकार। |
| [setSize(long value)](#setSize-long-) | बाइट्स में दस्तावेज़ आकार। |
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
| [getTextSignatures()](#getTextSignatures--) | दस्तावेज़ पाठ हस्ताक्षरों का संग्रह। |
| [getImageSignatures()](#getImageSignatures--) | दस्तावेज़ छवि हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं। |
| [getDigitalSignatures()](#getDigitalSignatures--) | दस्तावेज़ डिजिटल हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं। |
| [getBarcodeSignatures()](#getBarcodeSignatures--) | दस्तावेज़ बारकोड हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं। |
| [getQrCodeSignatures()](#getQrCodeSignatures--) | दस्तावेज़ QR-कोड हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं। |
| [getFormFieldSignatures()](#getFormFieldSignatures--) | दस्तावेज़ फ़ॉर्म फ़ील्ड हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं। |
| [getFormFields()](#getFormFields--) | दस्तावेज़ में सभी मौजूदा समर्थित फ़ॉर्म फ़ील्ड्स का संग्रह। |
| [getMetadataSignatures()](#getMetadataSignatures--) | दस्तावेज़ मेटाडेटा हस्ताक्षरों का संग्रह। |
| [getProcessLogs()](#getProcessLogs--) | दस्तावेज़ इतिहास प्रक्रियाओं जैसे साइन, अपडेट, डिलीट का संग्रह। |
| [getSignatures()](#getSignatures--) | दस्तावेज़ के सभी प्रकार के हस्ताक्षरों का संग्रह [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)। |
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


एक नया उदाहरण प्रारंभ करता है [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) वर्ग का।

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


दस्तावेज़ पृष्ठों की गिनती।

**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


दस्तावेज़ पृष्ठों की गिनती।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


दस्तावेज़ पृष्ठ विवरणों का संग्रह।

**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


दस्तावेज़ पृष्ठ विवरणों का संग्रह।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


अधिकतम पृष्ठ ऊँचाई के लिए चौड़ाई निर्दिष्ट करता है।

**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


अधिकतम पृष्ठ ऊँचाई के लिए चौड़ाई निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


अधिकतम पृष्ठ ऊँचाई निर्दिष्ट करता है।

**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


अधिकतम पृष्ठ ऊँचाई निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


फ़ाइल फ़ॉर्मेट प्रकार।

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


फ़ाइल फ़ॉर्मेट प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


बाइट्स में दस्तावेज़ आकार।

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


बाइट्स में दस्तावेज़ आकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageWidth | int |  |
| pageHeight | int |  |
| pageIndex | int |  |

**Returns:**
[PageInfo](../../com.groupdocs.signature.domain/pageinfo)
### getTextSignatures() {#getTextSignatures--}
```
public final List<TextSignature> getTextSignatures()
```


दस्तावेज़ पाठ हस्ताक्षरों का संग्रह।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


दस्तावेज़ छवि हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


दस्तावेज़ डिजिटल हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


दस्तावेज़ बारकोड हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


दस्तावेज़ QR-कोड हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


दस्तावेज़ फ़ॉर्म फ़ील्ड हस्ताक्षरों का संग्रह, जो [Signature](../../com.groupdocs.signature/signature) विधियों द्वारा जोड़े या अपडेट किए गए हैं।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


दस्तावेज़ में सभी मौजूदा समर्थित फ़ॉर्म फ़ील्ड्स का संग्रह। यह प्रॉपर्टी केवल Pdf और Word Processing दस्तावेज़ प्रकारों के लिए समर्थित है।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


दस्तावेज़ मेटाडेटा हस्ताक्षरों का संग्रह।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


दस्तावेज़ इतिहास प्रक्रियाओं जैसे साइन, अपडेट, डिलीट का संग्रह।

**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


दस्तावेज़ के सभी प्रकार के हस्ताक्षरों का संग्रह [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
