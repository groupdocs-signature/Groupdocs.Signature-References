---
title: "FormFieldSignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDFドキュメント用のFormField署名オプションのクラスを表します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

PDFドキュメント用のFormField署名オプションのクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FormFieldSignOptions()](#FormFieldSignOptions--) | PdfFormFieldSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | PdfFormFieldSignOptions クラスの新しいインスタンスを FormField 署名で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSignature()](#getSignature--) | 署名の FormField を取得または設定します。 |
|
|  | [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | 署名の FormField を取得または設定します。 |
|
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


PdfFormFieldSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


PdfFormFieldSignOptions クラスの新しいインスタンスを FormField 署名で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


署名の FormField を取得または設定します。


**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


署名の FormField を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

