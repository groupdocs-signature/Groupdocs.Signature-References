---
title: "Kelas MetadataSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi tanda tangan Metadata."
type: docs
url: /id/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

Mewakili opsi tanda tangan Metadata.

Pelajari lebih lanjut

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

Tipe MetadataSignOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | Menginisialisasi instance baru dari kelas MetadataSignOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | Menginisialisasi instance baru dari [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) dengan metadata. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | Tambahkan instance MetadataSignature yang ada ke koleksi. |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | Membuat ImageMetadataSignature baru dengan argumen yang diberikan dan menambahkannya ke koleksi. |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | Membuat PdfMetadataSignature baru dengan argumen yang diberikan dan menambahkannya ke koleksi. |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | Implementasi [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) yang digunakan untuk mengenkripsi semua tanda tangan metadata dalam koleksi opsi ini. |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | Tanda tangan metadata yang terkait dengan tanda tangan. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Tanda tangan akan ditempatkan pada semua halaman dokumen. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Penampilan tanda tangan tambahan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Tipe dokumen dari opsi tanda tangan (`DocumentType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Ekstensi tanda tangan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Algoritma hash yang akan digunakan untuk operasi kriptografi. Didukung secara eksklusif untuk tanda tangan digital dalam file PDF. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Nomor halaman dokumen untuk penandatanganan. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Opsi untuk menentukan halaman yang akan ditandatangani. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Tipe tanda tangan (`SignatureType`). (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Posisi urutan Z dari tanda tangan teks, yang menentukan urutan tampilan tanda tangan yang tumpang tindih. (diturunkan dari [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Contoh

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s).")
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
