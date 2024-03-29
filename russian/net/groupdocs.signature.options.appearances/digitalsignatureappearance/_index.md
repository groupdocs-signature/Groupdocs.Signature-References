---
title: DigitalSignatureAppearance
second_title: Справочник по API GroupDocs.Signature для .NET
description: Описывает внешний вид строки подписи для цифровой подписи. Одна строка подписи может применяться только для одной цифровой подписи. Строка подписи всегда находится на первой странице. Эта функция может быть полезна для форматов файлов .docx .doc .odt и .xlsx.
type: docs
weight: 1190
url: /ru/net/groupdocs.signature.options.appearances/digitalsignatureappearance/
---
## DigitalSignatureAppearance class

Описывает внешний вид строки подписи для цифровой подписи. Одна строка подписи может применяться только для одной цифровой подписи. Строка подписи всегда находится на первой странице. Эта функция может быть полезна для форматов файлов .docx, .doc, .odt и .xlsx.

```csharp
public sealed class DigitalSignatureAppearance : SignatureAppearance
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DigitalSignatureAppearance](digitalsignatureappearance#constructor)() | Создает объект «Внешний вид строки подписи». |
| [DigitalSignatureAppearance](digitalsignatureappearance#constructor_1)(string, string, string) | Создает внешний вид строки подписи с указанными значениями (подписавшаяся, должность, адрес электронной почты). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Email](../../groupdocs.signature.options.appearances/digitalsignatureappearance/email) { get; set; } | Получает или задает адрес электронной почты, который будет отображаться в строке подписи. |
| [Signer](../../groupdocs.signature.options.appearances/digitalsignatureappearance/signer) { get; set; } | Получает или задает имя подписавшего для строки подписи. |
| [Title](../../groupdocs.signature.options.appearances/digitalsignatureappearance/title) { get; set; } | Получает или задает заголовок для строки подписи. |

### Смотрите также

* class [SignatureAppearance](../signatureappearance)
* пространство имен [GroupDocs.Signature.Options.Appearances](../../groupdocs.signature.options.appearances)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
