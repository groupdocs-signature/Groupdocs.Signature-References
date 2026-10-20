---
title: "CheckboxFormFieldSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "チェックボックス入力フォームフィールド署名のプロパティを含みます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object、[com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)、[com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

チェックボックス入力フォームフィールド署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | 事前定義された名前で PdfCheckboxFormFieldSignature を作成します。 |
|
|  | [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | 事前定義された名前と値で PdfCheckboxFormFieldSignature を作成します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getChecked()](#getChecked--) | フォームフィールドのチェックボックス入力のチェックされた値を取得または設定します。 |
|
|  | [setChecked(boolean value)](#setChecked-boolean-) | フォームフィールドのチェックボックス入力のチェックされた値を取得または設定します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | FormField Signature インスタンスをクローンします。 |
|
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


事前定義された名前で PdfCheckboxFormFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


事前定義された名前と値で PdfCheckboxFormFieldSignature を作成します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|
|  | isChecked | boolean | チェックボックスがチェックされた場合の値 |
|

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


フォームフィールドのチェックボックス入力のチェックされた値を取得または設定します。


**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


フォームフィールドのチェックボックス入力のチェックされた値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

