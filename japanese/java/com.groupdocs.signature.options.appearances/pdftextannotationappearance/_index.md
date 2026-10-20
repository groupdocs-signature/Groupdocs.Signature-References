---
title: "PdfTextAnnotationAppearance"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDF テキスト注釈オブジェクトの Title、Subject、Content の外観を説明します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

PDFテキスト注釈オブジェクト（タイトル、サブジェクト、コンテンツ）の外観を説明します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | PDF 署名テキスト注釈の外観オブジェクトを作成します。 |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | 指定された値（title、subject、contents）で PDF 署名テキスト注釈を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getContents()](#getContents--) | 注釈オブジェクトの内容を取得または設定します。 |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | 注釈オブジェクトの内容を取得または設定します。 |
|
|  | [getSubject()](#getSubject--) | オブジェクトの説明を表す Subject を取得または設定します。 |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | オブジェクトの説明を表す Subject を取得または設定します。 |
|
|  | [getTitle()](#getTitle--) | 注釈オブジェクトのタイトルバーに表示される Title を取得または設定します。 |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | 注釈オブジェクトのタイトルバーに表示される Title を取得または設定します。 |
|
|  | [getBorder()](#getBorder--) | さまざまな枠線設定を取得または設定します。 |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | さまざまな枠線設定を取得または設定します。 |
|
|  | [getBorderEffect()](#getBorderEffect--) | 枠線効果を取得または設定します。 |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | 枠線効果を取得または設定します。 |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | 境界効果の強度を取得または設定します。 |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | 境界効果の強度を取得または設定します。 |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | 水平コーナー半径を取得または設定します。 |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | 水平コーナー半径を取得または設定します。 |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | 垂直コーナー半径を取得または設定します。 |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | 垂直コーナー半径を取得または設定します。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


PDF 署名テキスト注釈の外観オブジェクトを作成します。


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


指定された値（title、subject、contents）で PDF 署名テキスト注釈を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | タイトル | java.lang.String | タイトル。 |
|
|  | 件名 | java.lang.String | 件名。 |
|
|  | 内容 | java.lang.String | 内容。 |
|

### getContents() {#getContents--}
```
public final String getContents()
```


注釈オブジェクトの内容を取得または設定します。


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


注釈オブジェクトの内容を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


オブジェクトの説明を表す Subject を取得または設定します。


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


オブジェクトの説明を表す Subject を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


注釈オブジェクトのタイトルバーに表示される Title を取得または設定します。


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


注釈オブジェクトのタイトルバーに表示される Title を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


さまざまな枠線設定を取得または設定します。


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


さまざまな枠線設定を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


枠線効果を取得または設定します。


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


枠線効果を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


境界効果の強度を取得または設定します。値の有効範囲は [0..2] です。


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


境界効果の強度を取得または設定します。値の有効範囲は [0..2] です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


水平コーナー半径を取得または設定します。


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


水平コーナー半径を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


垂直コーナー半径を取得または設定します。


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


垂直コーナー半径を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
