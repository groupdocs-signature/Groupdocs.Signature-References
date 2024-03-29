---
title: SymmetricEncryption
second_title: Riferimento API GroupDocs.Signature per .NET
description: Implementa algoritmi simmetrici standard per la crittografia dei dati con chiave singola e passphrase salt.
type: docs
weight: 380
url: /it/net/groupdocs.signature.domain.extensions/symmetricencryption/
---
## SymmetricEncryption class

Implementa algoritmi simmetrici standard per la crittografia dei dati con chiave singola e passphrase (salt).

```csharp
public sealed class SymmetricEncryption : IDataEncryption
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SymmetricEncryption](symmetricencryption#constructor)(SymmetricAlgorithmType, string) | Crea un algoritmo di crittografia simmetrica con passphrase predefinita |
| [SymmetricEncryption](symmetricencryption#constructor_1)(SymmetricAlgorithmType, string, string) | Crea un algoritmo di crittografia simmetrico con parametri. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlgorithmType](../../groupdocs.signature.domain.extensions/symmetricencryption/algorithmtype) { get; set; } | Ottiene o imposta il tipo di algoritmo simmetrico. |
| [Key](../../groupdocs.signature.domain.extensions/symmetricencryption/key) { get; set; } | Ottiene o imposta la chiave dell'algoritmo di crittografia. |
| [Salt](../../groupdocs.signature.domain.extensions/symmetricencryption/salt) { get; set; } | Recupera o imposta la passphrase dell'algoritmo di crittografia. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryption/decode)(string) | Decrittografa la stringa in base al tipo di algoritmo, alla chiave e ai parametri salt forniti |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryption/encode)(string) | Crittografa la stringa in base al tipo di algoritmo, alla chiave e ai parametri salt forniti |

### Guarda anche

* interface [IDataEncryption](../idataencryption)
* spazio dei nomi [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
