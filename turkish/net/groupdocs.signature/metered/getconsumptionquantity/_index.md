---
title: GetConsumptionQuantity
second_title: .NET API Başvurusu için GroupDocs.Signature
description: İşlenen MB miktarını alır.
type: docs
weight: 40
url: /tr/net/groupdocs.signature/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

İşlenen MB miktarını alır.

```csharp
public static decimal GetConsumptionQuantity()
```

### Örnekler

Aşağıdaki örnek, işlenen MB miktarının nasıl alınacağını gösterir.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Ayrıca bakınız

* class [Metered](../../metered)
* ad alanı [GroupDocs.Signature](../../metered)
* toplantı [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->