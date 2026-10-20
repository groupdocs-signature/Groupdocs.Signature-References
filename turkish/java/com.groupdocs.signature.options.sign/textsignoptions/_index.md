---
title: "TextSignOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Metin imza seçeneklerini temsil eder."
type: docs
weight: 18
url: /tr/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Metin imza seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | SignTextOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | SignTextOptions sınıfının yeni bir örneğini metinle başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getLeft()](#getLeft--) | Belge sayfasındaki İmzanın sol X konumu ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType özelliğine bakınız).
|
|  | [setLeft(int value)](#setLeft-int-) | Belge sayfasındaki İmzanın sol X konumu ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType özelliğine bakınız).
|
|  | [getTop()](#getTop--) | Belge sayfasındaki İmzanın üst Y konumu ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType özelliğine bakınız).
|
|  | [setTop(int value)](#setTop-int-) | Belge sayfasındaki İmzanın üst Y konumu ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType özelliğine bakınız).
|
|  | [getWidth()](#getWidth--) | Belge sayfasındaki İmzanın genişliği ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType özelliğine bakınız).
|
|  | [setWidth(int value)](#setWidth-int-) | Belge sayfasındaki İmzanın genişliği ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType özelliğine bakınız).
|
|  | [getHeight()](#getHeight--) | Belge sayfasındaki İmzanın yüksekliği ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType özelliğine bakınız).
|
|  | [setHeight(int value)](#setHeight-int-) | Belge sayfasındaki İmzanın yüksekliği ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType özelliğine bakınız).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Sol ve Üst özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Sol ve Üst özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
|
|  | [getStretch()](#getStretch--) | Belge sayfasındaki germe modu. |
|
|  | [setStretch(int value)](#setStretch-int-) | Belge sayfasındaki germe modu. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Belge sayfasındaki imzanın döndürme açısı (saat yönünde). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Belge sayfasındaki imzanın döndürme açısı (saat yönünde). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Belge sayfasındaki imzanın yatay hizalaması. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Belge sayfasındaki imzanın yatay hizalaması. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Belge sayfasındaki imzanın dikey hizalaması. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Belge sayfasındaki imzanın dikey hizalaması. |
|
|  | [getMargin()](#getMargin--) | İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Margin için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Margin için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar. |
|
|  | [getTransparency()](#getTransparency--) | İmza şeffaflığını (0.0 (opak) ile 1.0 (şeffaf) arasında değer) alır veya ayarlar. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | İmza şeffaflığını (0.0 (opak) ile 1.0 (şeffaf) arasında değer) alır veya ayarlar. |
|
|  | [getText()](#getText--) | İmzanın metnini alır veya ayarlar. |
|
|  | [setText(String value)](#setText-java.lang.String-) | İmzanın metnini alır veya ayarlar. |
|
|  | [getFont()](#getFont--) | İmzanın yazı tipini alır veya ayarlar. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | İmzanın yazı tipini alır veya ayarlar. |
|
|  | [getFontOrDefault()](#getFontOrDefault--) | Dahili: bu örneğin oluşturulduğu sırada sahip olduğu yazı tipi veya varsayılan yazı tipi. |
|
|  | [getForeColor()](#getForeColor--) | İmzanın ön rengini alır veya ayarlar. |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | İmzanın ön rengini alır veya ayarlar. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Metin imza uygulamasının türünü alır veya ayarlar. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Metin imza uygulamasının türünü alır veya ayarlar. |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | İmza içindeki metnin yatay hizalaması. |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | İmza içindeki metnin yatay hizalaması. |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | İmza içindeki metnin dikey hizalaması. |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | İmza içindeki metnin dikey hizalaması. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Metin imzasını koymak için metin form alanının başlığını alır veya ayarlar. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Metin imzasını koymak için metin form alanının başlığını alır veya ayarlar. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Metin imzasını koymak için form alanının türünü alır veya ayarlar. |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Metin imzasını koymak için form alanının türünü alır veya ayarlar. |
|
|  | [getShapeType()](#getShapeType--) | Metni koymak için şeklin türünü alır veya ayarlar. |
|
|  | [setShapeType(int value)](#setShapeType-int-) | Metni koymak için şeklin türünü alır veya ayarlar. |
|
|  | [getSignatureID()](#getSignatureID--) | İmzanın benzersiz kimliğini alır veya ayarlar. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | İmzanın benzersiz kimliğini alır veya ayarlar. |
|
|  | [getBorder()](#getBorder--) | Kenarlık ayarlarını belirtin. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Kenarlık ayarlarını belirtin. |
|
|  | [getBackground()](#getBackground--) | İmza arka plan ayarlarını alır veya ayarlar. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | İmza arka plan ayarlarını alır veya ayarlar. |
|
|  | [getNative()](#getNative--) | Yerel özelliği alır veya ayarlar. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Yerel özelliği alır veya ayarlar. |
|
|  | [getShapePosition()](#getShapePosition--) | Şeklin belge düzeninde nerede sunulacağını tanımlar. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Şeklin belge düzeninde nerede sunulacağını tanımlar. |
|
|  | [validate()](#validate--) | Seçenek parametrelerini doğrulamak için dahili yöntem. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


SignTextOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


SignTextOptions sınıfının yeni bir örneğini metinle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | İmza metni. |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Belge sayfasındaki İmzanın sol X konumu ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType özelliğine bakınız).
(yatay hizalama belirtilmemişse çalışır).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Belge sayfasındaki İmzanın sol X konumu ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType özelliğine bakınız).
(yatay hizalama belirtilmemişse çalışır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Belge sayfasındaki İmzanın üst Y konumu ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType özelliğine bakınız).
(dikey hizalama belirtilmemişse çalışır).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Belge sayfasındaki İmzanın üst Y konumu ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType özelliğine bakınız).
(dikey hizalama belirtilmemişse çalışır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Belge sayfasındaki İmzanın genişliği ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType özelliğine bakınız).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Belge sayfasındaki İmzanın genişliği ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType özelliğine bakınız).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Belge sayfasındaki İmzanın yüksekliği ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType özelliğine bakınız).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Belge sayfasındaki İmzanın yüksekliği ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType özelliğine bakınız).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Sol ve Üst özellikleri için ölçüm türü (piksel, yüzde veya milimetre).


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Sol ve Üst özellikleri için ölçüm türü (piksel, yüzde veya milimetre).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre).


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Belge sayfasındaki germe modu.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Belge sayfasındaki germe modu.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Belge sayfasındaki imzanın döndürme açısı (saat yönünde).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Belge sayfasındaki imzanın döndürme açısı (saat yönünde).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Belge sayfasındaki imzanın yatay hizalaması.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Belge sayfasındaki imzanın yatay hizalaması.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Belge sayfasındaki imzanın dikey hizalaması.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Belge sayfasındaki imzanın dikey hizalaması.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar.
(YALNIZCA yatay veya dikey hizalama belirtilmişse çalışır).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar.
(YALNIZCA yatay veya dikey hizalama belirtilmişse çalışır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Margin için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Margin için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


İmza şeffaflığını (0.0 (opak) ile 1.0 (şeffaf) arasında değer) alır veya ayarlar. Varsayılan değer 0 (opak)dır.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


İmza şeffaflığını (0.0 (opak) ile 1.0 (şeffaf) arasında değer) alır veya ayarlar. Varsayılan değer 0 (opak)dır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getText() {#getText--}
```
public final String getText()
```


İmzanın metnini alır veya ayarlar.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


İmzanın metnini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


İmzanın yazı tipini alır veya ayarlar.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


İmzanın yazı tipini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getFontOrDefault() {#getFontOrDefault--}
```
public final SignatureFont getFontOrDefault()
```


Dahili: bu örneğin oluşturulduğu sırada sahip olduğu yazı tipi veya varsayılan yazı tipi.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


İmzanın ön rengini alır veya ayarlar.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


İmzanın ön rengini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Metin imza uygulamasının türünü alır veya ayarlar.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Metin imza uygulamasının türünü alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


İmza içindeki metnin yatay hizalaması.
Bu özellik yalnızca Image ve Annotation imza uygulamaları için desteklenir
(bkz [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation özelliği).


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


İmza içindeki metnin yatay hizalaması.
Bu özellik yalnızca Image ve Annotation imza uygulamaları için desteklenir
(bkz [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation özelliği).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


İmza içindeki metnin dikey hizalaması.
Bu özellik yalnızca Image imza uygulaması için desteklenir
(bkz [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation özelliği).


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


İmza içindeki metnin dikey hizalaması.
Bu özellik yalnızca Image imza uygulaması için desteklenir
(bkz [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation özelliği).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Metin imzasını koymak için metin form alanının başlığını alır veya ayarlar.
Bu özellik yalnızca SignatureImplementation = TextToFormField ile kullanılabilir.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Metin imzasını koymak için metin form alanının başlığını alır veya ayarlar.
Bu özellik yalnızca SignatureImplementation = TextToFormField ile kullanılabilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Metin imzasını koymak için form alanının türünü alır veya ayarlar.
Bu özellik yalnızca SignatureImplementation = TextToFormField ile kullanılabilir.
Varsayılan değer AllTextTypes'dir.


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Metin imzasını koymak için form alanının türünü alır veya ayarlar.
Bu özellik yalnızca SignatureImplementation = TextToFormField ile kullanılabilir.
Varsayılan değer AllTextTypes'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Metni koymak için şeklin türünü alır veya ayarlar.
Bu özellik yalnızca SignatureImplementation = TextStamp ile kullanılabilir.
Varsayılan değer Rectangle'dir.


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Metni koymak için şeklin türünü alır veya ayarlar.
Bu özellik yalnızca SignatureImplementation = TextStamp ile kullanılabilir.
Varsayılan değer Rectangle'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


İmzanın benzersiz kimliğini alır veya ayarlar. İmza doğrulama seçeneklerinde kullanılabilir. Özellik yalnızca Pdf belgeleri için desteklenir.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


İmzanın benzersiz kimliğini alır veya ayarlar. İmza doğrulama seçeneklerinde kullanılabilir. Özellik yalnızca Pdf belgeleri için desteklenir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Kenarlık ayarlarını belirtin.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Kenarlık ayarlarını belirtin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


İmza arka plan ayarlarını alır veya ayarlar.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


İmza arka plan ayarlarını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Yerel özelliği alır veya ayarlar. Ayarlanırsa belgeye özgü imzalar kullanılabilir.
WordProcessing belgeleri için yerel metin filigranı, normalden farklıdır, örneğin.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Yerel özelliği alır veya ayarlar. Ayarlanırsa belgeye özgü imzalar kullanılabilir.
WordProcessing belgeleri için yerel metin filigranı, normalden farklıdır, örneğin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Şeklin belge düzeninde nerede sunulacağını tanımlar.


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Şeklin belge düzeninde nerede sunulacağını tanımlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### validate() {#validate--}
```
public void validate()
```


Seçenek parametrelerini doğrulamak için dahili yöntem.


### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl.


**Returns:**
java.lang.String -
