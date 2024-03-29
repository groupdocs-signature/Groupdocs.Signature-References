---
title: VerifyOptions
second_title: Справочник по API GroupDocs.Signature для .NET
description: Сохраняет параметры для проверки документа.
type: docs
weight: 1780
url: /ru/net/groupdocs.signature.options/verifyoptions/
---
## VerifyOptions class

Сохраняет параметры для проверки документа.

```csharp
public abstract class VerifyOptions
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Флаг для проверки каждой страницы документа. По умолчанию значение равно true. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Дополнительные расширения для проверки альтернативных вариантов подписи. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Флаг действительного свойства. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Номер страницы документа для проверки. Если свойство не установлено, все страницы документа будут проверяться на первое вхождение. Минимальное значение 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Параметры страницы для указания проверяемых страниц. |

### Смотрите также

* пространство имен [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
