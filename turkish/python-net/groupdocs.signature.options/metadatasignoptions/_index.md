---
title: "MetadataSignOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Meta veri imza seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 320
---


## MetadataSignOptions class

Meta veri imza seçeneklerini temsil eder.

Daha fazla bilgi edinin

- Basic usage of creating Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature
- Advanced usage of settings of Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced

MetadataSignOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/) | MetadataSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#signatures) | [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) sınıfının yeni bir örneğini metadata ile başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#metadata_signature) | Mevcut MetadataSignature örneğini koleksiyona ekle. |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#id-value) | Verilen argümanlarla yeni bir ImageMetadataSignature oluşturur ve koleksiyona ekler. |
| [add_image_signature_uint16](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature_uint16/) |  |
| [add_metadata_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_metadata_signature/) |  |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#name-value-tag) | Verilen argümanlarla yeni bir PdfMetadataSignature oluşturur ve koleksiyona ekler. |
| [add_pdf_signature_file](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_file/) |  |
| [add_pdf_signature_string](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature_string/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/) | Bu seçenekler koleksiyonundaki tüm metadata imzalarını şifrelemek için kullanılan [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) uygulaması. |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures/) | İmza ile ilişkili metadata imzaları. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | İmza tüm belge sayfalarına yerleştirilecektir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Ek imza görünümü. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | İmza seçeneklerinin belge tipi (`DocumentType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | İmza uzantıları. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Kriptografik işlemler için kullanılacak hash algoritması. Yalnızca PDF dosyalarındaki dijital imzalar için desteklenir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | İmzalama için belge sayfa numarası. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | İmzalanacak sayfaları belirtmek için seçenekler. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | İmza tipi (`SignatureType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Metin imzasının Z-sırası konumu, üst üste gelen imzaların görüntülenme sırasını belirler. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |

### Örnek

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

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
