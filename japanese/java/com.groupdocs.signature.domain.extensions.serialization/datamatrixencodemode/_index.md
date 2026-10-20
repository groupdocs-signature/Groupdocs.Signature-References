---
title: "DataMatrixEncodeMode"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "DataMatrix エンコーダーのエンコーディングモードはデフォルトで Auto です。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

DataMatrix エンコーダのエンコーディングモード（デフォルトは Auto）

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Auto](#Auto) | DataMatrix エンコードの最適なエンコードモードを自動的に選択します |
|
|  | [ASCII](#ASCII) | 1 バイトあたり、1 つの英数字または 2 つの数字文字をエンコードします |
|
|  | [Full](#Full) | 8 ビット値をエンコードします |
|
|  | [Custom](#Custom) | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding で指定されたエンコーディングでエンコードします |
|
|  | [C40](#C40) | C40 エンコーディングを使用します。 |
|
|  | [Text](#Text) | テキストエンコーディングを使用します。 |
|
|  | [EDIFACT](#EDIFACT) | EDIFACT エンコーディングを使用します。 |
|
|  | [ANSIX12](#ANSIX12) | ANSI X12 エンコーディングを使用します。 |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | ExtendedCodetext モードでは、コードテキスト内でエンコーディング方式を手動で切り替えることができます。 |
|
### Auto {#Auto}
```
public static final int Auto
```


DataMatrix エンコードの最適なエンコードモードを自動的に選択します


### ASCII {#ASCII}
```
public static final int ASCII
```


1 バイトあたり、1 つの英数字または 2 つの数字文字をエンコードします


### Full {#Full}
```
public static final int Full
```


8 ビット値をエンコードします


### Custom {#Custom}
```
public static final int Custom
```


BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding で指定されたエンコーディングでエンコードします


### C40 {#C40}
```
public static final int C40
```


C40 エンコーディングを使用します。大文字の英数字、 小文字および特殊文字をエンコードします


### Text {#Text}
```
public static final int Text
```


テキストエンコーディングを使用します。小文字の英数字、 大文字および特殊文字をエンコードします。


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


EDIFACT エンコーディングを使用します。文字ごとに 6 ビットを使用し、数字をエンコードします、
大文字、 多くの句読点をエンコードしますが、 小文字はサポートされていません。


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


ANSI X12 エンコーディングを使用します。


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


ExtendedCodetext モードでは、コードテキスト内でエンコーディング方式を手動で切り替えることができます。
形式: "\\Encodation_scheme_name:text\\Encodation_scheme_name:text"。
使用可能なエンコーディング方式は次のとおりです: EDIFACT, ANSIX12, ASCII, C40, Text, Auto。
拡張コードテキスト例: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
doubled\\edifact:EdifactEncodedText\"
テキスト内のすべてのバックスラッシュ (\\) は二重にする必要があります。


