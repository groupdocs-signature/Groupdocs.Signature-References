---
title: "SignatureSettings"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Определяет настройки для настройки поведения."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Определяет настройки для настройки поведения [Signature](../../com.groupdocs.signature/signature).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | Создаёт экземпляр SignatureSettings со значениями по умолчанию. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Создаёт экземпляр SignatureSettings со реализацией Logger. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | Получает или задаёт культуру по умолчанию, используемую при обработке документов. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Получает или задаёт культуру по умолчанию, используемую при обработке документов. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Получает или задаёт флаг, включающий удалённые подписи в результат Document Info. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Получает или задаёт флаг, включающий удалённые подписи в результат Document Info. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Получает или задаёт флаг для повторного сохранения исходного документа, когда метод Update не имеет подписей для обновления. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Получает или задаёт флаг для повторного сохранения исходного документа, когда метод Update не имеет подписей для обновления. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Получает или задаёт флаг для повторного сохранения исходного документа, когда метод Delete не имеет затронутых подписей для удаления. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Получает или задаёт флаг для повторного сохранения исходного документа, когда метод Delete не имеет затронутых подписей для удаления. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Получает или задаёт флаг для включения в список метаданных встроенных стандартных подписей метаданных документа, таких как Author, Owner, дата создания документа, дата изменения и т.д. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Получает или задаёт флаг для включения в список метаданных встроенных стандартных подписей метаданных документа, таких как Author, Owner, дата создания документа, дата изменения и т.д. |
|
|  | [getLogger()](#getLogger--) | Реализация логгера, используемая для записи (Errors, Warnings, Traces). |
|
|  | [getLogLevel()](#getLogLevel--) | Получает или задаёт типы сообщений, передаваемых в логгер. |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | Получает или задаёт типы сообщений, передаваемых в логгер. |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Создаёт экземпляр SignatureSettings со значениями по умолчанию.


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Создаёт экземпляр SignatureSettings со реализацией Logger.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Получает или задаёт культуру по умолчанию, используемую при обработке документов. Значение по умолчанию — "en-US".


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Получает или задаёт культуру по умолчанию, используемую при обработке документов. Значение по умолчанию — "en-US".


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Получает или задаёт флаг, включающий удалённые подписи в результат Document Info.
Каждая подпись [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) имеет флаг Deleted.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) чтобы определить, был ли он удалён.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Получает или задаёт флаг, включающий удалённые подписи в результат Document Info.
Каждая подпись [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) имеет флаг Deleted.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) чтобы определить, был ли он удалён.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Получает или задаёт флаг для повторного сохранения исходного документа, когда метод Update не имеет подписей для обновления.
Если этот флаг установлен в true (по умолчанию), документ будет сохраняться с соответствующим журналом истории процесса (дата и тип операции), даже если метод Update не имеет подписей для обновления.
Когда этот флаг установлен в false, исходный документ не будет изменён вообще.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Получает или задаёт флаг для повторного сохранения исходного документа, когда метод Update не имеет подписей для обновления.
Если этот флаг установлен в true (по умолчанию), документ будет сохраняться с соответствующим журналом истории процесса (дата и тип операции), даже если метод Update не имеет подписей для обновления.
Когда этот флаг установлен в false, исходный документ не будет изменён вообще.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Получает или задаёт флаг для повторного сохранения исходного документа, когда метод Delete не имеет затронутых подписей для удаления.
Если этот флаг установлен в true (по умолчанию), документ будет сохраняться с соответствующим журналом истории процесса (дата и тип операции), даже если метод Delete не имеет подписей для удаления.
Когда этот флаг установлен в false, исходный документ не будет изменён вообще.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Получает или задаёт флаг для повторного сохранения исходного документа, когда метод Delete не имеет затронутых подписей для удаления.
Если этот флаг установлен в true (по умолчанию), документ будет сохраняться с соответствующим журналом истории процесса (дата и тип операции), даже если метод Delete не имеет подписей для удаления.
Когда этот флаг установлен в false, исходный документ не будет изменён вообще.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Получает или задаёт флаг для включения в список метаданных встроенных стандартных подписей метаданных документа, таких как Author, Owner, дата создания документа, дата изменения и т.д.
Если этот флаг установлен в false (по умолчанию), GetDocumentInfo не будет включать эти подписи метаданных.
Когда этот флаг установлен в true, информация о документе будет включать эти стандартные подписи метаданных.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Получает или задаёт флаг для включения в список метаданных встроенных стандартных подписей метаданных документа, таких как Author, Owner, дата создания документа, дата изменения и т.д.
Если этот флаг установлен в false (по умолчанию), GetDocumentInfo не будет включать эти подписи метаданных.
Когда этот флаг установлен в true, информация о документе будет включать эти стандартные подписи метаданных.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Реализация логгера, используемая для записи (Ошибки, Предупреждения, Трассировки). [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Получает или задаёт типы сообщений, передаваемых в логгер.
Значение представляет собой набор флагов [LogLevel](../../com.groupdocs.signature.logging/loglevel), которые можно комбинировать, например

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
не записывает ничего.
По умолчанию
LogLevel.All
: ошибки, предупреждения и трассировки.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Получает или задаёт типы сообщений, передаваемых в логгер.
Значение представляет собой набор флагов [LogLevel](../../com.groupdocs.signature.logging/loglevel), которые можно комбинировать, например

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
не записывает ничего.
По умолчанию
LogLevel.All
: ошибки, предупреждения и трассировки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

