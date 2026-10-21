---
title: "SwissQR"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Clase para codificar y decodificar el texto incrustado en el código SwissQR."
type: docs
weight: 520
url: /es/net/groupdocs.signature.domain.extensions/swissqr/
---
## SwissQR class

Clase para codificar y decodificar el texto incrustado en el código SwissQR.

```csharp
public class SwissQR
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SwissQR](swissqr)() | Crea una instancia de SwissQR. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Account](../../groupdocs.signature.domain.extensions/swissqr/account) { get; set; } | Obtiene o establece el número de cuenta del acreedor. Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein. Se permiten espacios en el número de cuenta. |
| [Amount](../../groupdocs.signature.domain.extensions/swissqr/amount) { get; set; } | Obtiene o establece el importe del pago. Los valores válidos están entre 0.01 y 999,999,999.99. |
| [BillInformation](../../groupdocs.signature.domain.extensions/swissqr/billinformation) { get; set; } | Obtiene o establece la información estructurada adicional de la factura. |
| [Creditor](../../groupdocs.signature.domain.extensions/swissqr/creditor) { get; set; } | Obtiene o establece la dirección del acreedor. |
| [Currency](../../groupdocs.signature.domain.extensions/swissqr/currency) { get; set; } | Obtiene o establece la moneda del pago. Los valores válidos son "CHF" y "EUR". |
| [Debtor](../../groupdocs.signature.domain.extensions/swissqr/debtor) { get; set; } | Obtiene o establece la dirección del deudor. El deudor es opcional. Si se omite, tanto establecer este campo como null como establecer una dirección con todos los valores null o vacíos es aceptable. |
| [Reference](../../groupdocs.signature.domain.extensions/swissqr/reference) { get; set; } | Obtiene o establece la referencia de pago del acreedor. La referencia es obligatoria para los IBAN SwissQR, es decir, IBAN en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx. Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente al formulario de referencia ISR) o una referencia de acreedor válida según ISO 11649 ("RFxxxx"). Ambas pueden contener espacios para el formato. |
| [UnstructuredMessage](../../groupdocs.signature.domain.extensions/swissqr/unstructuredmessage) { get; set; } | Obtiene o establece el mensaje adicional no estructurado. |

### Ver también

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
