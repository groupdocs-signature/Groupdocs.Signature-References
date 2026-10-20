---
title: "TextSignatureImplementation"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDFテキスト署名の実装タイプを指定します。"
type: docs
weight: 32
url: /ja/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

PDFテキスト署名の実装タイプを指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Native](#Native) | テキスト署名をドキュメントページ上のネイティブテキストオブジェクトとして使用します。 |
|
|  | [Image](#Image) | テキスト署名をドキュメントページ上の画像オブジェクトとして使用します。 |
|
|  | [Annotation](#Annotation) | テキスト署名をPDFページ上のテキスト注釈オブジェクトとして使用します。 |
|
|  | [Sticker](#Sticker) | テキスト署名をPDFページ上のステッカーオブジェクトとして使用します。 |
|
|  | [FormField](#FormField) | テキスト署名を指定されたフォームフィールド内のテキストとして使用します。 |
|
|  | [Watermark](#Watermark) | テキスト署名をドキュメントページ上の透かしとして使用します。 |
|
### Native {#Native}
```
public static final int Native
```


テキスト署名をドキュメントページ上のネイティブテキストオブジェクトとして使用します。


### Image {#Image}
```
public static final int Image
```


テキスト署名をドキュメントページ上の画像オブジェクトとして使用します。


### Annotation {#Annotation}
```
public static final int Annotation
```


テキスト署名をPDFページ上のテキスト注釈オブジェクトとして使用します。
注釈はライセンス版でのみ表示されます。


### Sticker {#Sticker}
```
public static final int Sticker
```


テキスト署名をPDFページ上のステッカーオブジェクトとして使用します。


### FormField {#FormField}
```
public static final int FormField
```


テキスト署名を指定されたフォームフィールド内のテキストとして使用します。
この実装タイプでは TextSignOptions.Text のみ使用できます、
TextSignOptions.FormTextFieldType と TextSignOptions.FormTextFieldTitle オプション。


### Watermark {#Watermark}
```
public static final int Watermark
```


テキスト署名をドキュメントページ上の透かしとして使用します。


