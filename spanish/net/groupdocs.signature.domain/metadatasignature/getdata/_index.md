---
title: GetData
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Obtener objeto del valor de la firma de metadatos sobre la deserialización.
type: docs
weight: 60
url: /es/net/groupdocs.signature.domain/metadatasignature/getdata/
---
## GetData&lt;T&gt;() {#getdata}

Obtener objeto del valor de la firma de metadatos sobre la deserialización.

```csharp
public T GetData<T>()
    where T : class
```

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto para deserializar a partir del valor de metadatos |

### Valor_devuelto

Instancia de objeto T

### Ver también

* class [MetadataSignature](../../metadatasignature)
* espacio de nombres [GroupDocs.Signature.Domain](../../metadatasignature)
* asamblea [GroupDocs.Signature](../../../)

---

## GetData&lt;T&gt;(IDataEncryption) {#getdata_1}

Obtener objeto de texto de firma de metadatos sobre deserialización.

```csharp
public T GetData<T>(IDataEncryption dataEncryption)
    where T : class
```

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto para deserializar del valor de metadatos |
| dataEncryption | Establecer la implementación de cifrado de datos personalizado |

### Ver también

* interface [IDataEncryption](../../../groupdocs.signature.domain.extensions/idataencryption)
* class [MetadataSignature](../../metadatasignature)
* espacio de nombres [GroupDocs.Signature.Domain](../../metadatasignature)
* asamblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->