---
title: "PdfDigitalSignatureAppearance"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDFドキュメント上のデジタル署名の外観を説明します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

PDFドキュメント上のデジタル署名の外観を説明します。

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | デフォルト値で署名外観オブジェクトを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | 連絡先情報ラベルを取得または設定します。 |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | 連絡先情報ラベルを取得または設定します。 |
|
|  | [getReasonLabel()](#getReasonLabel--) | 理由ラベルを取得または設定します。 |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | 理由ラベルを取得または設定します。 |
|
|  | [getLocationLabel()](#getLocationLabel--) | 場所ラベルを取得または設定します。 |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | 場所ラベルを取得または設定します。 |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | デジタル署名ラベルを取得または設定します。 |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | デジタル署名ラベルを取得または設定します。 |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | 署名日ラベルを取得または設定します。 |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | 署名日ラベルを取得または設定します。 |
|
|  | [getBackground()](#getBackground--) | 署名の外観の背景色を取得または設定します。 |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | 署名の外観の背景色を取得または設定します。 |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | 署名の外観の背景色を取得または設定します。 |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | ラベルを表示するフォント ファミリ名を取得または設定します。 |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | ラベルを表示するフォント ファミリ名を取得または設定します。 |
|
|  | [getFontSize()](#getFontSize--) | ラベルを表示するフォント サイズを取得または設定します。 |
|
|  | [setFontSize(double value)](#setFontSize-double-) | ラベルを表示するフォント サイズを取得または設定します。 |
|
|  | [getForeground()](#getForeground--) | 署名の外観の前景テキスト色を取得または設定します。 |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | 署名の外観の前景テキスト色を取得または設定します。 |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | 署名の外観の前景テキスト色を取得または設定します。 |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


デフォルト値で署名外観オブジェクトを作成します。


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


連絡先情報ラベルを取得または設定します。デフォルト値: "Contact"。
この値が空の場合、デジタル署名領域に連絡先ラベルは表示されません。


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


連絡先情報ラベルを取得または設定します。デフォルト値: "Contact"。
この値が空の場合、デジタル署名領域に連絡先ラベルは表示されません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


理由ラベルを取得または設定します。デフォルト値: "Reason"。
この値が空の場合、デジタル署名領域に理由ラベルは表示されません。


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


理由ラベルを取得または設定します。デフォルト値: "Reason"。
この値が空の場合、デジタル署名領域に理由ラベルは表示されません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


場所ラベルを取得または設定します。デフォルト値: "Location"。
この値が空の場合、デジタル署名領域に場所ラベルは表示されません。


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


場所ラベルを取得または設定します。デフォルト値: "Location"。
この値が空の場合、デジタル署名領域に場所ラベルは表示されません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


デジタル署名ラベルを取得または設定します。デフォルト値: "Digitally signed by"。


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


デジタル署名ラベルを取得または設定します。デフォルト値: "Digitally signed by"。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


署名日ラベルを取得または設定します。デフォルト値: "Date"。


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


署名日ラベルを取得または設定します。デフォルト値: "Date"。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


署名の外観の背景色を取得または設定します。
デフォルトでは値は SystemColors.Windows です。


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


署名の外観の背景色を取得または設定します。
デフォルトでは値は SystemColors.Windows です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


署名の外観の背景色を取得または設定します。
デフォルトでは値は SystemColors.Windows です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


ラベルを表示するフォント ファミリ名を取得または設定します。デフォルト値は "Arial" です。


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


ラベルを表示するフォント ファミリ名を取得または設定します。デフォルト値は "Arial" です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


ラベルを表示するフォント サイズを取得または設定します。デフォルト値は 10 です。


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


ラベルを表示するフォント サイズを取得または設定します。デフォルト値は 10 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


署名の外観の前景テキスト色を取得または設定します。
デフォルトでは値は Color.FromArgb(76, 100, 255) です。


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


署名の外観の前景テキスト色を取得または設定します。
デフォルトでは値は Color.FromArgb(76, 100, 255) です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


署名の外観の前景テキスト色を取得または設定します。
デフォルトでは値は Color.FromArgb(76, 100, 255) です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

