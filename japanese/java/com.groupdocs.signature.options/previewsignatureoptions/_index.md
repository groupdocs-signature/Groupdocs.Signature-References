---
title: "PreviewSignatureOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名プレビューオプションを表します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

署名プレビューオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | PreviewSignatureOptions オブジェクトを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | 署名を区別するためのユニークな値。 |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | 署名を区別するためのユニークな値。 |
|
|  | [getSignOptions()](#getSignOptions--) | プレビュー生成のための署名オプション。 |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | プレビュー生成のための署名オプション。 |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | プレビュー画像の形式を取得または設定します。 |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | プレビュー画像の形式を取得または設定します。 |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


PreviewSignatureOptions オブジェクトを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | プレビューを生成するための署名オプション。 |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | 出力ページプレビュー ストリームを作成するメソッドを定義するインターフェイス。 |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


署名を区別するためのユニークな値。
プレビューオプションを識別するために SignatureId を使用します。


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


署名を区別するためのユニークな値。
プレビューオプションを識別するために SignatureId を使用します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


プレビュー生成のための署名オプション。


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


プレビュー生成のための署名オプション。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


プレビュー画像の形式を取得または設定します。
デフォルト値は PNG です。


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


プレビュー画像の形式を取得または設定します。
デフォルト値は PNG です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

