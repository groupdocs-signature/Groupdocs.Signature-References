---
title: "ToDateTime"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Convierte a DateTime."
type: docs
weight: 100
url: /es/net/groupdocs.signature.domain/metadatasignature/todatetime/
---
## ToDateTime() {#todatetime}

Convierte a DateTime.

```csharp
public virtual DateTime ToDateTime()
```

### Valor de retorno

Devuelve el valor de la Metadata Signature como DateTime.

### Observaciones

Lanza una excepción si el valor de Metadata no pudo ser convertido. Si el valor original es de tipo cadena, se utilizará la información de la propiedad de cultura predeterminada de las propiedades de SignatureSettings [`DefaultCulture`](../../../groupdocs.signature/signaturesettings/defaultculture)

### Ver también

* class [MetadataSignature](../../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## ToDateTime(IFormatProvider) {#todatetime_1}

Convierte a DateTime.

```csharp
public virtual DateTime ToDateTime(IFormatProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| provider | IFormatProvider | Proveedor de formato de datos a usar con operaciones de conversión de datos. |

### Valor de retorno

Devuelve el valor de la Metadata Signature como DateTime.

### Observaciones

Lanza una excepción si el valor de Metadata no pudo ser convertido

### Ver también

* class [MetadataSignature](../../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
