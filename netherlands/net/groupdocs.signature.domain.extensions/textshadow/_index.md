---
title: TextShadow
second_title: GroupDocs.Signature voor .NET API-referentie
description: Vertegenwoordigt tekstschaduweigenschappen voor teksthandtekeningen. Het resultaat kan variëren afhankelijk van het type handtekening en documentindeling. TextShadow wordt aanbevolen voor gebruik met TextAsImagehandtekening voor alle ondersteunde documenttypen ook met eenvoudige TextSignature en TextSignature als watermerk voor Spreadsheets  .xslx en Presentations .pptx. Simple TextSignature for Words .docx wordt ook aanbevolen maar heeft beperkte functionaliteit.
type: docs
weight: 400
url: /nl/net/groupdocs.signature.domain.extensions/textshadow/
---
## TextShadow class

Vertegenwoordigt tekstschaduweigenschappen voor teksthandtekeningen. Het resultaat kan variëren afhankelijk van het type handtekening en documentindeling. TextShadow wordt aanbevolen voor gebruik met TextAsImage-handtekening voor alle ondersteunde documenttypen, ook met eenvoudige TextSignature en TextSignature als watermerk voor Spreadsheets ( .xslx) en Presentations (.pptx). Simple TextSignature for Words (.docx) wordt ook aanbevolen, maar heeft beperkte functionaliteit.

```csharp
public class TextShadow : SignatureExtension
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [TextShadow](textshadow)() | Creëert TextShadow met standaardopties. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Angle](../../groupdocs.signature.domain.extensions/textshadow/angle) { get; set; } | Haalt of stelt de hoek in voor het plaatsen van schaduw ten opzichte van de tekst. Standaardwaarde is 0. |
| [Blur](../../groupdocs.signature.domain.extensions/textshadow/blur) { get; set; } | Vervaging van de schaduw ophalen of instellen. Standaardwaarde is 4. |
| [Color](../../groupdocs.signature.domain.extensions/textshadow/color) { get; set; } | Kleur van de schaduw ophalen of instellen. Standaardwaarde is Zwart. |
| [Distance](../../groupdocs.signature.domain.extensions/textshadow/distance) { get; set; } | Haalt of stelt de afstand van tekst tot schaduw in. Standaardwaarde is 1. |
| [Transparency](../../groupdocs.signature.domain.extensions/textshadow/transparency) { get; set; } | Hiermee wordt de transparantie van de schaduw opgehaald of ingesteld. Standaardwaarde is 0. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain.extensions/signatureextension/clone)() | Krijgt een kopie van dit object. |

### Zie ook

* class [SignatureExtension](../signatureextension)
* naamruimte [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->