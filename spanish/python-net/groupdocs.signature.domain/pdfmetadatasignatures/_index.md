---
title: "PdfMetadataSignatures clase"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Contiene firmas de metadatos estándar para opciones de firma de metadatos de documentos PDF."
type: docs
url: /es/python-net/groupdocs.signature.domain/pdfmetadatasignatures/
is_root: false
weight: 450
---


## PdfMetadataSignatures class

Contiene firmas de metadatos estándar para opciones de firma de metadatos de documentos PDF.

El tipo PdfMetadataSignatures expone los siguientes miembros:

### Campos
| Campo | Descripción |
| :- | :- |
| [AUTHOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/author/) | Metadatos del autor del documento PDF. |
| [CREATE_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/create_date/) | Firma de metadatos de la fecha de creación del documento PDF. |
| [METADATA_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/metadata_date/) | Información de fecha de metadatos del documento PDF. |
| [CREATOR_TOOL](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator_tool/) | Firma de metadatos de la herramienta de creación del documento PDF. |
| [MODIFY_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/modify_date/) | Propiedad de metadatos de la fecha de modificación del documento PDF. |
| [PRODUCER](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/producer/) | Propiedad de metadatos del productor del documento PDF. |
| [ENTRY](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/entry/) | Propiedad de metadatos de la entrada del documento PDF. |
| [KEYWORDS](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/keywords/) | Propiedad de metadatos del creador del documento PDF |
| [TITLE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/title/) | Propiedad de metadatos del título del documento PDF |
| [SUBJECT](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/subject/) | Propiedad de metadatos del asunto del documento PDF. |
| [DESCRIPTION](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/description/) | Propiedad de metadatos de la descripción del documento PDF. |
| [CREATOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator/) | Propiedad de metadatos del creador del documento PDF. |

### Ejemplo

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

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
