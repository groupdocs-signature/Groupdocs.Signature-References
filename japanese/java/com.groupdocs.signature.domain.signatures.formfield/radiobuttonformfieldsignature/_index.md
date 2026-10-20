---
title: "RadioButtonFormFieldSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ラジオボタン入力フォームフィールド署名のプロパティを含みます。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object、[com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)、[com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

ラジオボタン入力フォームフィールド署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | 事前定義された名前で RadioButtonFieldSignature を作成します。 |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | 事前定義された名前と項目リストで RadioButtonFieldSignature を作成します。 |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | 事前定義された名前、項目リスト、選択された値で RadioButtonFieldSignature を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSelected()](#getSelected--) | 選択された値を含みます。 |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | 選択された値を含みます。 |
|
|  | [getItems()](#getItems--) | Radio ボタンのオプションリストを取得または設定します。 |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Radio ボタンのオプションリストを取得または設定します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | FormField Signature インスタンスをクローンします。 |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


事前定義された名前で RadioButtonFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


事前定義された名前と項目リストで RadioButtonFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|
|  | items | java.util.List<java.lang.String> | ラジオボタンリストの値。 |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


事前定義された名前、項目リスト、選択された値で RadioButtonFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|
|  | items | java.util.List<java.lang.String> | ラジオボタンリストの値。 |
|
|  | selected | java.lang.Object | 選択された値。 |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


選択された値を含みます。


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


選択された値を含みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Radio ボタンのオプションリストを取得または設定します。


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Radio ボタンのオプションリストを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<java.lang.String> |  |

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

