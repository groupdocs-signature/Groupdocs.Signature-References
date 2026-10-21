---
title: "GetData"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene el objeto del Valor de Metadata Signature durante la deserialización."
type: docs
weight: 70
url: /es/net/groupdocs.signature.domain/metadatasignature/getdata/
---
## GetData&lt;T&gt;() {#getdata}

Obtiene el objeto del Valor de Metadata Signature durante la deserialización.

```csharp
public T GetData<T>()
    where T : class
```

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto para deserializar del valor de Metadata |

### Valor de retorno

Instancia del objeto T

### Ver también

* class [MetadataSignature](../../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## GetData&lt;T&gt;(IDataEncryption) {#getdata_1}

Obtiene el objeto del Texto de Metadata Signature durante la deserialización.

```csharp
public T GetData<T>(IDataEncryption dataEncryption)
    where T : class
```

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto para deserializar del Valor de Metadata |
| dataEncryption | Establecer implementación personalizada de cifrado de datos |

### Ver también

* interface [IDataEncryption](../../../groupdocs.signature.domain.extensions/idataencryption)
* class [MetadataSignature](../../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
