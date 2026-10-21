---
title: "Referencia"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece la referencia de pago del acreedor. La referencia es obligatoria para los IBAN SwissQR, es decir, los IBAN en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx. Si se especifica, la referencia debe ser una referencia SwissQR válida que corresponda al formulario de referencia ISR o una referencia de acreedor válida según ISO 11649 RFxxxx. Ambas pueden contener espacios para el formato."
type: docs
weight: 80
url: /es/net/groupdocs.signature.domain.extensions/swissqr/reference/
---
## SwissQR.Reference property

Obtiene o establece la referencia de pago del acreedor. La referencia es obligatoria para los IBAN SwissQR, es decir, IBAN en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx. Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente al formulario de referencia ISR) o una referencia de acreedor válida según ISO 11649 ("RFxxxx"). Ambas pueden contener espacios para el formato.

```csharp
public string Reference { get; set; }
```

### Property Value

La referencia de pago del acreedor.

### Ver también

* class [SwissQR](../../swissqr)
* namespace [GroupDocs.Signature.Domain.Extensions](../../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
