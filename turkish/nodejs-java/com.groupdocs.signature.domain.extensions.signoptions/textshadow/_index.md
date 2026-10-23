---
title: "TextShadow"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Metin imzaları için metin gölge özelliklerini temsil eder."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Metin imzaları için metin gölgesi özelliklerini temsil eder. Sonuç, imza türüne ve belge formatına bağlı olarak değişebilir. TextShadow, tüm desteklenen belge türleri için TextAsImage imzası ile kullanılmasını önerir, ayrıca Cells (.xslx) ve Slides (.pptx) için basit TextSignature ve watermark olarak TextSignature ile de kullanılabilir. Words (.docx) için basit TextSignature da önerilir, ancak sınırlı işlevselliğe sahiptir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextShadow()](#TextShadow--) | Varsayılan seçeneklerle TextShadow oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDistance()](#getDistance--) | Metinden gölgeye olan mesafeyi alır veya ayarlar. |
| [setDistance(double value)](#setDistance-double-) | Metinden gölgeye olan mesafeyi alır veya ayarlar. |
| [getAngle()](#getAngle--) | Gölgenin metne göre yerleştirilme açısını alır veya ayarlar. |
| [setAngle(double value)](#setAngle-double-) | Gölgenin metne göre yerleştirilme açısını alır veya ayarlar. |
| [getColor()](#getColor--) | Gölgenin rengini alır veya ayarlar. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Gölgenin rengini alır veya ayarlar. |
| [setColor(String value)](#setColor-java.lang.String-) | Gölgenin rengini alır veya ayarlar. |
| [getTransparency()](#getTransparency--) | Gölgenin şeffaflığını alır veya ayarlar. |
| [setTransparency(double value)](#setTransparency-double-) | Gölgenin şeffaflığını alır veya ayarlar. |
| [getBlur()](#getBlur--) | Gölgenin bulanıklığını alır veya ayarlar. |
| [setBlur(double value)](#setBlur-double-) | Gölgenin bulanıklığını alır veya ayarlar. |
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Varsayılan seçeneklerle TextShadow oluşturur.

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Metinden gölgeye olan mesafeyi alır veya ayarlar. Varsayılan değer 1'dir.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Metinden gölgeye olan mesafeyi alır veya ayarlar. Varsayılan değer 1'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Gölgenin metne göre yerleştirilme açısını alır veya ayarlar. Varsayılan değer 0'dır.

**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Gölgenin metne göre yerleştirilme açısını alır veya ayarlar. Varsayılan değer 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Gölgenin rengini alır veya ayarlar. Varsayılan değer Siyah'tır.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Gölgenin rengini alır veya ayarlar. Varsayılan değer Siyah'tır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Gölgenin rengini alır veya ayarlar. Varsayılan değer Siyah'tır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Gölgenin şeffaflığını alır veya ayarlar. Varsayılan değer 0'dır.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Gölgenin şeffaflığını alır veya ayarlar. Varsayılan değer 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Gölgenin bulanıklığını alır veya ayarlar. Varsayılan değer 4'tür.

**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Gölgenin bulanıklığını alır veya ayarlar. Varsayılan değer 4'tür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

