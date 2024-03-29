---
title: ProcessProgressEventArgs
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Fournit des données pour lévénement OnProgress des processus de signature de vérification et de recherche.
type: docs
weight: 1840
url: /fr/net/groupdocs.signature/processprogresseventargs/
---
## ProcessProgressEventArgs class

Fournit des données pour l'événement OnProgress des processus de signature, de vérification et de recherche.

```csharp
public class ProcessProgressEventArgs : ProcessEventArgs
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ProcessProgressEventArgs](processprogresseventargs)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Cancel](../../groupdocs.signature/processprogresseventargs/cancel) { get; set; } | Indique si le processus doit être annulé. |
| [ProcessedSignatures](../../groupdocs.signature/processprogresseventargs/processedsignatures) { get; set; } | Représente la quantité de signatures traitées. |
| [Progress](../../groupdocs.signature/processprogresseventargs/progress) { get; set; } | Représente la progression en pourcentage. La plage de valeurs est de 0 à 100. |
| [Status](../../groupdocs.signature/processeventargs/status) { get; set; } | Indique l'état actuel du processus. |
| [Ticks](../../groupdocs.signature/processprogresseventargs/ticks) { get; set; } | Représente le temps passé en millisecondes depuis l'événement de démarrage du processus. |

### Voir également

* class [ProcessEventArgs](../processeventargs)
* espace de noms [GroupDocs.Signature](../../groupdocs.signature)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
