---
title: "PdfTextStickerAppearance"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDFテキスト注釈ステッカーオブジェクトとステッカーのポップアップウィンドウの外観を説明します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

PDFテキスト注釈ステッカーオブジェクトとステッカーのポップアップウィンドウの外観を説明します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | PDF 署名テキスト注釈の外観オブジェクトを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getTitle()](#getTitle--) | ポップアップウィンドウのタイトルを取得または設定します。 |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | ポップアップウィンドウのタイトルを取得または設定します。 |
|
|  | [getSubject()](#getSubject--) | 件名を取得または設定します。 |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | 件名を取得または設定します。 |
|
|  | [getContents()](#getContents--) | ポップアップウィンドウの内容を取得または設定します。 |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | ポップアップウィンドウの内容を取得または設定します。 |
|
|  | [getOpened()](#getOpened--) | ステッカーのポップアップウィンドウをデフォルトで開くか設定します。 |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | ステッカーのポップアップウィンドウをデフォルトで開くか設定します。 |
|
|  | [getIcon()](#getIcon--) | ステッカーのアイコンを取得または設定します。 |
|
|  | [setIcon(int value)](#setIcon-int-) | ステッカーのアイコンを取得または設定します。 |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | ステッカーのデフォルト外観を取得します。 |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | ステッカーのデフォルト外観の値をクリアします。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


PDF 署名テキスト注釈の外観オブジェクトを作成します。


### getTitle() {#getTitle--}
```
public final String getTitle()
```


ポップアップウィンドウのタイトルを取得または設定します。


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


ポップアップウィンドウのタイトルを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


件名を取得または設定します。


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


件名を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


ポップアップウィンドウの内容を取得または設定します。


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


ポップアップウィンドウの内容を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


ステッカーのポップアップウィンドウをデフォルトで開くか設定します。


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


ステッカーのポップアップウィンドウをデフォルトで開くか設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


ステッカーのアイコンを取得または設定します。


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


ステッカーのアイコンを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


ステッカーのデフォルト外観を取得します。これらのプロパティは、次の場合にデフォルトとして適用されます。
Options.SignatureAppearance プロパティが指定されていない場合です。
これらのプロパティはユーザーによっていつでも変更可能です。


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


ステッカーのデフォルト外観の値をクリアします。


### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
