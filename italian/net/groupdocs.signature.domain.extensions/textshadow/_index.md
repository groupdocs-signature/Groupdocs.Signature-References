---
title: "TextShadow"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le proprietà dell'ombra del testo per le firme di testo. Il risultato può variare a seconda del tipo di firma e del formato del documento. TextShadow è consigliato per l'uso con la firma TextAsImage per tutti i tipi di documento supportati, anche con TextSignature semplice e TextSignature come filigrana per Spreadsheets .xslx e Presentations .pptx. TextSignature semplice per Words .docx è consigliato anche se ha funzionalità limitate."
type: docs
weight: 560
url: /it/net/groupdocs.signature.domain.extensions/textshadow/
---
## TextShadow class

Rappresenta le proprietà dell'ombra del testo per le firme di testo. Il risultato può variare a seconda del tipo di firma e del formato del documento. TextShadow è consigliato per l'uso con la firma TextAsImage per tutti i tipi di documento supportati, anche con TextSignature semplice e TextSignature come filigrana per Fogli di calcolo (.xslx) e Presentazioni (.pptx). TextSignature semplice per Word (.docx) è consigliato anch'esso, ma ha funzionalità limitate.

```csharp
public class TextShadow : SignatureExtension
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextShadow](textshadow)() | Crea TextShadow con le opzioni predefinite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Angle](../../groupdocs.signature.domain.extensions/textshadow/angle) { get; set; } | Ottiene o imposta l'angolo per posizionare l'ombra rispetto al testo. Il valore predefinito è 0. |
| [Blur](../../groupdocs.signature.domain.extensions/textshadow/blur) { get; set; } | Ottiene o imposta la sfocatura dell'ombra. Il valore predefinito è 4. |
| [Color](../../groupdocs.signature.domain.extensions/textshadow/color) { get; set; } | Ottiene o imposta il colore dell'ombra. Il valore predefinito è Nero. |
| [Distance](../../groupdocs.signature.domain.extensions/textshadow/distance) { get; set; } | Ottiene o imposta la distanza dal testo all'ombra. Il valore predefinito è 1. |
| [Transparency](../../groupdocs.signature.domain.extensions/textshadow/transparency) { get; set; } | Ottiene o imposta la trasparenza dell'ombra. Il valore predefinito è 0. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain.extensions/signatureextension/clone)() | Ottiene una copia di questo oggetto. |

### Vedi anche

* class [SignatureExtension](../signatureextension)
* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
