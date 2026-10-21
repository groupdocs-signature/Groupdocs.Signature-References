---
title: "SymmetricEncryptionAttribute"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Indica alla serializzazione delle istanze di crittografare / decrittografare la stringa di serializzazione dell'oggetto."
type: docs
weight: 550
url: /it/net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/
---
## SymmetricEncryptionAttribute class

Indica alla serializzazione delle istanze di crittografare / decrittografare la stringa di serializzazione dell'oggetto.

```csharp
[AttributeUsage(AttributeTargets.Class | AttributeTargets.Struct)]
public sealed class SymmetricEncryptionAttribute : Attribute, IDataEncryption
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SymmetricEncryptionAttribute](symmetricencryptionattribute#constructor)(SymmetricAlgorithmType, string) | Crea un algoritmo simmetrico con parametri e passphrase predefinita. |
| [SymmetricEncryptionAttribute](symmetricencryptionattribute#constructor_1)(SymmetricAlgorithmType, string, string) | Crea un algoritmo simmetrico con parametri. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryptionattribute/decode)(string) | Decripta la stringa fornita in base al tipo di algoritmo, chiave e parametri di sale. |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryptionattribute/encode)(string) | Cripta la stringa in base al tipo di algoritmo fornito, chiave e parametri di sale. |

### Vedi anche

* interface [IDataEncryption](../idataencryption)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
