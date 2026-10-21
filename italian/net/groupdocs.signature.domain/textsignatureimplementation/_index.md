---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Specifica il tipo di implementazione per la firma di testo PDF."
type: docs
weight: 1200
url: /it/net/groupdocs.signature.domain/textsignatureimplementation/
---
## TextSignatureImplementation enumeration

Specifica il tipo di implementazione per la firma di testo PDF.

```csharp
public enum TextSignatureImplementation
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Native | `1` | Firma di testo come oggetto di testo nativo nella pagina del documento. |
| Image | `2` | Firma di testo come oggetto Immagine nella pagina del documento. |
| Annotation | `3` | Firma di testo come oggetto Annotazione di testo nella pagina PDF. Le annotazioni sono visibili solo nella versione con licenza. |
| Sticker | `4` | Firma di testo come oggetto Adesivo nella pagina PDF. |
| FormField | `5` | Firma di testo come testo in campo modulo specificato. Con questo tipo di implementazione possono essere usate solo le opzioni TextSignOptions.Text, TextSignOptions.FormTextFieldType e TextSignOptions.FormTextFieldTitle. |
| Watermark | `6` | Firma di testo come filigrana nella pagina del documento. |

### Vedi anche

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
