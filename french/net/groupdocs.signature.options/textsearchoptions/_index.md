---
title: TextSearchOptions
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Représente les options de recherche pour les signatures textuelles.
type: docs
weight: 1640
url: /fr/net/groupdocs.signature.options/textsearchoptions/
---
## TextSearchOptions class

Représente les options de recherche pour les signatures textuelles.

```csharp
public class TextSearchOptions : SearchOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TextSearchOptions](textsearchoptions#constructor)() | Initialise une nouvelle instance de la classe TextSearchOptions avec les valeurs par défaut. |
| [TextSearchOptions](textsearchoptions#constructor_1)(string) | Initialise une nouvelle instance de la classe TextSearchOptions avec une valeur de texte. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicateur de recherche sur chaque page de document. Par défaut, cette valeur est définie sur true. |
| [MatchType](../../groupdocs.signature.options/textsearchoptions/matchtype) { get; set; } | Obtient ou définit la recherche de type de correspondance de texte. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtient ou définit le numéro de page du document pour la recherche. La valeur est facultative. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Options pour spécifier les pages pour la recherche de signature. |
| [SignatureImplementation](../../groupdocs.signature.options/textsearchoptions/signatureimplementation) { get; set; } | Spécifie l'implémentation de la signature de texte à rechercher. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicateur pour renvoyer uniquement les signatures marquées comme IsSignature. Par défaut, la valeur est false qui indique de renvoyer toutes les signatures qui correspondent aux critères spécifiés. |
| [Text](../../groupdocs.signature.options/textsearchoptions/text) { get; set; } | Spécifie le texte de la signature à faire correspondre lors de la recherche. |

### Remarques

**Apprendre encore plus**

* Utilisation de base de la recherche de signature électronique textuelle par GroupDocs.Signature : [ Comment effectuer une recherche électronique de signatures de texte dans un document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
* Utilisation avancée des paramètres de recherche de signature électronique Texte avec GroupDocs.Signature : [Utilisation avancée des signatures de texte eSearch dans un document et paramètres supplémentaires](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

### Voir également

* class [SearchOptions](../searchoptions)
* espace de noms [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->