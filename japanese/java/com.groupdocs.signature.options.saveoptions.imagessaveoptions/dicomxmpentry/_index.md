---
title: "DicomXmpEntry"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "DICOM 画像（.dcm）の XMP データエントリ。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

DICOM 画像（.dcm）の XMP データのエントリです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | DICOM 画像用の XMP エントリを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getType()](#getType--) | エントリのタイプ。 |
|
|  | [getValue()](#getValue--) | エントリの値。 |
|
|  | [toString()](#toString--) | XMP エントリのテキスト表現を取得します。 |
|
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


DICOM 画像用の XMP エントリを作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | タイプ | int | エントリのタイプ |
|
|  | 値 | java.lang.String | エントリの値 |
|

### getType() {#getType--}
```
public final int getType()
```


エントリのタイプ。


**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


エントリの値。


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


XMP エントリのテキスト表現を取得します。


**Returns:**
java.lang.String - XMP エントリのテキスト表現。

