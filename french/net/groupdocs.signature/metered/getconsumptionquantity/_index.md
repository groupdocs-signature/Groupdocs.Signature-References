---
title: GetConsumptionQuantity
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Récupère le nombre de Mo traités.
type: docs
weight: 40
url: /fr/net/groupdocs.signature/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Récupère le nombre de Mo traités.

```csharp
public static decimal GetConsumptionQuantity()
```

### Exemples

L'exemple suivant montre comment récupérer le nombre de Mo traités.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Voir également

* class [Metered](../../metered)
* espace de noms [GroupDocs.Signature](../../metered)
* Assemblée [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
