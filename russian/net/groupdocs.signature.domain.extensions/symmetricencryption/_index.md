---
title: SymmetricEncryption
second_title: Справочник по API GroupDocs.Signature для .NET
description: Реализует стандартные симметричные алгоритмы шифрования данных с одним ключом и парольной фразой солью.
type: docs
weight: 380
url: /ru/net/groupdocs.signature.domain.extensions/symmetricencryption/
---
## SymmetricEncryption class

Реализует стандартные симметричные алгоритмы шифрования данных с одним ключом и парольной фразой (солью).

```csharp
public sealed class SymmetricEncryption : IDataEncryption
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SymmetricEncryption](symmetricencryption#constructor)(SymmetricAlgorithmType, string) | Создает симметричный алгоритм шифрования с парольной фразой по умолчанию |
| [SymmetricEncryption](symmetricencryption#constructor_1)(SymmetricAlgorithmType, string, string) | Создает алгоритм симметричного шифрования с параметрами. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlgorithmType](../../groupdocs.signature.domain.extensions/symmetricencryption/algorithmtype) { get; set; } | Получает или задает тип симметричного алгоритма. |
| [Key](../../groupdocs.signature.domain.extensions/symmetricencryption/key) { get; set; } | Получает или задает ключ алгоритма шифрования. |
| [Salt](../../groupdocs.signature.domain.extensions/symmetricencryption/salt) { get; set; } | Получает или задает кодовую фразу алгоритма шифрования. |

## Методы

| Имя | Описание |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryption/decode)(string) | Расшифровывает строку на основе предоставленного типа алгоритма, ключа и параметров соли |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryption/encode)(string) | Шифрует строку на основе предоставленного типа алгоритма, ключа и параметров соли |

### Смотрите также

* interface [IDataEncryption](../idataencryption)
* пространство имен [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
