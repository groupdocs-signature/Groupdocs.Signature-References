---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Recupera la quantità di MB elaborati."
type: docs
weight: 40
url: /it/net/groupdocs.signature/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Recupera la quantità di MB elaborati.

```csharp
public static decimal GetConsumptionQuantity()
```

### Esempi

L'esempio seguente dimostra come recuperare la quantità di MB elaborati.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Vedi anche

* class [Metered](../../metered)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
