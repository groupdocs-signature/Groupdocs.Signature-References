---
title: "EPC"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa el Quick Response Code del European Payments Council."
type: docs
weight: 250
url: /es/net/groupdocs.signature.domain.extensions/epc/
---
## EPC class

Representa el Quick Response Code del European Payments Council.

```csharp
public sealed class EPC
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EPC](epc)() | Instancia un nuevo objeto EPC. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [Amount](../../groupdocs.signature.domain.extensions/epc/amount) { get; set; } | Obtiene o establece la cantidad. |
| [BIC](../../groupdocs.signature.domain.extensions/epc/bic) { get; set; } | Obtiene o establece el BIC del beneficiario con una longitud de hasta 11 caracteres. |
| [Charset](../../groupdocs.signature.domain.extensions/epc/charset) { get; } | Implementación del conjunto de caracteres EPC / SEPA QR-Code. Por defecto, este valor se establece en 1. |
| [Code](../../groupdocs.signature.domain.extensions/epc/code) { get; set; } | Obtiene o establece el código de negocio con hasta 4 caracteres. |
| [IBAN](../../groupdocs.signature.domain.extensions/epc/iban) { get; set; } | Obtiene o establece la cuenta del beneficiario (IBAN). El IBAN consta de hasta 34 caracteres alfanuméricos. |
| [Identification](../../groupdocs.signature.domain.extensions/epc/identification) { get; } | Identificación EPC / SEPA QR-Code. Por defecto, este valor se establece en SCT. |
| [Information](../../groupdocs.signature.domain.extensions/epc/information) { get; set; } | Obtiene o establece la información de pista. Máximo 70 caracteres. |
| [Name](../../groupdocs.signature.domain.extensions/epc/name) { get; set; } | Obtiene o establece el nombre del beneficiario. La longitud máxima es de 70 caracteres. |
| [Reference](../../groupdocs.signature.domain.extensions/epc/reference) { get; set; } | Obtiene o establece la referencia de pago (máximo 35 caracteres). Este campo y el campo de Información de Remesa son mutuamente excluyentes. |
| [Remittance](../../groupdocs.signature.domain.extensions/epc/remittance) { get; set; } | Obtiene o establece la información de remesa (máximo 140 caracteres). Este campo y el campo de Referencia de Pago son mutuamente excluyentes. |
| [Version](../../groupdocs.signature.domain.extensions/epc/version) { get; } | Implementación de la versión EPC / SEPA QR-Code. Por defecto, este valor se establece en 002. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.signature.domain.extensions/epc/equals)(object) | Sobrescribe el método Equals para comparar las propiedades de EPC |
| override [GetHashCode](../../groupdocs.signature.domain.extensions/epc/gethashcode)() | Sobrescribe el método GetHashCode |

### Ver también

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
