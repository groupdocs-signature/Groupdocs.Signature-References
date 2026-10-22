---
title: "ImageSearchOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "इमेज हस्ताक्षरों के लिए खोज विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

इमेज हस्ताक्षरों के लिए खोज विकल्पों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ImageSearchOptions()](#ImageSearchOptions--) | डिफ़ॉल्ट मानों के साथ ImageSearchOptions वर्ग का नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getReturnContent()](#getReturnContent--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की छवि सामग्री को प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की छवि सामग्री को प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
| [getMinContentSize()](#getMinContentSize--) | शून्य से अलग मान के लिए यह फ़्लैग खोज मानदंडों के लिए छवियों का न्यूनतम आकार निर्दिष्ट करता है। |
| [setMinContentSize(long value)](#setMinContentSize-long-) | शून्य से अलग मान के लिए यह फ़्लैग खोज मानदंडों के लिए छवियों का न्यूनतम आकार निर्दिष्ट करता है। |
| [getMaxContentSize()](#getMaxContentSize--) | शून्य से अलग मान के लिए यह फ़्लैग खोज मानदंडों के लिए छवियों का अधिकतम आकार निर्दिष्ट करता है। |
| [setMaxContentSize(long value)](#setMaxContentSize-long-) | शून्य से अलग मान के लिए यह फ़्लैग खोज मानदंडों के लिए छवियों का अधिकतम आकार निर्दिष्ट करता है। |
| [getReturnContentType()](#getReturnContentType--) | जब ReturnContent प्रॉपर्टी सक्षम हो तो छवि हस्ताक्षर की लौटाई गई सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | जब ReturnContent प्रॉपर्टी सक्षम हो तो छवि हस्ताक्षर की लौटाई गई सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। |
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


डिफ़ॉल्ट मानों के साथ ImageSearchOptions वर्ग का नया उदाहरण प्रारंभ करता है।

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की छवि सामग्री को प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है। यदि यह फ़्लैग true पर सेट किया जाता है, तो छवि हस्ताक्षर सामग्री आवश्यक प्रारूप ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)) द्वारा कच्चा छवि डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प अक्षम है।

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की छवि सामग्री को प्राप्त करने के लिए फ़्लैग प्राप्त करता है या सेट करता है। यदि यह फ़्लैग true पर सेट किया जाता है, तो छवि हस्ताक्षर सामग्री आवश्यक प्रारूप ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)) द्वारा कच्चा छवि डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प अक्षम है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


शून्य से अलग मान के लिए यह फ़्लैग खोज मानदंडों के लिए छवियों का न्यूनतम आकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह फ़्लैग शून्य पर सेट है और खोज परिणाम को प्रभावित नहीं करता।

**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


शून्य से अलग मान के लिए यह फ़्लैग खोज मानदंडों के लिए छवियों का न्यूनतम आकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह फ़्लैग शून्य पर सेट है और खोज परिणाम को प्रभावित नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


शून्य से अलग मान के लिए यह फ़्लैग खोज मानदंडों के लिए छवियों का अधिकतम आकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह फ़्लैग शून्य पर सेट है और खोज परिणाम को प्रभावित नहीं करता।

**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


शून्य से अलग मान के लिए यह फ़्लैग खोज मानदंडों के लिए छवियों का अधिकतम आकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह फ़्लैग शून्य पर सेट है और खोज परिणाम को प्रभावित नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


जब ReturnContent प्रॉपर्टी सक्षम हो तो छवि हस्ताक्षर की लौटाई गई सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह Null पर सेट है। इसका अर्थ है कि छवि सामग्री मूल प्रारूप में लौटाई जाएगी। यह छवि प्रारूप ImageSignature.Format पर निर्दिष्ट किया गया है। संभावित समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया प्रारूप समर्थित नहीं है तो मूल प्रारूप में छवि सामग्री लौटाई जाएगी।

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


जब ReturnContent प्रॉपर्टी सक्षम हो तो छवि हस्ताक्षर की लौटाई गई सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह Null पर सेट है। इसका अर्थ है कि छवि सामग्री मूल प्रारूप में लौटाई जाएगी। यह छवि प्रारूप ImageSignature.Format पर निर्दिष्ट किया गया है। संभावित समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया प्रारूप समर्थित नहीं है तो मूल प्रारूप में छवि सामग्री लौटाई जाएगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

