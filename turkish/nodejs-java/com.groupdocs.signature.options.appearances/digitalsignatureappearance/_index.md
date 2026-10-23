---
title: "DigitalSignatureAppearance"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Dijital İmza için İmza Çizgisinin görünümünü tanımlar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Dijital İmza için İmza Satırının görünümünü açıklar. Bir İmza Satırı yalnızca bir Dijital İmza için uygulanabilir. İmza Satırı her zaman ilk sayfada bulunur. Bu özellik .docx, .doc, .odt ve .xlsx dosya formatları için faydalı olabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | İmza Satırı Görünümü nesnesi oluşturur. |
| [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Belirtilen değerlerle (imzalayan, başlık, e-posta) İmza Satırı Görünümü oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSigner()](#getSigner--) | İmza satırı için imzalayan adını alır veya ayarlar. |
| [setSigner(String value)](#setSigner-java.lang.String-) | İmza satırı için imzalayan adını alır veya ayarlar. |
| [getTitle()](#getTitle--) | İmza satırı için bir başlık alır veya ayarlar. |
| [setTitle(String value)](#setTitle-java.lang.String-) | İmza satırı için bir başlık alır veya ayarlar. |
| [getEmail()](#getEmail--) | İmza satırında görüntülenecek bir e-posta alır veya ayarlar. |
| [setEmail(String value)](#setEmail-java.lang.String-) | İmza satırında görüntülenecek bir e-posta alır veya ayarlar. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


İmza Satırı Görünümü nesnesi oluşturur.

### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Belirtilen değerlerle (imzalayan, başlık, e-posta) İmza Satırı Görünümü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imzalayan | java.lang.String | İmzalayan adı. |
| başlık | java.lang.String | İmza başlığı. |
| e-posta | java.lang.String | Yazarın e-posta adresi. |

### getSigner() {#getSigner--}
```
public final String getSigner()
```


İmza satırı için imzalayan adını alır veya ayarlar.

**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


İmza satırı için imzalayan adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


İmza satırı için bir başlık alır veya ayarlar.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


İmza satırı için bir başlık alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


İmza satırında görüntülenecek bir e-posta alır veya ayarlar.

**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


İmza satırında görüntülenecek bir e-posta alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
