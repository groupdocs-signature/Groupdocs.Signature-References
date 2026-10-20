---
title: "TextureBrush"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "テクスチャーブラシを表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

テクスチャーブラシを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | TextureBrush クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | TextureBrush クラスの新しいインスタンスを画像ファイルで初期化します。 |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | TextureBrush クラスの新しいインスタンスを画像ストリームオプションで初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | テクスチャ画像ファイルのパスを取得または設定します。 |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | テクスチャ画像ファイルのパスを取得または設定します。 |
|
|  | [getImageStream()](#getImageStream--) | テクスチャ画像ストリームを取得または設定します。 |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | テクスチャ画像ストリームを取得または設定します。 |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


TextureBrush クラスの新しいインスタンスをデフォルト値で初期化します。


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


TextureBrush クラスの新しいインスタンスを画像ファイルで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | 画像ファイルのパス。 |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


TextureBrush クラスの新しいインスタンスを画像ストリームオプションで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | 画像ストリーム。 |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


テクスチャ画像ファイルのパスを取得または設定します。
このプロパティは ImageStream が指定されていない場合にのみ使用されます。


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


テクスチャ画像ファイルのパスを取得または設定します。
このプロパティは ImageStream が指定されていない場合にのみ使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


テクスチャ画像ストリームを取得または設定します。
このプロパティが指定されている場合、常に ImageFilePath の代わりに使用されます。


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


テクスチャ画像ストリームを取得または設定します。
このプロパティが指定されている場合、常に ImageFilePath の代わりに使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.io.InputStream |  |

