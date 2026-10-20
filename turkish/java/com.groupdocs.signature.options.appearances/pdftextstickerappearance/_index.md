---
title: "PdfTextStickerAppearance"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "PDF metin ek açıklama çıkartma nesnesinin ve çıkartmanın açılır penceresinin görünümünü açıklar."
type: docs
weight: 14
url: /tr/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

PDF metin ek açıklama çıkartma nesnesinin ve çıkartmanın açılır penceresinin görünümünü açıklar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | PDF imza metin ek açıklama görünümü nesnesi oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getTitle()](#getTitle--) | Açılır pencerenin başlığını alır veya ayarlar. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Açılır pencerenin başlığını alır veya ayarlar. |
|
|  | [getSubject()](#getSubject--) | Konu alır veya ayarlar. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Konu alır veya ayarlar. |
|
|  | [getContents()](#getContents--) | Açılır pencerenin içeriğini alır veya ayarlar. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Açılır pencerenin içeriğini alır veya ayarlar. |
|
|  | [getOpened()](#getOpened--) | Sticker açılır penceresinin varsayılan olarak açılıp açılmayacağını ayarlayın. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | Sticker açılır penceresinin varsayılan olarak açılıp açılmayacağını ayarlayın. |
|
|  | [getIcon()](#getIcon--) | Sticker simgesini alır veya ayarlar. |
|
|  | [setIcon(int value)](#setIcon-int-) | Sticker simgesini alır veya ayarlar. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | Sticker için varsayılan görünümü alır. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | Sticker için varsayılan görünüm değerlerini temizler. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


PDF imza metin ek açıklama görünümü nesnesi oluşturur.


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


Konu alır veya ayarlar.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Konu alır veya ayarlar.


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


Sticker açılır penceresinin varsayılan olarak açılıp açılmayacağını ayarlayın.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Sticker açılır penceresinin varsayılan olarak açılıp açılmayacağını ayarlayın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Sticker simgesini alır veya ayarlar.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Sticker simgesini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Sticker için varsayılan görünümü alır. Bu özellikler, eğer
Options.SignatureAppearance özelliği belirtilmemiştir.
Özellikler, kullanıcı tarafından her zaman değiştirilebilir.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Sticker için varsayılan görünüm değerlerini temizler.


### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl.


**Returns:**
java.lang.String -
