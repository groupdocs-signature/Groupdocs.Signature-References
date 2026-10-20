---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Параметры сохранения для документов обработки текста."
type: docs
weight: 15
url: /ru/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Параметры сохранения для документов обработки текста.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Инициализирует новый экземпляр класса WordProcessingSaveOptions с значениями по умолчанию. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Инициализирует новый экземпляр класса WordProcessingSaveOptions с указанным форматом выходного файла. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Инициализирует новый экземпляр класса WordProcessingSaveOptions с указанным типом вывода и флагом перезаписи. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Инициализирует новый экземпляр класса WordProcessingSaveOptions с указанным форматом выходного файла и флагом перезаписи. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Получает или задает формат файла подписанного документа. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Получает или задает формат файла подписанного документа. |
|
|  | [getOoxmlCompliance()](#getOoxmlCompliance--) | Необязательный уровень соответствия OOXML для подписанного документа. |
|
|  | [setOoxmlCompliance(Integer value)](#setOoxmlCompliance-java.lang.Integer-) | Необязательный уровень соответствия OOXML для подписанного документа. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Инициализирует новый экземпляр класса WordProcessingSaveOptions с значениями по умолчанию.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Инициализирует новый экземпляр класса WordProcessingSaveOptions с указанным форматом выходного файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Тип выходного файла [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Инициализирует новый экземпляр класса WordProcessingSaveOptions с указанным типом вывода и флагом перезаписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Флаг, указывающий, следует ли перезаписать подписанный файл тем же файлом. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Инициализирует новый экземпляр класса WordProcessingSaveOptions с указанным форматом выходного файла и флагом перезаписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileFormat | int | Тип выходного файла [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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

### getOoxmlCompliance() {#getOoxmlCompliance--}
```
public final Integer getOoxmlCompliance()
```


Необязательный уровень соответствия OOXML для подписанного документа. При установке переопределяет
соответствие оригинального документа. Когда
null
(по умолчанию), соответствие загруженного документа
сохраняется. Учитывается только для форматов OOXML
(Docx, Docm, Dotx, Dotm, FlatOpc и варианты FlatOpc).


Значение является одним из [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance).


**Returns:**
java.lang.Integer
### setOoxmlCompliance(Integer value) {#setOoxmlCompliance-java.lang.Integer-}
```
public final void setOoxmlCompliance(Integer value)
```


Необязательный уровень соответствия OOXML для подписанного документа. При установке переопределяет
соответствие оригинального документа. Когда
null
(по умолчанию), соответствие загруженного документа
сохраняется. Учитывается только для форматов OOXML
(Docx, Docm, Dotx, Dotm, FlatOpc и варианты FlatOpc).


Значение является одним из [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки


**Returns:**
java.lang.String -
