---
title: "PdfTextAnnotationAppearance"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "PDF metin açıklama nesnesi Title Subject Content görünümünü tanımlar."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

PDF metin açıklama nesnesinin (Başlık, Konu, İçerik) görünümünü tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | PDF imza txt açıklama görünüm nesnesi oluşturur. |
| [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Belirtilen değerlerle (title, subject, contents) PDF imza txt açıklaması oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContents()](#getContents--) | Açıklama nesnesinin içeriğini alır veya ayarlar. |
| [setContents(String value)](#setContents-java.lang.String-) | Açıklama nesnesinin içeriğini alır veya ayarlar. |
| [getSubject()](#getSubject--) | Nesnenin açıklamasını temsil eden Subject'i alır veya ayarlar. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Nesnenin açıklamasını temsil eden Subject'i alır veya ayarlar. |
| [getTitle()](#getTitle--) | Bir Başlık alır veya ayarlar; bu Başlık ek açıklama nesnesinin başlık çubuğunda görüntülenecektir. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Bir Başlık alır veya ayarlar; bu Başlık ek açıklama nesnesinin başlık çubuğunda görüntülenecektir. |
| [getBorder()](#getBorder--) | Farklı kenar ayarlarını alır veya ayarlar. |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Farklı kenar ayarlarını alır veya ayarlar. |
| [getBorderEffect()](#getBorderEffect--) | Kenar etkisini alır veya ayarlar. |
| [setBorderEffect(int value)](#setBorderEffect-int-) | Kenar etkisini alır veya ayarlar. |
| [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Kenar etkisi yoğunluğunu alır veya ayarlar. |
| [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Kenar etkisi yoğunluğunu alır veya ayarlar. |
| [getHCornerRadius()](#getHCornerRadius--) | Yatay köşe yarıçapını alır veya ayarlar. |
| [setHCornerRadius(int value)](#setHCornerRadius-int-) | Yatay köşe yarıçapını alır veya ayarlar. |
| [getVCornerRadius()](#getVCornerRadius--) | Dikey köşe yarıçapını alır veya ayarlar. |
| [setVCornerRadius(int value)](#setVCornerRadius-int-) | Dikey köşe yarıçapını alır veya ayarlar. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


PDF imza txt açıklama görünüm nesnesi oluşturur.

### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Belirtilen değerlerle (title, subject, contents) PDF imza txt açıklaması oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlık | java.lang.String | Başlık. |
| konu | java.lang.String | Konu. |
| içerikler | java.lang.String | İçerikler. |

### getContents() {#getContents--}
```
public final String getContents()
```


Açıklama nesnesinin içeriğini alır veya ayarlar.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Açıklama nesnesinin içeriğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Nesnenin açıklamasını temsil eden Subject'i alır veya ayarlar.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Nesnenin açıklamasını temsil eden Subject'i alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Bir Başlık alır veya ayarlar; bu Başlık ek açıklama nesnesinin başlık çubuğunda görüntülenecektir.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Bir Başlık alır veya ayarlar; bu Başlık ek açıklama nesnesinin başlık çubuğunda görüntülenecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Farklı kenar ayarlarını alır veya ayarlar.

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Farklı kenar ayarlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Kenar etkisini alır veya ayarlar.

**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Kenar etkisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Kenar etkisi yoğunluğunu alır veya ayarlar. Değerin geçerli aralığı [0..2] dir.

**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Kenar etkisi yoğunluğunu alır veya ayarlar. Değerin geçerli aralığı [0..2] dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Yatay köşe yarıçapını alır veya ayarlar.

**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Yatay köşe yarıçapını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Dikey köşe yarıçapını alır veya ayarlar.

**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Dikey köşe yarıçapını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
