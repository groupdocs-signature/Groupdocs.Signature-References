---
title: DicomXmpEntry
second_title: GroupDocs.Signature for Java API Reference
description: Entry of XMP data for DICOM images .dcm.
type: docs
weight: 13
url: /java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

Entry of XMP data for DICOM images (.dcm).
## Constructors

| Constructor | Description |
| --- | --- |
| [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | Creates Xmp entry for DICOM image. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Entry type. |
| [getValue()](#getValue--) | Entry value. |
| [toString()](#toString--) | Get Xmp entry textual representation. |
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


Creates Xmp entry for DICOM image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Entry type |
| value | java.lang.String | Entry value |

### getType() {#getType--}
```
public final int getType()
```


Entry type.

**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


Entry value.

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Get Xmp entry textual representation.

**Returns:**
java.lang.String - Xmp entry textual representation.
