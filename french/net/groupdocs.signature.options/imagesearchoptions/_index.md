---
title: ImageSearchOptions
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Représente les options de recherche pour les signatures dimage.
type: docs
weight: 1330
url: /fr/net/groupdocs.signature.options/imagesearchoptions/
---
## ImageSearchOptions class

Représente les options de recherche pour les signatures d'image.

```csharp
public class ImageSearchOptions : SearchOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageSearchOptions](imagesearchoptions)() | Initialise une nouvelle instance de la classe ImageSearchOptions avec les valeurs par défaut. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicateur de recherche sur chaque page de document. Par défaut, cette valeur est définie sur true. |
| [MaxContentSize](../../groupdocs.signature.options/imagesearchoptions/maxcontentsize) { get; set; } | Pour une valeur non nulle, cet indicateur spécifie la taille maximale des images pour les critères de recherche. Par défaut, cet indicateur est défini sur zéro et n'affecte pas le résultat de la recherche. |
| [MinContentSize](../../groupdocs.signature.options/imagesearchoptions/mincontentsize) { get; set; } | Pour une valeur non nulle, cet indicateur spécifie la taille minimale des images pour les critères de recherche. Par défaut, cet indicateur est défini sur zéro et n'affecte pas le résultat de la recherche. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document pour la recherche. La valeur est facultative. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Options pour spécifier les pages pour la recherche de signature. |
| [ReturnContent](../../groupdocs.signature.options/imagesearchoptions/returncontent) { get; set; } | Obtient ou définit un indicateur pour saisir le contenu de l'image de la signature sur la page du document. Si cet indicateur est défini sur vrai, le contenu de la signature de l'image conservera les données d'image brutes au format requis[`ReturnContentType`](./returncontenttype) . Par défaut cette option est désactivée. |
| [ReturnContentType](../../groupdocs.signature.options/imagesearchoptions/returncontenttype) { get; set; } | Spécifie le type de fichier du contenu renvoyé de la signature d'image lorsque la propriété ReturnContent est activée. Par défaut, il est défini sur Null. Cela signifie renvoyer le contenu de l'image dans son format d'origine. Ce format d'image est spécifié à[`Format`](../../groupdocs.signature.domain/imagesignature/format) Les valeurs possibles prises en charge sont : FileType.JPEG, FileType.PNG, FileType.BMP. Si le format fourni n'est pas pris en charge, le contenu de l'image au format d'origine sera renvoyé. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicateur pour renvoyer uniquement les signatures marquées comme IsSignature. Par défaut, la valeur est false qui indique de renvoyer toutes les signatures qui correspondent aux critères spécifiés. |

### Remarques

**Apprendre encore plus**

* Utilisation de base de la recherche de signature électronique d'image par GroupDocs.Signature : [ Comment effectuer une recherche électronique sur les signatures d'image dans un document](https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures)
* Utilisation avancée des paramètres de recherche de signature électronique Image avec GroupDocs.Signature : [Utilisation avancée des signatures d'image eSearch dans un document et paramètres supplémentaires](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures)

### Voir également

* class [SearchOptions](../searchoptions)
* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->