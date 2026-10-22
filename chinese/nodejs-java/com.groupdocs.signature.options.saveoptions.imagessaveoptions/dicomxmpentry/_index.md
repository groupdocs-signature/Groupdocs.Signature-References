---
title: "DicomXmpEntry"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "DICOM 图像 .dcm 的 XMP 数据条目。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

DICOM 图像（.dcm）的 XMP 数据入口。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | 为 DICOM 图像创建 XMP 条目。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 条目类型。 |
| [getValue()](#getValue--) | 条目值。 |
| [toString()](#toString--) | 获取 XMP 条目的文本表示。 |
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


为 DICOM 图像创建 XMP 条目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | int | 条目类型 |
| 值 | java.lang.String | 条目值 |

### getType() {#getType--}
```
public final int getType()
```


条目类型。

**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


条目值。

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


获取 XMP 条目的文本表示。

**Returns:**
java.lang.String - XMP 条目的文本表示。
