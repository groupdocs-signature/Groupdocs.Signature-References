---
title: "FormFieldSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "フォームフィールド署名のプロパティを含みます。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

フォームフィールド署名のプロパティを含みます。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | 一意のフォームフィールド名を指定します。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 一意のフォームフィールド名を指定します。 |
|
|  | [getType()](#getType--) | フォームフィールドのタイプを指定します。 |
|
|  | [getValue()](#getValue--) | フォームフィールドのデータオブジェクトを指定します。 |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | フォームフィールドのデータオブジェクトを指定します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | FormField Signature インスタンスをクローンします。 |
|
### getName() {#getName--}
```
public final String getName()
```


一意のフォームフィールド名を指定します。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


一意のフォームフィールド名を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


フォームフィールドのタイプを指定します。


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


フォームフィールドのデータオブジェクトを指定します。


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


フォームフィールドのデータオブジェクトを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


署名プロパティを比較するために Equals メソッドをオーバーライドします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signature | java.lang.Object | 比較対象となる Signature オブジェクト。 |
|

**Returns:**
boolean - 渡された signature オブジェクトが同じ型であり、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int - Signature のハッシュコード

### deepClone() {#deepClone--}
```
public Object deepClone()
```


FormField Signature インスタンスをクローンします。


**Returns:**
java.lang.Object - クローンされた FormField Signature インスタンスを返します。

