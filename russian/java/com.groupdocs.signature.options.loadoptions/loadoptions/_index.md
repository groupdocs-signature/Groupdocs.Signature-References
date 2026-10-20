---
title: "LoadOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Позволяет указать дополнительные параметры, такие как пароль, при открытии документа для подписи."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Позволяет указывать дополнительные параметры (например, пароль) при открытии документа для подписи.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Инициализирует новый экземпляр класса LoadOptions. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-) | Инициализирует новый экземпляр класса LoadOptions с указанным типом файла. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Получает или задает пароль для открытия защищённого документа. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Получает или задает пароль для открытия защищённого документа. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | Получает или задает флаг, указывающий, следует ли пропускать ресурсы, хранящиеся вне документа, при его загрузке. |
|
|  | [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | Получает или задает флаг, указывающий, следует ли пропускать ресурсы, хранящиеся вне документа, при его загрузке. |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | Получает или задает части адресов внешних ресурсов, которые могут быть загружены во время |
#getSkipExternalResources().getSkipExternalResources() истинно.
|
|  | [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | Получает или задает части адресов внешних ресурсов, которые могут быть загружены во время |
#getSkipExternalResources().getSkipExternalResources() истинно.
|
|  | [getPermissions()](#getPermissions--) | Разрешения PDF‑документа, такие как печать, изменение и извлечение данных. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Внутренний сеттер, используемый процессорами загрузки документа для записи разрешений, извлечённых из файла. |
|
|  | [getFileType()](#getFileType--) | Получает тип файла документа. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Устанавливает тип файла документа, чтобы он не определялся из содержимого документа. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Инициализирует новый экземпляр класса LoadOptions.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public LoadOptions(FileType fileType)
```


Инициализирует новый экземпляр класса LoadOptions с указанным типом файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) | Тип файла документа, см. #setFileType(FileType).setFileType(FileType). |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Получает или задает пароль для открытия защищённого документа.
Он также будет использоваться для сохранения подписанного документа как защищённого.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Получает или задает пароль для открытия защищённого документа.
Он также будет использоваться для сохранения подписанного документа как защищённого.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public final boolean getSkipExternalResources()
```


Получает или задает флаг, указывающий, следует ли пропускать ресурсы, хранящиеся вне документа, при его загрузке.
Значение по умолчанию — true.


Документ может ссылаться на внешние ресурсы: связанные изображения и поля INCLUDEPICTURE в текстовом процессоре
документы, связанные изображения в презентациях и электронных таблицах, изображения и таблицы стилей, на которые ссылается SVG‑изображение.
Загрузка такого ресурса означает запрос адреса, записанного в документе. На сервере, который обрабатывает
документы от других людей, что представляет риск подделки запросов на стороне сервера, а в автономной установке
запрос завершится неудачей или будет ожидать тайм‑аут.


Если значение true, внешние ресурсы не загружаются, за исключением тех, чей адрес содержит один из
#getWhitelistedResources().getWhitelistedResources(). Пропущенные ресурсы не отображаются в предварительном просмотре страниц или в документах, сохранённых как
изображения, и поиск изображений, штрихкодов и QR‑кодов их не видит. Встроенные изображения не затрагиваются, и
гиперссылки никогда не следуются. Эта настройка также применяется к документам внутри архивов.


**Returns:**
boolean
### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public final void setSkipExternalResources(boolean value)
```


Получает или задает флаг, указывающий, следует ли пропускать ресурсы, хранящиеся вне документа, при его загрузке.
Значение по умолчанию — true. См. #getSkipExternalResources().getSkipExternalResources().


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public final List<String> getWhitelistedResources()
```


Получает или задает части адресов внешних ресурсов, которые могут быть загружены во время
#getSkipExternalResources().getSkipExternalResources() равно true. Адрес загружается, когда он содержит один из них, без учёта регистра.
Пустые значения игнорируются. По умолчанию — пустой список; установка null очищает его.


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public final void setWhitelistedResources(List<String> value)
```


Получает или задает части адресов внешних ресурсов, которые могут быть загружены во время
#getSkipExternalResources().getSkipExternalResources() равно true. См. #getWhitelistedResources().getWhitelistedResources().


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<java.lang.String> |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Разрешения PDF‑документа, такие как печать, изменение и извлечение данных.
Только для PDF‑документов. Только для чтения \\u2014 заполняется автоматически при загрузке документа.
Значение представляет собой комбинацию флагов из [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Внутренний сеттер, используемый процессорами загрузки документа для записи разрешений, извлечённых из файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Получает тип файла документа. Когда он равен [FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (по умолчанию),
тип файла определяется по содержимому документа.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Устанавливает тип файла документа, чтобы он не определялся из содержимого документа.
[FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default) or null detects it.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

