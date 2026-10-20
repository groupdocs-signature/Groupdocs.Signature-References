---
title: "TextFormFieldSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDF ドキュメント用のテキスト入力フォームフィールド署名のプロパティを含みます。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object、[com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)、[com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

PDF ドキュメント用のテキスト入力フォームフィールド署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | 事前定義された名前で PdfTextFormFieldSignature を作成します。 |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | 事前定義された名前で PdfTextFormFieldSignature を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getText()](#getText--) | フォームフィールドのテキスト入力のテキストを取得または設定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | フォームフィールドのテキスト入力のテキストを取得または設定します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | FormField Signature インスタンスをクローンします。 |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


事前定義された名前で PdfTextFormFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


事前定義された名前で PdfTextFormFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|
|  | テキスト | java.lang.String | フォームフィールドオブジェクトのテキスト。 |
|

### getText() {#getText--}
```
public final String getText()
```


フォームフィールドのテキスト入力のテキストを取得または設定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


フォームフィールドのテキスト入力のテキストを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

