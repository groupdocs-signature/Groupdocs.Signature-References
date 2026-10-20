---
title: "SaveOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Позволяет указать дополнительные параметры, такие как пароль, при сохранении документа для подписи."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Позволяет указать дополнительные параметры (например, пароль) при сохранении документа для подписи.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Инициализирует новый экземпляр класса SaveOptions со значениями по умолчанию. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Инициализирует новый экземпляр класса SaveOptions с указанным типом вывода и флагом перезаписи. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Получает или задает, следует ли перезаписывать существующий файл новым выходным файлом. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Получает или задает, следует ли перезаписывать существующий файл новым выходным файлом. |
|
|  | [getPassword()](#getPassword--) | Получает или задает пароль для сохранения подписанного документа с защитой паролем. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Получает или задает пароль для сохранения подписанного документа с защитой паролем. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | Получает или задает, использовать ли пароль из LoadOptions для сохранения подписанного документа как защищённого. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Получает или задает, использовать ли пароль из LoadOptions для сохранения подписанного документа как защищённого. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Получает или задает флаг для автоматического добавления расширения, если оно отсутствовало в пути выходного файла |
Значение по умолчанию — false.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Получает или задает флаг для автоматического добавления расширения, если оно отсутствовало в пути выходного файла |
Значение по умолчанию — false.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Инициализирует новый экземпляр класса SaveOptions со значениями по умолчанию.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Инициализирует новый экземпляр класса SaveOptions с указанным типом вывода и флагом перезаписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Флаг, указывающий, следует ли перезаписать подписанный файл тем же файлом. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Получает или задает, следует ли перезаписывать существующий файл новым выходным файлом.
В противном случае будет создан новый файл с номером в качестве суффикса.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Получает или задает, следует ли перезаписывать существующий файл новым выходным файлом.
В противном случае будет создан новый файл с номером в качестве суффикса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Получает или задает пароль для сохранения подписанного документа с защитой паролем.
Это свойство не поддерживается для документов Image.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Получает или задает пароль для сохранения подписанного документа с защитой паролем.
Это свойство не поддерживается для документов Image.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Получает или задает, использовать ли пароль из LoadOptions для сохранения подписанного документа как защищённого.
Значение по умолчанию — true.
Это свойство не поддерживается для документов Image.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Получает или задает, использовать ли пароль из LoadOptions для сохранения подписанного документа как защищённого.
Значение по умолчанию — true.
Это свойство не поддерживается для документов Image.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Получает или задает флаг для автоматического добавления расширения, если оно отсутствовало в пути выходного файла
Значение по умолчанию — false.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Получает или задает флаг для автоматического добавления расширения, если оно отсутствовало в пути выходного файла
Значение по умолчанию — false.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

