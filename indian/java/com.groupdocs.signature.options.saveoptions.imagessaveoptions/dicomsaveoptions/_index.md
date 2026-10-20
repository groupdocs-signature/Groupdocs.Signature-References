---
title: "DicomSaveOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "DICOM इमेज दस्तावेज़ों के लिए सहेजने विकल्प।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

DICOM इमेज दस्तावेज़ों के लिए सहेजने विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | डिफ़ॉल्ट मानों के साथ DicomSaveOptions बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | DICOM के लिए XMP डेटा। |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | DICOM के लिए XMP डेटा। |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


डिफ़ॉल्ट मानों के साथ DicomSaveOptions बनाता है।


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


DICOM के लिए XMP डेटा। इसे इमेज मेटाडेटा सेट करने के लिए उपयोग करें।


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


DICOM के लिए XMP डेटा। इसे इमेज मेटाडेटा सेट करने के लिए उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

