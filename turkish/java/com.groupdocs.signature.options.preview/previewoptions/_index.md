---
title: "PreviewOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belge önizleme seçeneklerini temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Belge önizleme seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | PreviewOptions nesnesini başlatır. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | PreviewOptions nesnesini başlatır. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | PreviewOptions nesnesini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWidth()](#getWidth--) | Önizleme görüntülerinin genişliğini alır veya ayarlar. |
|
|  | [setWidth(int value)](#setWidth-int-) | Önizleme görüntülerinin genişliğini alır veya ayarlar. |
|
|  | [getHeight()](#getHeight--) | Önizleme görüntülerinin yüksekliğini alır veya ayarlar. |
|
|  | [setHeight(int value)](#setHeight-int-) | Önizleme görüntülerinin yüksekliğini alır veya ayarlar. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Önizleme görüntülerinin sayfa numaralarını alır veya ayarlar. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Önizleme görüntülerinin sayfa numaralarını alır veya ayarlar. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Önizleme görüntü formatını alır veya ayarlar. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Önizleme görüntü formatını alır veya ayarlar. |
|
|  | [getHideSignatures()](#getHideSignatures--) | İmzaların sayfa önizleme görüntüsünden gizlenmesi için bayrağı alır veya ayarlar. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | İmzaların sayfa önizleme görüntüsünden gizlenmesi için bayrağı alır veya ayarlar. |
|
|  | [getResolution()](#getResolution--) | Önizleme görüntülerinin DPI (inç başına nokta) cinsinden çözünürlüğünü alır. |
|
|  | [setResolution(int value)](#setResolution-int-) | Önizleme görüntülerinin DPI (inç başına nokta) cinsinden çözünürlüğünü ayarlar. |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


PreviewOptions nesnesini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Çıktı sayfa önizleme akışı oluşturmak için yöntemi tanımlayan arayüz. |
|
|  | pageNumbers | int[] | İstenen sayfa numaraları |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


PreviewOptions nesnesini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Çıktı sayfa önizleme akışı oluşturmak için yöntemi tanımlayan arayüz. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


PreviewOptions nesnesini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Çıktı dosyasının yolu. |
|
|  | pageNumbers | int[] | İstenen sayfa numaraları |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Önizleme görüntülerinin genişliğini alır veya ayarlar.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Önizleme görüntülerinin genişliğini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Önizleme görüntülerinin yüksekliğini alır veya ayarlar.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Önizleme görüntülerinin yüksekliğini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Önizleme görüntülerinin sayfa numaralarını alır veya ayarlar.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Önizleme görüntülerinin sayfa numaralarını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Önizleme görüntü formatını alır veya ayarlar.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Önizleme görüntü formatını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


İmzaların sayfa önizleme görüntüsünden gizlenmesi için bayrağı alır veya ayarlar.
Yalnızca IsSignature olarak işaretlenen imzalar, oluşturulan belge sayfa görüntüsünden gizlenecektir.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


İmzaların sayfa önizleme görüntüsünden gizlenmesi için bayrağı alır veya ayarlar.
Yalnızca IsSignature olarak işaretlenen imzalar, oluşturulan belge sayfa görüntüsünden gizlenecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Önizleme görüntülerinin DPI (inç başına nokta) cinsinden çözünürlüğünü alır.


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Önizleme görüntülerinin DPI (inç başına nokta) cinsinden çözünürlüğünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

