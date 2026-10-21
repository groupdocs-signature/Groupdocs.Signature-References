---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Recupera il conteggio dei crediti consumati."
type: docs
weight: 30
url: /it/net/groupdocs.signature/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Recupera il conteggio dei crediti consumati.

```csharp
public static decimal GetConsumptionCredit()
```

### Esempi

L'esempio seguente dimostra come recuperare il conteggio dei crediti consumati.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Vedi anche

* class [Metered](../../metered)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
