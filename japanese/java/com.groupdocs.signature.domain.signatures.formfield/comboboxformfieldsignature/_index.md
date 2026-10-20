---
title: "ComboboxFormFieldSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "コンボボックス入力フォームフィールド署名のプロパティを含みます。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object、[com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)、[com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

コンボボックス入力フォームフィールド署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | 事前定義された名前で ComboboxFormFieldSignature を作成します。 |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | 事前定義された名前とオプションリストで ComboboxFormFieldSignature を作成します。 |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | 事前定義された名前、オプションリスト、選択された値で ComboboxFormFieldSignature を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSelected()](#getSelected--) | 選択された値を取得または設定します。 |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | 選択された値を取得または設定します。 |
|
|  | [getItems()](#getItems--) | コンボボックスのオプションリストを取得または設定します。 |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | コンボボックスのオプションリストを取得または設定します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | FormField Signature インスタンスをクローンします。 |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


事前定義された名前で ComboboxFormFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


事前定義された名前とオプションリストで ComboboxFormFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|
|  | items | java.util.List<java.lang.String> | コンボボックスリストの値。 |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


事前定義された名前、オプションリスト、選択された値で ComboboxFormFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|
|  | items | java.util.List<java.lang.String> | コンボボックスリストの値。 |
|
|  | selected | java.lang.Object | 選択された値。 |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


選択された値を取得または設定します。


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


選択された値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


コンボボックスのオプションリストを取得または設定します。


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


コンボボックスのオプションリストを取得または設定します。


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

