---
title: "SymmetricEncryption"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "単一キーとパスフレーズソルトを使用したデータ暗号化のための標準的な対称アルゴリズムを実装します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

単一キーとパスフレーズ（ソルト）を使用したデータ暗号化のための標準的な対称アルゴリズムを実装します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | パラメータで対称暗号化アルゴリズムを作成します。 |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | デフォルトのパスフレーズで対称暗号化アルゴリズムを作成します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | 対称アルゴリズムのタイプを取得または設定します。 |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | 対称アルゴリズムのタイプを取得または設定します。 |
|
|  | [getKey()](#getKey--) | 暗号化アルゴリズムのキーを取得または設定します。 |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | 暗号化アルゴリズムのキーを取得または設定します。 |
|
|  | [getSalt()](#getSalt--) | 暗号化アルゴリズムのパスフレーズを取得または設定します。 |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | 暗号化アルゴリズムのパスフレーズを取得または設定します。 |
|
|  | [encode(String source)](#encode-java.lang.String-) | 指定されたアルゴリズムタイプ、キー、ソルトパラメータに基づいて文字列を暗号化します |
|
|  | [decode(String source)](#decode-java.lang.String-) | 指定されたアルゴリズムタイプ、キー、ソルトパラメータに基づいて文字列を復号化します |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


パラメータで対称暗号化アルゴリズムを作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | algorithmType | int | 対称アルゴリズムのタイプを指定してください |
|
|  | key | java.lang.String | 暗号化キー |
|
|  | ソルト | java.lang.String | 暗号化用パスフレーズ |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


デフォルトのパスフレーズで対称暗号化アルゴリズムを作成します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | algorithmType | int | 対称アルゴリズムのタイプを指定してください |
|
|  | key | java.lang.String | 暗号化キー |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


対称アルゴリズムのタイプを取得または設定します。


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


対称アルゴリズムのタイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


暗号化アルゴリズムのキーを取得または設定します。


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


暗号化アルゴリズムのキーを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


暗号化アルゴリズムのパスフレーズを取得または設定します。


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


暗号化アルゴリズムのパスフレーズを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


指定されたアルゴリズムタイプ、キー、ソルトパラメータに基づいて文字列を暗号化します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ソース | java.lang.String | エンコードする元文字列。 |
|

**Returns:**
java.lang.String - 暗号化された文字列を返します。

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


指定されたアルゴリズムタイプ、キー、ソルトパラメータに基づいて文字列を復号化します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ソース | java.lang.String | 復号化する暗号化文字列。 |
|

**Returns:**
java.lang.String - 復号化された文字列を返します。

