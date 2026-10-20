---
title: "DocumentInfo"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Определяет свойства описания документа."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Определяет свойства описания документа.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | Инициализирует новый экземпляр класса [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | Количество страниц документа. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Количество страниц документа. |
|
|  | [getPages()](#getPages--) | Коллекция описаний страниц документа. |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Коллекция описаний страниц документа. |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Указывает ширину для максимальной высоты страницы. |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Указывает ширину для максимальной высоты страницы. |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | Указывает максимальную высоту страницы. |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Указывает максимальную высоту страницы. |
|
|  | [getFileType()](#getFileType--) | Тип формата файла. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Тип формата файла. |
|
|  | [getSize()](#getSize--) | Размер документа в байтах. |
|
|  | [setSize(long value)](#setSize-long-) | Размер документа в байтах. |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | Коллекция текстовых подписей документа. |
|
|  | [getImageSignatures()](#getImageSignatures--) | Коллекция подписей‑изображений документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | Коллекция цифровых подписей документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | Коллекция подписей штрих‑кода документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | Коллекция подписей QR‑кода документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | Коллекция подписей полей формы документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getFormFields()](#getFormFields--) | Коллекция всех существующих поддерживаемых полей формы в документе. |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | Коллекция подписей метаданных документа. |
|
|  | [getProcessLogs()](#getProcessLogs--) | Коллекция процессов истории документа, таких как Sign, Update, Delete. |
|
|  | [getSignatures()](#getSignatures--) | Коллекция всех типов подписей документа [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Инициализирует новый экземпляр класса [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo).


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Количество страниц документа.


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Количество страниц документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Коллекция описаний страниц документа.


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Коллекция описаний страниц документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Указывает ширину для максимальной высоты страницы.


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Указывает ширину для максимальной высоты страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Указывает максимальную высоту страницы.


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Указывает максимальную высоту страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Тип формата файла.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Тип формата файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Размер документа в байтах.


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Размер документа в байтах.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageWidth | int |  |
| pageHeight | int |  |
| pageIndex | int |  |

**Returns:**
[PageInfo](../../com.groupdocs.signature.domain/pageinfo)
### getTextSignatures() {#getTextSignatures--}
```
public final List<TextSignature> getTextSignatures()
```


Коллекция текстовых подписей документа.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Коллекция подписей‑изображений документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Коллекция цифровых подписей документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Коллекция подписей штрих‑кода документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Коллекция подписей QR‑кода документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Коллекция подписей полей формы документа, добавленных или обновлённых методами [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Коллекция всех существующих поддерживаемых полей формы в документе. Это свойство поддерживается только для типов документов Pdf и Word Processing.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Коллекция подписей метаданных документа.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Коллекция процессов истории документа, таких как Sign, Update, Delete.


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Коллекция всех типов подписей документа [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
