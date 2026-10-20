---
title: "StampLine"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Damga çizgi özelliklerini belirtin."
type: docs
weight: 13
url: /tr/java/com.groupdocs.signature.domain.stamps/stampline/
---
**Inheritance:**
java.lang.Object
```
public class StampLine
```

Damga çizgi özelliklerini belirtin.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [StampLine()](#StampLine--) | Varsayılan değerlerle StampLine oluştur. |
|
|  | [StampLine(String text)](#StampLine-java.lang.String-) | Metinle StampLine oluştur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getHeight()](#getHeight--) | Stamp üzerindeki satır yüksekliğini alır veya ayarlar. |
|
|  | [setHeight(int value)](#setHeight-int-) | Stamp üzerindeki satır yüksekliğini alır veya ayarlar. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | İmzanın arka plan rengini alır veya ayarlar. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | İmzanın arka plan rengini alır veya ayarlar. |
|
|  | [setBackgroundColor(String value)](#setBackgroundColor-java.lang.String-) | İmzanın arka plan rengini alır veya ayarlar. |
|
|  | [getText()](#getText--) | Stamp satırının metnini alır veya ayarlar. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stamp satırının metnini alır veya ayarlar. |
|
|  | [getFont()](#getFont--) | Stamp satır metninin yazı tipini al veya ayarla. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Stamp satır metninin yazı tipini al veya ayarla. |
|
|  | [getTextColor()](#getTextColor--) | İmzanın metin rengini alır veya ayarlar. |
|
|  | [setTextColor(Color value)](#setTextColor-java.awt.Color-) | İmzanın metin rengini alır veya ayarlar. |
|
|  | [setTextColor(String value)](#setTextColor-java.lang.String-) | İmzanın metin rengini alır veya ayarlar. |
|
|  | [getTextBottomIntent()](#getTextBottomIntent--) | Metnin alt boşluğunu alır veya ayarlar. |
|
|  | [setTextBottomIntent(int value)](#setTextBottomIntent-int-) | Metnin alt boşluğunu alır veya ayarlar. |
|
|  | [getTextRepeatType()](#getTextRepeatType--) | Metin tekrar tipini alır veya ayarlar. |
|
|  | [setTextRepeatType(int value)](#setTextRepeatType-int-) | Metin tekrar tipini alır veya ayarlar. |
|
|  | [getOuterBorder()](#getOuterBorder--) | Dış kenarı ayarla. |
|
|  | [setOuterBorder(Border value)](#setOuterBorder-com.groupdocs.signature.domain.Border-) | Dış kenarı ayarla. |
|
|  | [getInnerBorder()](#getInnerBorder--) | İç kenarı ayarla. |
|
|  | [setInnerBorder(Border value)](#setInnerBorder-com.groupdocs.signature.domain.Border-) | İç kenarı ayarla. |
|
|  | [getVisible()](#getVisible--) | Stamp satırının görünürlüğünü al ve ayarla. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Stamp satırının görünürlüğünü al ve ayarla. |
|
### StampLine() {#StampLine--}
```
public StampLine()
```


Varsayılan değerlerle StampLine oluştur.


### StampLine(String text) {#StampLine-java.lang.String-}
```
public StampLine(String text)
```


Metinle StampLine oluştur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Stamp satırının metni. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Stamp üzerindeki satır yüksekliğini alır veya ayarlar.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stamp üzerindeki satır yüksekliğini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


İmzanın arka plan rengini alır veya ayarlar.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


İmzanın arka plan rengini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setBackgroundColor(String value) {#setBackgroundColor-java.lang.String-}
```
public final void setBackgroundColor(String value)
```


İmzanın arka plan rengini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


Stamp satırının metnini alır veya ayarlar.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Stamp satırının metnini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Stamp satır metninin yazı tipini al veya ayarla.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Stamp satır metninin yazı tipini al veya ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getTextColor() {#getTextColor--}
```
public final Color getTextColor()
```


İmzanın metin rengini alır veya ayarlar.


**Returns:**
java.awt.Color
### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public final void setTextColor(Color value)
```


İmzanın metin rengini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setTextColor(String value) {#setTextColor-java.lang.String-}
```
public final void setTextColor(String value)
```


İmzanın metin rengini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getTextBottomIntent() {#getTextBottomIntent--}
```
public final int getTextBottomIntent()
```


Metnin alt boşluğunu alır veya ayarlar.


**Returns:**
int
### setTextBottomIntent(int value) {#setTextBottomIntent-int-}
```
public final void setTextBottomIntent(int value)
```


Metnin alt boşluğunu alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTextRepeatType() {#getTextRepeatType--}
```
public final int getTextRepeatType()
```


Metin tekrar tipini alır veya ayarlar.


**Returns:**
int
### setTextRepeatType(int value) {#setTextRepeatType-int-}
```
public final void setTextRepeatType(int value)
```


Metin tekrar tipini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOuterBorder() {#getOuterBorder--}
```
public final Border getOuterBorder()
```


Dış kenarı ayarla.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setOuterBorder(Border value) {#setOuterBorder-com.groupdocs.signature.domain.Border-}
```
public final void setOuterBorder(Border value)
```


Dış kenarı ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getInnerBorder() {#getInnerBorder--}
```
public final Border getInnerBorder()
```


İç kenarı ayarla.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setInnerBorder(Border value) {#setInnerBorder-com.groupdocs.signature.domain.Border-}
```
public final void setInnerBorder(Border value)
```


İç kenarı ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Stamp satırının görünürlüğünü al ve ayarla.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Stamp satırının görünürlüğünü al ve ayarla.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

