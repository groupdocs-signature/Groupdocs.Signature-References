---
title: "PdfDigitalSignatureAppearance"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "PDF belgelerinde Dijital İmzanın görünümünü tanımlar."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

PDF belgelerinde Dijital İmzanın görünümünü tanımlar.

--------------------

**Learn more**

 *  See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures][]
 *  See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties][]


[Advanced signing document with Digital electronic signatures]: https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/
[Advanced electronic signatures properties]: https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Varsayılan değerlerle imza görünüm nesnesi oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContactInfoLabel()](#getContactInfoLabel--) | İletişim bilgisi etiketini alır veya ayarlar. |
| [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | İletişim bilgisi etiketini alır veya ayarlar. |
| [getReasonLabel()](#getReasonLabel--) | Sebep etiketini alır veya ayarlar. |
| [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Sebep etiketini alır veya ayarlar. |
| [getLocationLabel()](#getLocationLabel--) | Konum etiketini alır veya ayarlar. |
| [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Konum etiketini alır veya ayarlar. |
| [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Dijital imzalı etiketini alır veya ayarlar. |
| [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Dijital imzalı etiketini alır veya ayarlar. |
| [getDateSignedAtLabel()](#getDateSignedAtLabel--) | İmza tarihi etiketini alır veya ayarlar. |
| [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | İmza tarihi etiketini alır veya ayarlar. |
| [getBackground()](#getBackground--) | İmza görünümünün arka plan rengini alır veya ayarlar. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | İmza görünümünün arka plan rengini alır veya ayarlar. |
| [setBackground(String value)](#setBackground-java.lang.String-) | İmza görünümünün arka plan rengini alır veya ayarlar. |
| [getFontFamilyName()](#getFontFamilyName--) | Etiketleri görüntülemek için Font aile adını alır veya ayarlar. |
| [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Etiketleri görüntülemek için Font aile adını alır veya ayarlar. |
| [getFontSize()](#getFontSize--) | Etiketleri görüntülemek için Font boyutunu alır veya ayarlar. |
| [setFontSize(double value)](#setFontSize-double-) | Etiketleri görüntülemek için Font boyutunu alır veya ayarlar. |
| [getForeground()](#getForeground--) | İmza görünümünün ön plan metin rengini alır veya ayarlar. |
| [setForeground(Color value)](#setForeground-java.awt.Color-) | İmza görünümünün ön plan metin rengini alır veya ayarlar. |
| [setForeground(String value)](#setForeground-java.lang.String-) | İmza görünümünün ön plan metin rengini alır veya ayarlar. |
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Varsayılan değerlerle imza görünüm nesnesi oluşturur.

### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


İletişim bilgisi etiketini alır veya ayarlar. Varsayılan değer: "Contact". Bu değer boş ise dijital imza alanında iletişim etiketi görünmez.

**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


İletişim bilgisi etiketini alır veya ayarlar. Varsayılan değer: "Contact". Bu değer boş ise dijital imza alanında iletişim etiketi görünmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Sebep etiketini alır veya ayarlar. Varsayılan değer: "Reason". Bu değer boş ise dijital imza alanında sebep etiketi görünmez.

**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Sebep etiketini alır veya ayarlar. Varsayılan değer: "Reason". Bu değer boş ise dijital imza alanında sebep etiketi görünmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Konum etiketini alır veya ayarlar. Varsayılan değer: "Location". Bu değer boş ise dijital imza alanında konum etiketi görünmez.

**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Konum etiketini alır veya ayarlar. Varsayılan değer: "Location". Bu değer boş ise dijital imza alanında konum etiketi görünmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Dijital imzalı etiketini alır veya ayarlar. Varsayılan değer: "Digitally signed by".

**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Dijital imzalı etiketini alır veya ayarlar. Varsayılan değer: "Digitally signed by".

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


İmza tarihi etiketini alır veya ayarlar. Varsayılan değer: "Date".

**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


İmza tarihi etiketini alır veya ayarlar. Varsayılan değer: "Date".

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


İmza görünümünün arka plan rengini alır veya ayarlar. Varsayılan olarak değer SystemColors.Windows'dir.

**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


İmza görünümünün arka plan rengini alır veya ayarlar. Varsayılan olarak değer SystemColors.Windows'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


İmza görünümünün arka plan rengini alır veya ayarlar. Varsayılan olarak değer SystemColors.Windows'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Etiketleri görüntülemek için Font aile adını alır veya ayarlar. Varsayılan değer "Arial"dır.

**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Etiketleri görüntülemek için Font aile adını alır veya ayarlar. Varsayılan değer "Arial"dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Etiketleri görüntülemek için Font boyutunu alır veya ayarlar. Varsayılan değer 10'dur.

**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Etiketleri görüntülemek için Font boyutunu alır veya ayarlar. Varsayılan değer 10'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


İmza görünümünün ön plan metin rengini alır veya ayarlar. Varsayılan olarak değer Color.FromArgb(76, 100, 255)'dir.

**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


İmza görünümünün ön plan metin rengini alır veya ayarlar. Varsayılan olarak değer Color.FromArgb(76, 100, 255)'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


İmza görünümünün ön plan metin rengini alır veya ayarlar. Varsayılan olarak değer Color.FromArgb(76, 100, 255)'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

