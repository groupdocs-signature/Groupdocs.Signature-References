---
title: "HIBCLICPrimaryData"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code の主要データを格納するクラスです。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）の一次データを格納するクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | 既定 ctor() |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | ラベラー識別コードの日付を識別します。 |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | ラベラー識別コードの日付を識別します。 |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | 製品またはカタログ番号を識別します。 |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | 製品またはカタログ番号を識別します。 |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | 測定単位 ID を識別します。 |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | 測定単位 ID を識別します。 |
|
|  | [deepClone()](#deepClone--) | このオブジェクトのコピーを取得します。 |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


既定 ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


ラベラー識別コードの日付を識別します。ラベラー識別コードは必要です
先頭文字が必ず英字である、4文字の英数字文字列であること。


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


ラベラー識別コードの日付を識別します。ラベラー識別コードは必要です
先頭文字が必ず英字である、4文字の英数字文字列であること。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


製品またはカタログ番号を識別します。製品またはカタログ番号は英数字である必要があります。
最大18文字の文字列です。


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


製品またはカタログ番号を識別します。製品またはカタログ番号は英数字である必要があります。
最大18文字の文字列です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


測定単位IDを識別します。測定単位IDは0から9までの整数である必要があります。


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


測定単位IDを識別します。測定単位IDは0から9までの整数である必要があります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


このオブジェクトのコピーを取得します。


**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
