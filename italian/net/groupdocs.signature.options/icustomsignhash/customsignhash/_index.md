---
title: "CustomSignHash"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Firma l'hash fornito utilizzando un'implementazione di firma personalizzata."
type: docs
weight: 10
url: /it/net/groupdocs.signature.options/icustomsignhash/customsignhash/
---
## ICustomSignHash.CustomSignHash method

Firma l'hash fornito utilizzando un'implementazione di firma personalizzata.

```csharp
public byte[] CustomSignHash(byte[] signableHash, HashAlgorithm hashAlgorithm, 
    SignatureContext signatureContext)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signableHash | Byte[] | Il valore hash da firmare. |
| hashAlgorithm | HashAlgorithm | L'algoritmo hash utilizzato per generare l'hash. |
| signatureContext | SignatureContext | Il contesto che fornisce opzioni aggiuntive relative alla firma. |

### Valore di ritorno

L'hash firmato come array di byte.

### Vedi anche

* enum [HashAlgorithm](../../../groupdocs.signature.domain/hashalgorithm)
* class [SignatureContext](../../signaturecontext)
* interface [ICustomSignHash](../../icustomsignhash)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
