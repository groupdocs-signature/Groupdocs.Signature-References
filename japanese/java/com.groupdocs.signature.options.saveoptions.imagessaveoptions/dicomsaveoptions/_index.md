---
title: "DicomSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "DICOM 画像ドキュメント用の保存オプションです。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

DICOM 画像ドキュメント用の保存オプションです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | デフォルト値で DicomSaveOptions を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | DICOM 用の XMP データ。 |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | DICOM 用の XMP データ。 |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


デフォルト値で DicomSaveOptions を作成します。


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


DICOM 用の XMP データ。画像メタデータの設定に使用します。


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


DICOM 用の XMP データ。画像メタデータの設定に使用します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

