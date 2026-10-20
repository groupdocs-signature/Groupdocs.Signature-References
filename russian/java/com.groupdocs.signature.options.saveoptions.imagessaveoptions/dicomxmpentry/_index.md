---
title: "DicomXmpEntry"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Запись данных XMP для DICOM‑изображений .dcm."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomxmpentry/
---
**Inheritance:**
java.lang.Object
```
public final class DicomXmpEntry
```

Ввод XMP‑данных для DICOM‑изображений (.dcm).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DicomXmpEntry(int type, String value)](#DicomXmpEntry-int-java.lang.String-) | Создаёт запись XMP для DICOM‑изображения. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getType()](#getType--) | Тип записи. |
|
|  | [getValue()](#getValue--) | Значение записи. |
|
|  | [toString()](#toString--) | Получить текстовое представление записи XMP. |
|
### DicomXmpEntry(int type, String value) {#DicomXmpEntry-int-java.lang.String-}
```
public DicomXmpEntry(int type, String value)
```


Создаёт запись XMP для DICOM‑изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | тип | int | Тип записи |
|
|  | значение | java.lang.String | Значение записи |
|

### getType() {#getType--}
```
public final int getType()
```


Тип записи.


**Returns:**
int
### getValue() {#getValue--}
```
public final String getValue()
```


Значение записи.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Получить текстовое представление записи XMP.


**Returns:**
java.lang.String - Текстовое представление записи Xmp.

