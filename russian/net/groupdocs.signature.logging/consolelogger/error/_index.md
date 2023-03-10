---
title: Error
second_title: Справочник по API GroupDocs.Signature для .NET
description: Выводит сообщение об ошибке на консоль. Сообщения журнала ошибок предоставляют информацию о неисправимых событиях в потоке приложения.
type: docs
weight: 20
url: /ru/net/groupdocs.signature.logging/consolelogger/error/
---
## ConsoleLogger.Error method

Выводит сообщение об ошибке на консоль. Сообщения журнала ошибок предоставляют информацию о неисправимых событиях в потоке приложения.

```csharp
public void Error(string message, Exception exception)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | String | Сообщение об ошибке. |
| exception | Exception | Исключение. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*message* нулевой. |
| ArgumentNullException | Брошен, когда*exception* нулевой. |

### Смотрите также

* class [ConsoleLogger](../../consolelogger)
* пространство имен [GroupDocs.Signature.Logging](../../consolelogger)
* сборка [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->