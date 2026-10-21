---
title: "SymmetricEncryption"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Implementa gli algoritmi simmetrici standard per la crittografia dei dati con chiave singola e salt della passphrase."
type: docs
weight: 540
url: /it/net/groupdocs.signature.domain.extensions/symmetricencryption/
---
## SymmetricEncryption class

Implementa algoritmi simmetrici standard per la crittografia dei dati con chiave singola e passphrase (sale).

```csharp
public sealed class SymmetricEncryption : IDataEncryption
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SymmetricEncryption](symmetricencryption#constructor)(SymmetricAlgorithmType, string) | Crea un algoritmo di crittografia simmetrica con passphrase predefinita |
| [SymmetricEncryption](symmetricencryption#constructor_1)(SymmetricAlgorithmType, string, string) | Crea un algoritmo di crittografia simmetrica con parametri. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlgorithmType](../../groupdocs.signature.domain.extensions/symmetricencryption/algorithmtype) { get; set; } | Ottiene o imposta il tipo di algoritmo simmetrico. |
| [Key](../../groupdocs.signature.domain.extensions/symmetricencryption/key) { get; set; } | Ottiene o imposta la chiave dell'algoritmo di crittografia. |
| [Salt](../../groupdocs.signature.domain.extensions/symmetricencryption/salt) { get; set; } | Ottiene o imposta la passphrase dell'algoritmo di crittografia. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryption/decode)(string) | Decripta la stringa in base al tipo di algoritmo fornito, chiave e parametri di salt. |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryption/encode)(string) | Cripta la stringa in base al tipo di algoritmo fornito, chiave e parametri di sale. |

### Vedi anche

* interface [IDataEncryption](../idataencryption)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
