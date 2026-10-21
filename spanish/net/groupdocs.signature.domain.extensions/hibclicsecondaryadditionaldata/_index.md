---
title: "HIBCLICSecondaryAdditionalData"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Clase para almacenar datos secundarios y adicionales del HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 320
url: /es/net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/
---
## HIBCLICSecondaryAdditionalData class

Clase para almacenar datos secundarios y adicionales HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

```csharp
public class HIBCLICSecondaryAdditionalData : ICloneable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HIBCLICSecondaryAdditionalData](hibclicsecondaryadditionaldata)() | Predeterminado ctor() |

## Properties

| Nombre | Descripción |
| --- | --- |
| [DateOfManufacture](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/dateofmanufacture) { get; set; } | Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Valor predeterminado: DateTime.MinValue. |
| [ExpiryDate](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/expirydate) { get; set; } | Identifica la fecha de caducidad. Se utilizará si ExpiryDateFormat no está configurado en None. |
| [ExpiryDateFormat](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/expirydateformat) { get; set; } | Identifica el formato de la fecha de caducidad. |
| [LinkCharacter](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/linkcharacter) { get; set; } | Identifica el carácter de enlace en la cadena de salida. |
| [LotNumber](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/lotnumber) { get; set; } | Identifica el número de lote o partida. El número de lote/partida debe ser una cadena alfanumérica con una longitud máxima de 18 símbolos. |
| [Quantity](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/quantity) { get; set; } | Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1. |
| [SerialNumber](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/serialnumber) { get; set; } | Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/clone)() | Obtiene una copia de este objeto. |

### Ver también

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
