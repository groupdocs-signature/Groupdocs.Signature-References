---
title: "DigitalFormFieldSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDF ドキュメント用のデジタル署名入力フォームフィールドのプロパティを含みます。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object、[com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)、[com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

PDF ドキュメント用のデジタル署名入力フォームフィールドのプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | 事前定義された名前で PdfDigitalFormFieldSignature を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSigned()](#getSigned--) | デジタル証明書で署名されたかどうかを示す読み取り専用プロパティです。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | FormField Signature インスタンスをクローンします。 |
|
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


事前定義された名前で PdfDigitalFormFieldSignature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドオブジェクトの名前。 |
|

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


デジタル証明書で署名されたかどうかを示す読み取り専用プロパティです。


**Returns:**
boolean
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

