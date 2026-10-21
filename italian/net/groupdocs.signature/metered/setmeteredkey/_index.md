---
title: "SetMeteredKey"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Attiva il prodotto con chiavi Metered."
type: docs
weight: 20
url: /it/net/groupdocs.signature/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Attiva il prodotto con chiavi Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | String | La chiave pubblica. |
| privateKey | String | La chiave privata. |

### Esempi

L'esempio seguente dimostra come attivare il prodotto con chiavi a consumo.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Vedi anche

* class [Metered](../../metered)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
