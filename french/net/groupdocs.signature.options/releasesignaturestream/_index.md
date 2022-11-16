---
title: ReleaseSignatureStream
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Délégué qui définit la méthode pour publier le flux daperçu de la signature de sortie.
type: docs
weight: 1580
url: /fr/net/groupdocs.signature.options/releasesignaturestream/
---
## ReleaseSignatureStream delegate

Délégué qui définit la méthode pour publier le flux d'aperçu de la signature de sortie.

```csharp
public delegate void ReleaseSignatureStream(PreviewSignatureOptions previewOptions, 
    Stream signatureStream);
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| previewOptions | PreviewSignatureOptions | Les options de signature prévisualisée. |
| signatureStream | Stream | Flux d'images de signature à publier. |

### Voir également

* class [PreviewSignatureOptions](../previewsignatureoptions)
* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->