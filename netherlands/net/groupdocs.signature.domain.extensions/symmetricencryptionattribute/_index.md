---
title: SymmetricEncryptionAttribute
second_title: GroupDocs.Signature voor .NET API-referentie
description: Instrueert instanceserialisatie om objectserialisatietekenreeks te versleutelen/ontsleutelen.
type: docs
weight: 390
url: /nl/net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/
---
## SymmetricEncryptionAttribute class

Instrueert instanceserialisatie om objectserialisatietekenreeks te versleutelen/ontsleutelen.

```csharp
[AttributeUsage(AttributeTargets.Class | AttributeTargets.Struct)]
public sealed class SymmetricEncryptionAttribute : Attribute, IDataEncryption
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SymmetricEncryptionAttribute](symmetricencryptionattribute#constructor)(SymmetricAlgorithmType, string) | Creëert symmetrisch algoritme met parameters en standaard wachtwoordzin. |
| [SymmetricEncryptionAttribute](symmetricencryptionattribute#constructor_1)(SymmetricAlgorithmType, string, string) | Creëert symmetrisch algoritme met parameters. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryptionattribute/decode)(string) | Decodeert doorgegeven tekenreeks op basis van algoritmetype, sleutel en salt-parameters |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryptionattribute/encode)(string) | Versleutelt tekenreeks op basis van opgegeven algoritmetype, sleutel en salt-parameters |

### Zie ook

* interface [IDataEncryption](../idataencryption)
* naamruimte [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->