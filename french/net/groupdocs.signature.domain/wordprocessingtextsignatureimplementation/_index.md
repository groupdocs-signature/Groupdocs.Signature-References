---
title: WordProcessingTextSignatureImplementation
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Spécifie le type dimplémentation de signature de texte pour les documents WordProcessing.
type: docs
weight: 1060
url: /fr/net/groupdocs.signature.domain/wordprocessingtextsignatureimplementation/
---
## WordProcessingTextSignatureImplementation enumeration

Spécifie le type d'implémentation de signature de texte pour les documents WordProcessing.

```csharp
public enum WordProcessingTextSignatureImplementation
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| TextStamp | `0` | Signature de texte en tant qu'objet Étiquette sur la page Mots. |
| TextAsImage | `1` | Signature de texte en tant qu'objet Image sur la page Mots. |
| TextToFormField | `2` | Signature de texte sous forme de texte dans le champ de formulaire spécifié. Avec ce type d'implémentation, seules les options TextSignOptions.Text, TextSignOptions.FormTextFieldTitle et TextSignOptions.FormTextFieldType peuvent être utilisées. |
| Watermark | `3` | Signature textuelle en filigrane sur la page Words. |

### Voir également

* espace de noms [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Assemblée [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->