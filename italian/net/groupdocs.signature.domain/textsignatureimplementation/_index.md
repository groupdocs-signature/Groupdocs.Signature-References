---
title: TextSignatureImplementation
second_title: Riferimento API GroupDocs.Signature per .NET
description: Specifica il tipo di implementazione per la firma del testo PDF.
type: docs
weight: 1010
url: /it/net/groupdocs.signature.domain/textsignatureimplementation/
---
## TextSignatureImplementation enumeration

Specifica il tipo di implementazione per la firma del testo PDF.

```csharp
public enum TextSignatureImplementation
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Native | `1` | Testo Firma come oggetto di testo nativo sulla pagina del documento. |
| Image | `2` | Firma testo come oggetto immagine sulla pagina del documento. |
| Annotation | `3` | Firma testo come oggetto Annotazione testo sulla pagina PDF. Le annotazioni sono visibili solo per la versione con licenza. |
| Sticker | `4` | Firma testo come oggetto adesivo sulla pagina PDF. |
| FormField | `5` | Text Signature come testo nel campo modulo specificato. Con questo tipo di implementazione possono essere utilizzate solo le opzioni TextSignOptions.Text, TextSignOptions.FormTextFieldType e TextSignOptions.FormTextFieldTitle. |
| Watermark | `6` | Testo Firma come filigrana sulla pagina del documento. |

### Guarda anche

* spazio dei nomi [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
