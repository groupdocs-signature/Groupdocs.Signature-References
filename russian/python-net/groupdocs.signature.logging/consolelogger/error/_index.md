---
title: "метод error"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Записывает сообщение об ошибке в консоль."
type: docs
url: /ru/python-net/groupdocs.signature.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Записывает сообщение об ошибке в консоль.

Сообщения журнала Error предоставляют информацию о необратимых событиях в ходе выполнения приложения.

```python
def error(self, message, ex):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| message | `str` | Сообщение error. |
| ex | `Exception` | Исключение. |

| Вызывает | Описание |
| :- | :- |
| `ValueError` | Когда `ex` равно None. |

### См. также
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
