---
title: "Mailmark2D"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Clase para codificar y decodificar el texto incrustado en el Royal Mail 2D Mailmark."
type: docs
weight: 400
url: /es/net/groupdocs.signature.domain.extensions/mailmark2d/
---
## Mailmark2D class

Clase para codificar y decodificar el texto incrustado en el Royal Mail 2D Mailmark.

```csharp
public class Mailmark2D : ICloneable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Mailmark2D](mailmark2d)() | Crea datos combinados de Royal Mail Mailmark con valores predeterminados de datos primarios y secundarios. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Class](../../groupdocs.signature.domain.extensions/mailmark2d/class) { get; set; } | Identifica la clase del elemento. |
| [CustomerContent](../../groupdocs.signature.domain.extensions/mailmark2d/customercontent) { get; set; } | Espacio opcional para uso del cliente. |
| [CustomerContentEncodeMode](../../groupdocs.signature.domain.extensions/mailmark2d/customercontentencodemode) { get; set; } | Modo de codificación del código de barras DataMatrix. Valor predeterminado: DataMatrixEncodeMode.C40. [`DataMatrixEncodeMode`](../datamatrixencodemode) |
| [DataMatrixType](../../groupdocs.signature.domain.extensions/mailmark2d/datamatrixtype) { get; set; } | El tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
| [DestinationPostCodeAndDPS](../../groupdocs.signature.domain.extensions/mailmark2d/destinationpostcodeanddps) { get; set; } | Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres: Área (1 o 2 caracteres) Distrito (1 o 2 caracteres) Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres). El código postal y el DPS deben cumplir con un formato PAF® válido. La longitud máxima es 9. |
| [InformationTypeID](../../groupdocs.signature.domain.extensions/mailmark2d/informationtypeid) { get; set; } | Identifica la carga útil del código de barras Mailmark de Royal Mail para cada tipo de producto. |
| [ItemID](../../groupdocs.signature.domain.extensions/mailmark2d/itemid) { get; set; } | Identifica el elemento único dentro del ID de la cadena de suministro. Cada código de barras Mailmark debe llevar un ID para que pueda ser identificado de forma única durante al menos 90 días. Valor máximo: 99999999. |
| [ReturnToSenderPostCode](../../groupdocs.signature.domain.extensions/mailmark2d/returntosenderpostcode) { get; set; } | Contiene el código postal de devolución al remitente pero sin DPS. El PC (sin DPS) debe cumplir con un formato PAF®. |
| [RTSFlag](../../groupdocs.signature.domain.extensions/mailmark2d/rtsflag) { get; set; } | Indicador que muestra qué nivel del servicio de devolución al remitente se está solicitando. La longitud máxima es 1. |
| [SupplyChainID](../../groupdocs.signature.domain.extensions/mailmark2d/supplychainid) { get; set; } | Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999. |
| [UPUCountryID](../../groupdocs.signature.domain.extensions/mailmark2d/upucountryid) { get; set; } | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| [VersionID](../../groupdocs.signature.domain.extensions/mailmark2d/versionid) { get; } | Identifica la versión del código de barras según cada ID de tipo de información. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.signature.domain.extensions/mailmark2d/clone)() | Obtiene una copia de este objeto. |

### Ver también

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
