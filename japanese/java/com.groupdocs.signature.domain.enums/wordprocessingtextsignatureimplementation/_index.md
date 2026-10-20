---
title: "WordProcessingTextSignatureImplementation"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "WordProcessing ドキュメントのテキスト署名実装タイプを指定します。"
type: docs
weight: 36
url: /ja/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

WordProcessing ドキュメントのテキスト署名実装タイプを指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [TextStamp](#TextStamp) | Words ページ上のラベルオブジェクトとしてのテキスト署名です。 |
|
|  | [TextAsImage](#TextAsImage) | Words ページ上の画像オブジェクトとしてのテキスト署名です。 |
|
|  | [TextToFormField](#TextToFormField) | テキスト署名を指定されたフォームフィールド内のテキストとして使用します。 |
|
|  | [Watermark](#Watermark) | Words ページ上の透かしとしてのテキスト署名です。 |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Words ページ上のラベルオブジェクトとしてのテキスト署名です。


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Words ページ上の画像オブジェクトとしてのテキスト署名です。


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


テキスト署名を指定されたフォームフィールド内のテキストとして使用します。
この実装タイプでは TextSignOptions.Text のみ使用できます、
TextSignOptions.FormTextFieldTitle と TextSignOptions.FormTextFieldType のオプションです。


### Watermark {#Watermark}
```
public static final int Watermark
```


Words ページ上の透かしとしてのテキスト署名です。


