---
title: "classe PdfMetadataSignatures"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Contiene firme di metadati standard per le opzioni di firma di metadati del documento PDF."
type: docs
url: /it/python-net/groupdocs.signature.domain/pdfmetadatasignatures/
is_root: false
weight: 450
---


## PdfMetadataSignatures class

Contiene firme di metadati standard per le opzioni di firma di metadati del documento PDF.

Il tipo PdfMetadataSignatures espone i seguenti membri:

### Campi
| Campo | Descrizione |
| :- | :- |
| [AUTHOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/author/) | Metadati dell'autore del documento PDF. |
| [CREATE_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/create_date/) | Firma dei metadati della data di creazione del documento PDF. |
| [METADATA_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/metadata_date/) | Informazioni sulla data dei metadati del documento PDF. |
| [CREATOR_TOOL](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator_tool/) | Firma dei metadati dello strumento di creazione del documento PDF. |
| [MODIFY_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/modify_date/) | Proprietà dei metadati della data di modifica del documento PDF. |
| [PRODUCER](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/producer/) | Proprietà dei metadati del produttore del documento PDF. |
| [ENTRY](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/entry/) | Proprietà dei metadati dell'entrata del documento PDF. |
| [KEYWORDS](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/keywords/) | Proprietà dei metadati del creatore del documento PDF |
| [TITLE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/title/) | Proprietà dei metadati del titolo del documento PDF |
| [SUBJECT](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/subject/) | Proprietà dei metadati dell'oggetto del documento PDF. |
| [DESCRIPTION](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/description/) | Proprietà dei metadati della descrizione del documento PDF. |
| [CREATOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator/) | Proprietà dei metadati del creatore del documento PDF. |

### Esempio

```python
from datetime import datetime, timedelta

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures


def sign_pdf_standard():
    with Signature("sample.pdf") as signature:
        options = MetadataSignOptions()

        now = datetime.now()
        signatures = [
            PdfMetadataSignatures.AUTHOR.clone("Mr.Scherlock Holmes"),
            PdfMetadataSignatures.CREATE_DATE.clone(now - timedelta(days=1)),
            PdfMetadataSignatures.METADATA_DATE.clone(now - timedelta(days=2)),
            PdfMetadataSignatures.CREATOR_TOOL.clone("GD.Signature-Test"),
            PdfMetadataSignatures.MODIFY_DATE.clone(now - timedelta(days=13)),
            PdfMetadataSignatures.PRODUCER.clone("GroupDocs-Producer"),
            PdfMetadataSignatures.ENTRY.clone("Signature"),
            PdfMetadataSignatures.KEYWORDS.clone("GroupDocs, Signature, Metadata, Creation Tool"),
            PdfMetadataSignatures.TITLE.clone("Metadata Example"),
            PdfMetadataSignatures.SUBJECT.clone("Metadata Test Example"),
            PdfMetadataSignatures.DESCRIPTION.clone("Metadata Test example description"),
            PdfMetadataSignatures.CREATOR.clone("GroupDocs.Signature"),
        ]

        options.signatures.add_range(signatures)
```

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
