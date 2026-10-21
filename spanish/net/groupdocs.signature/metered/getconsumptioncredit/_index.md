---
title: "GetConsumptionCredit"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Recupera el recuento de créditos consumidos."
type: docs
weight: 30
url: /es/net/groupdocs.signature/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Recupera el recuento de créditos consumidos.

```csharp
public static decimal GetConsumptionCredit()
```

### Ejemplos

El siguiente ejemplo muestra cómo obtener el recuento de créditos consumidos.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
