---
title: SearchResult
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Résultat de la recherche de signatures dans le document spécifié.
type: docs
weight: 830
url: /fr/net/groupdocs.signature.domain/searchresult/
---
## SearchResult class

Résultat de la recherche de signatures dans le document spécifié.

```csharp
public class SearchResult : IEnumerable<BaseSignature>, IResult
```

## Propriétés

| Nom | La description |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/searchresult/destindocumentsize) { get; } | Renvoie la taille du document de destination. Pour la méthode de recherche, il renvoie toujours 0. |
| [ProcessingTime](../../groupdocs.signature.domain/searchresult/processingtime) { get; } | Renvoie le temps d'exécution du processus de recherche en millisecondes. |
| [Signatures](../../groupdocs.signature.domain/searchresult/signatures) { get; } | Liste des signatures trouvées[`BaseSignature`](../basesignature) . |
| [SourceDocumentSize](../../groupdocs.signature.domain/searchresult/sourcedocumentsize) { get; } | Renvoie la taille du document source |
| [Succeeded](../../groupdocs.signature.domain/searchresult/succeeded) { get; } | Liste des signatures trouvées[`BaseSignature`](../basesignature) . Cette liste sera toujours égale à[`Signatures`](./signatures) propriété. |
| [TotalSignatures](../../groupdocs.signature.domain/searchresult/totalsignatures) { get; } | Renvoie le nombre total de signatures traitées par le processus de recherche |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetEnumerator](../../groupdocs.signature.domain/searchresult/getenumerator)() | Renvoie l'énumérateur. |
| [ToList&lt;T&gt;](../../groupdocs.signature.domain/searchresult/tolist)() | Fournit la conversion en liste de signatures fortement typées. |

### Voir également

* class [BaseSignature](../basesignature)
* interface [IResult](../iresult)
* espace de noms [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
