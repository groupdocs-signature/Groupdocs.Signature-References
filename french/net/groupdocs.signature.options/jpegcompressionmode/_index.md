---
title: JpegCompressionMode
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Spécifie les modes de compression JPEG.
type: docs
weight: 1440
url: /fr/net/groupdocs.signature.options/jpegcompressionmode/
---
## JpegCompressionMode enumeration

Spécifie les modes de compression JPEG.

```csharp
public enum JpegCompressionMode
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Baseline | `0` | La compression de base. |
| Progressive | `1` | La compression progressive. |
| Lossless | `2` | La compression sans perte. Utilisez ce type de compression avec précaution car de nombreuses visionneuses d'images ne le prennent pas en charge. Si vous l'utilisez, essayez d'attribuer le [`ColorType`](../jpegsaveoptions/colortype) propriété àGrayscale ouRgb valeurs. |
| JpegLs | `3` | La compression JPEG-LS. Utilisez ce type de compression avec précaution car de nombreuses visionneuses d'images ne le prennent pas en charge. Si vous l'utilisez, essayez d'attribuer le [`ColorType`](../jpegsaveoptions/colortype) propriété àGrayscale valeur. |

### Voir également

* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
