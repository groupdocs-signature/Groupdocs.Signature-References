---
title: "kelas PdfMetadataSignatures"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Berisi tanda tangan metadata standar untuk opsi tanda tangan metadata dokumen PDF."
type: docs
url: /id/python-net/groupdocs.signature.domain/pdfmetadatasignatures/
is_root: false
weight: 450
---


## PdfMetadataSignatures class

Berisi tanda tangan metadata standar untuk opsi tanda tangan metadata dokumen PDF.

Tipe PdfMetadataSignatures menampilkan anggota berikut:

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [AUTHOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/author/) | metadata Penulis Dokumen PDF. |
| [CREATE_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/create_date/) | tanda tangan metadata tanggal pembuatan Dokumen PDF. |
| [METADATA_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/metadata_date/) | informasi tanggal metadata Dokumen PDF. |
| [CREATOR_TOOL](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator_tool/) | tanda tangan metadata alat pembuatan Dokumen PDF. |
| [MODIFY_DATE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/modify_date/) | properti metadata tanggal modifikasi Dokumen PDF. |
| [PRODUCER](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/producer/) | properti metadata Produsen Dokumen PDF. |
| [ENTRY](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/entry/) | properti metadata Entri Dokumen PDF. |
| [KEYWORDS](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/keywords/) | properti metadata pembuat Dokumen PDF |
| [TITLE](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/title/) | properti metadata Judul Dokumen PDF |
| [SUBJECT](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/subject/) | properti metadata Subjek Dokumen PDF. |
| [DESCRIPTION](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/description/) | properti metadata Deskripsi Dokumen PDF. |
| [CREATOR](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignatures/creator/) | properti metadata pembuat Dokumen PDF. |

### Contoh

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

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
