---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения для презентаций."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Параметры сохранения для презентаций.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Инициализирует новый экземпляр класса PresentationSaveOptions со значениями по умолчанию. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Инициализирует новый экземпляр класса PresentationSaveOptions с указанным форматом выходного файла. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Инициализирует новый экземпляр класса PresentationSaveOptions с указанным типом вывода и флагом перезаписи. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Инициализирует новый экземпляр класса PresentationSaveOptions с указанным форматом выходного файла и флагом перезаписи. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Получает или задает формат файла подписанного документа. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Получает или задает формат файла подписанного документа. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Инициализирует новый экземпляр класса PresentationSaveOptions со значениями по умолчанию.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Инициализирует новый экземпляр класса PresentationSaveOptions с указанным форматом выходного файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Тип выходного файла [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Инициализирует новый экземпляр класса PresentationSaveOptions с указанным типом вывода и флагом перезаписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Флаг, указывающий, следует ли перезаписать подписанный файл тем же файлом. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Инициализирует новый экземпляр класса PresentationSaveOptions с указанным форматом выходного файла и флагом перезаписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Тип выходного файла [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
