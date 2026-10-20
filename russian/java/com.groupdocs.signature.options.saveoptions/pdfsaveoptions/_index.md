---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения для PDF‑документов."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Параметры сохранения для PDF‑документов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Инициализирует новый экземпляр класса PdfSaveOptions со значениями по умолчанию. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Инициализирует новый экземпляр класса PdfSaveOptions с указанным форматом выходного файла. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Инициализирует новый экземпляр класса PdfSaveOptions с флагом перезаписи. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Инициализирует новый экземпляр класса PdfSaveOptions с указанным форматом выходного файла и флагом перезаписи. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Получает или задает формат файла подписанного документа. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Получает или задает формат файла подписанного документа. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Пароль разрешений (основной пароль) требует ввода пароля для изменения настроек разрешений. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Пароль разрешений (основной пароль) требует ввода пароля для изменения настроек разрешений. |
|
|  | [getPermissions()](#getPermissions--) | Разрешения PDF‑документа, такие как печать, изменение и извлечение данных. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Разрешения PDF‑документа, такие как печать, изменение и извлечение данных. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Инициализирует новый экземпляр класса PdfSaveOptions со значениями по умолчанию.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Инициализирует новый экземпляр класса PdfSaveOptions с указанным форматом выходного файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Тип выходного файла [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Инициализирует новый экземпляр класса PdfSaveOptions с флагом перезаписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Флаг, указывающий, следует ли перезаписать подписанный файл тем же файлом. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Инициализирует новый экземпляр класса PdfSaveOptions с указанным форматом выходного файла и флагом перезаписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Тип выходного файла [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|
|  | overwriteExistingFile | boolean | Флаг, указывающий, следует ли перезаписать подписанный файл тем же файлом. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Получает или задает формат файла подписанного документа.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Получает или задает формат файла подписанного документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Пароль разрешений (основной пароль) требует ввода пароля для изменения настроек разрешений.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Пароль разрешений (основной пароль) требует ввода пароля для изменения настроек разрешений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Разрешения PDF‑документа, такие как печать, изменение и извлечение данных.


Чтобы изменить эти разрешения,
PermissionsPassword
должен быть установлен.
Значение представляет собой комбинацию флагов из [Permissions](../../com.groupdocs.signature.options/permissions).
Один
null
значение означает, что явные разрешения не применяются.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Разрешения PDF‑документа, такие как печать, изменение и извлечение данных.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
