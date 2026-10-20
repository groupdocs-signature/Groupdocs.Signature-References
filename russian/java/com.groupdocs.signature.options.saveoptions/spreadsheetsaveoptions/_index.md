---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения для электронных таблиц."
type: docs
weight: 14
url: /ru/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Параметры сохранения для электронных таблиц.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Инициализирует новый экземпляр класса SpreadsheetSaveOptions с значениями по умолчанию. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Инициализирует новый экземпляр класса SpreadsheetSaveOptions с предопределённым форматом выходного файла. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Инициализирует новый экземпляр класса SpreadsheetSaveOptions с указанным типом вывода и флагом перезаписи. |
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
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Инициализирует новый экземпляр класса SpreadsheetSaveOptions с значениями по умолчанию.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Инициализирует новый экземпляр класса SpreadsheetSaveOptions с предопределённым форматом выходного файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Указывает формат выходного файла. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Инициализирует новый экземпляр класса SpreadsheetSaveOptions с указанным типом вывода и флагом перезаписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Указывает формат выходного файла. |
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
