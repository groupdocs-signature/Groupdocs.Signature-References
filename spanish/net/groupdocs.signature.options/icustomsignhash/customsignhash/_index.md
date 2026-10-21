---
title: "CustomSignHash"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Firma el hash proporcionado utilizando una implementación de firma personalizada."
type: docs
weight: 10
url: /es/net/groupdocs.signature.options/icustomsignhash/customsignhash/
---
## ICustomSignHash.CustomSignHash method

Firma el hash proporcionado utilizando una implementación de firma personalizada.

```csharp
public byte[] CustomSignHash(byte[] signableHash, HashAlgorithm hashAlgorithm, 
    SignatureContext signatureContext)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signableHash | Byte[] | El valor hash a firmar. |
| hashAlgorithm | HashAlgorithm | El algoritmo hash utilizado para generar el hash. |
| signatureContext | SignatureContext | El contexto que proporciona opciones adicionales relacionadas con la firma. |

### Valor de retorno

El hash firmado como una matriz de bytes.

### Ver también

* enum [HashAlgorithm](../../../groupdocs.signature.domain/hashalgorithm)
* class [SignatureContext](../../signaturecontext)
* interface [ICustomSignHash](../../icustomsignhash)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
