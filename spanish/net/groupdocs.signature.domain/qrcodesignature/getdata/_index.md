---
title: "GetData"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtener el objeto del texto de firma QRCode mediante deserialización."
type: docs
weight: 80
url: /es/net/groupdocs.signature.domain/qrcodesignature/getdata/
---
## GetData&lt;T&gt;() {#getdata}

Obtener el objeto del Texto de la firma QR-Code tras la deserialización.

```csharp
public T GetData<T>()
    where T : class
```

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a deserializar del texto QR-Code |

### Ver también

* class [QrCodeSignature](../../qrcodesignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## GetData&lt;T&gt;(IDataEncryption) {#getdata_1}

Obtener el objeto del Texto de la firma QR-Code tras la deserialización.

```csharp
public T GetData<T>(IDataEncryption dataEncryption)
    where T : class
```

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto a deserializar del texto QR-Code |
| dataEncryption | Establecer implementación personalizada de cifrado de datos |

### Ver también

* interface [IDataEncryption](../../../groupdocs.signature.domain.extensions/idataencryption)
* class [QrCodeSignature](../../qrcodesignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
