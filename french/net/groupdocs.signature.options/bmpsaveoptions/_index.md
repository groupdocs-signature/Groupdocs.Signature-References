---
title: BmpSaveOptions
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Options denregistrement Bmp pour les documents image.
type: docs
weight: 1290
url: /fr/net/groupdocs.signature.options/bmpsaveoptions/
---
## BmpSaveOptions class

Options d'enregistrement Bmp pour les documents image.

```csharp
public sealed class BmpSaveOptions : ImageSaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BmpSaveOptions](bmpsaveoptions)() | Crée BmpSaveOptions avec les valeurs par défaut. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtient ou définit un indicateur pour ajouter automatiquement une extension lorsqu'elle manquait dans le chemin du fichier de sortie La valeur par défaut est false. |
| [BitsPerPixel](../../groupdocs.signature.options/bmpsaveoptions/bitsperpixel) { get; set; } | Obtient ou définit le nombre de bits d'image par pixel. |
| [Compression](../../groupdocs.signature.options/bmpsaveoptions/compression) { get; set; } | Obtient ou définit la compression. Voir[`BitmapCompression`](../bitmapcompression) . |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Obtient ou définit le format de fichier du document signé. |
| [HorizontalResolution](../../groupdocs.signature.options/bmpsaveoptions/horizontalresolution) { get; set; } | Obtient ou définit la résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de celle transmise. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtient ou définit s'il faut écraser le fichier existant avec le nouveau fichier de sortie. Sinon, un nouveau fichier sera créé avec un numéro comme suffixe. Par défaut, cette valeur est définie sur true, ce qui signifie que le fichier sera écrasé. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtient ou définit le mot de passe pour enregistrer le document signé avec une protection par mot de passe. Cette propriété n'est pas prise en charge pour les documents Image. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtient ou définit s'il faut utiliser le mot de passe de LoadOptions pour enregistrer le document signé comme protégé. La valeur par défaut est true. Cette propriété n'est pas prise en charge pour les documents Image. |
| [VerticalResolution](../../groupdocs.signature.options/bmpsaveoptions/verticalresolution) { get; set; } | Obtient ou définit la résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de celle transmise. |

### Voir également

* class [ImageSaveOptions](../imagesaveoptions)
* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
