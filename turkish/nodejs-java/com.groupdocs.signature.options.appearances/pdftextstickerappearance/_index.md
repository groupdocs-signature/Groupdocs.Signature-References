---
title: "PdfTextStickerAppearance"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "PDF metin açıklama etiket nesnesinin ve etiketin açılır penceresinin görünümünü tanımlar."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

PDF metin açıklama etiket nesnesinin ve etiketin açılır penceresinin görünümünü tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | PDF imza metin açıklama görünüm nesnesi oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTitle()](#getTitle--) | Açılır pencerenin başlığını alır veya ayarlar. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Açılır pencerenin başlığını alır veya ayarlar. |
| [getSubject()](#getSubject--) | Konuyu alır veya ayarlar. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Konuyu alır veya ayarlar. |
| [getContents()](#getContents--) | Açılır pencerenin içeriğini alır veya ayarlar. |
| [setContents(String value)](#setContents-java.lang.String-) | Açılır pencerenin içeriğini alır veya ayarlar. |
| [getOpened()](#getOpened--) | Etiket açılır penceresinin varsayılan olarak açılıp açılmayacağını ayarlayın. |
| [setOpened(boolean value)](#setOpened-boolean-) | Etiket açılır penceresinin varsayılan olarak açılıp açılmayacağını ayarlayın. |
| [getIcon()](#getIcon--) | Etiketin simgesini alır veya ayarlar. |
| [setIcon(int value)](#setIcon-int-) | Etiketin simgesini alır veya ayarlar. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Etiket için varsayılan görünümü alır. |
| [resetDefaultAppearance()](#resetDefaultAppearance--) | Etiket için varsayılan görünüm değerlerini temizler. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


PDF imza metin açıklama görünüm nesnesi oluşturur.

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Açılır pencerenin başlığını alır veya ayarlar.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Açılır pencerenin başlığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Konuyu alır veya ayarlar.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Konuyu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Açılır pencerenin içeriğini alır veya ayarlar.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Açılır pencerenin içeriğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Etiket açılır penceresinin varsayılan olarak açılıp açılmayacağını ayarlayın.

**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Etiket açılır penceresinin varsayılan olarak açılıp açılmayacağını ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Etiketin simgesini alır veya ayarlar.

**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Etiketin simgesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Etiket için varsayılan görünümü alır. Bu özellikler, Options.SignatureAppearance özelliği belirtilmemişse varsayılan olarak uygulanır. Özellikler kullanıcı tarafından her zaman değiştirilebilir.

**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Etiket için varsayılan görünüm değerlerini temizler.

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
