---
title: "SwissAddress"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa la dirección del acreedor o deudor. Puede establecer el tipo de dirección estructurada con calle, número de casa, código postal y localidad, o el tipo de elementos de dirección combinados con la línea de dirección 1 y 2."
type: docs
weight: 510
url: /es/net/groupdocs.signature.domain.extensions/swissaddress/
---
## SwissAddress class

Representa la dirección del acreedor o deudor. Puede establecer la calle, número, código postal y localidad (tipo de dirección estructurada) o la línea de dirección 1 y 2 (tipo de elementos de dirección combinados).

```csharp
public class SwissAddress
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SwissAddress](swissaddress)() | El constructor predeterminado. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddressLine1](../../groupdocs.signature.domain.extensions/swissaddress/addressline1) { get; set; } | Obtiene o establece la línea de dirección 1. La línea de dirección 1 contiene el nombre de la calle, el número de casa o apartado postal. Este campo solo se usa para direcciones con elementos combinados y es opcional. |
| [AddressLine2](../../groupdocs.signature.domain.extensions/swissaddress/addressline2) { get; set; } | Obtiene o establece la línea de dirección 2. La línea de dirección 2 contiene el código postal y la localidad. Este campo solo se usa para direcciones con elementos combinados. Para este tipo, es obligatorio. |
| [CountryCode](../../groupdocs.signature.domain.extensions/swissaddress/countrycode) { get; set; } | Obtiene o establece el código de país ISO de dos letras. El código de país es obligatorio a menos que toda la dirección contenga valores nulos o vacíos. |
| [HouseNo](../../groupdocs.signature.domain.extensions/swissaddress/houseno) { get; set; } | Obtiene o establece el número de casa. Este campo solo se usa para direcciones estructuradas y es opcional. |
| [Name](../../groupdocs.signature.domain.extensions/swissaddress/name) { get; set; } | Obtiene o establece el nombre, ya sea el nombre y apellido de una persona física o la razón social de una persona jurídica. |
| [PostalCode](../../groupdocs.signature.domain.extensions/swissaddress/postalcode) { get; set; } | Obtiene o establece el código postal. Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio. |
| [Street](../../groupdocs.signature.domain.extensions/swissaddress/street) { get; set; } | Obtiene o establece la calle. La calle debe especificarse sin número de casa. Este campo solo se usa para direcciones estructuradas y es opcional. |
| [Town](../../groupdocs.signature.domain.extensions/swissaddress/town) { get; set; } | Obtiene o establece la localidad o ciudad. Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio. |

### Ver también

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
