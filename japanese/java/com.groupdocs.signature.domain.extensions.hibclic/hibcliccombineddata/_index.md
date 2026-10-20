---
title: "HIBCLICCombinedData"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）の一次データと二次データエンティティを含む結合データを格納するクラス。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.extensions.hibclic/hibcliccombineddata/
---
**Inheritance:**
java.lang.Object
```
public class HIBCLICCombinedData
```

一次および二次データエンティティを含む、HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）結合データを格納するクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [HIBCLICCombinedData()](#HIBCLICCombinedData--) | 一次および二次データのデフォルト値を使用して、HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）結合データを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPrimaryData()](#getPrimaryData--) | HIBC LIC の一次データ構造 |
|
|  | [setPrimaryData(HIBCLICPrimaryData value)](#setPrimaryData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICPrimaryData-) | HIBC LIC の一次データ構造 |
|
|  | [getSecondaryAdditionalData()](#getSecondaryAdditionalData--) | HIBC LIC 二次データ構造 |
|
|  | [setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value)](#setSecondaryAdditionalData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICSecondaryAdditionalData-) | HIBC LIC 二次データ構造 |
|
|  | [deepClone()](#deepClone--) | このオブジェクトのコピーを取得します。 |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICCombinedData() {#HIBCLICCombinedData--}
```
public HIBCLICCombinedData()
```


一次および二次データのデフォルト値を使用して、HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）結合データを作成します。


### getPrimaryData() {#getPrimaryData--}
```
public final HIBCLICPrimaryData getPrimaryData()
```


HIBC LIC の一次データ構造


**Returns:**
[HIBCLICPrimaryData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata)
### setPrimaryData(HIBCLICPrimaryData value) {#setPrimaryData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICPrimaryData-}
```
public final void setPrimaryData(HIBCLICPrimaryData value)
```


HIBC LIC の一次データ構造


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [HIBCLICPrimaryData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata) |  |

### getSecondaryAdditionalData() {#getSecondaryAdditionalData--}
```
public final HIBCLICSecondaryAdditionalData getSecondaryAdditionalData()
```


HIBC LIC 二次データ構造


**Returns:**
[HIBCLICSecondaryAdditionalData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata)
### setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value) {#setSecondaryAdditionalData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICSecondaryAdditionalData-}
```
public final void setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value)
```


HIBC LIC 二次データ構造


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [HIBCLICSecondaryAdditionalData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata) |  |

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
