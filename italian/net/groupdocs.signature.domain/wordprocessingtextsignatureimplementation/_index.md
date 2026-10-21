---
title: "WordProcessingTextSignatureImplementation"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Specifica il tipo di implementazione della firma di testo per i documenti di elaborazione testi."
type: docs
weight: 1280
url: /it/net/groupdocs.signature.domain/wordprocessingtextsignatureimplementation/
---
## WordProcessingTextSignatureImplementation enumeration

Specifica il tipo di implementazione della firma di testo per i documenti di elaborazione testi.

```csharp
public enum WordProcessingTextSignatureImplementation
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| TextStamp | `0` | Firma di testo come oggetto Etichetta nella pagina Words. |
| TextAsImage | `1` | Firma di testo come oggetto Immagine nella pagina Words. |
| TextToFormField | `2` | Firma di testo come testo in un campo modulo specificato. Con questo tipo di implementazione è possibile utilizzare solo le opzioni TextSignOptions.Text, TextSignOptions.FormTextFieldTitle e TextSignOptions.FormTextFieldType. |
| Watermark | `3` | Firma di testo come filigrana nella pagina Words. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
