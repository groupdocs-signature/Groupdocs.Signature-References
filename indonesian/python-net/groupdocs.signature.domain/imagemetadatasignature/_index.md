---
title: "kelas ImageMetadataSignature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili tanda tangan metadata gambar."
type: docs
url: /id/python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 320
---


## ImageMetadataSignature class

Mewakili tanda tangan metadata gambar.

Signature metadata untuk dokumen gambar adalah tanda tangan elektronik berdasarkan standar metadata gambar seperti EXIF. Setiap tanda tangan diidentifikasi oleh pengenal numerik (0‑65535) dan menyimpan nilai dari berbagai tipe (teks, tanggal/waktu, integer, floating‑point).

Tipe ImageMetadataSignature menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#id-value) | Menginisialisasi Image Metadata Signature dengan pengenal dan nilai yang ditentukan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/) | Menggandakan instance Tanda Tangan Metadata. |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#value) | Menggandakan instance ImageMetadataSignature dengan nilai yang diberikan. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals/#obj) | Menentukan apakah objek tanda tangan yang ditentukan sama dengan instance ini. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/get_hash_code/) | Mengembalikan kode hash untuk tanda tangan. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/) | Mengonversi nilai signature metadata menjadi boolean. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/) | Mengonversi nilai signature metadata menjadi `datetime.datetime`. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#provider) | Mengonversi nilai signature metadata menjadi `datetime`. |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time_iformat_provider/) |  |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/) | Mengonversi menjadi Decimal. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#provider) | Mengonversi nilai signature metadata menjadi desimal. |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal_iformat_provider/) |  |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/) | Mengonversi menjadi float. |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#provider) | Mengonversi nilai tanda tangan metadata ke float. |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double_iformat_provider/) |  |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/) | Mengonversi nilai tanda tangan metadata ke integer. |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/) | Mengonversi menjadi long. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/) | Mengonversi ke float. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#provider) | Mengonversi nilai tanda tangan metadata ke float. |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single_iformat_provider/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/) | Mengonversi nilai signature metadata menjadi string. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format) | Mengonversi nilai signature metadata menjadi string menggunakan format yang ditentukan. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#format-provider) | Mengonversi menjadi string dengan format yang ditentukan. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string_string/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (diturunkan dari [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (diturunkan dari [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description/) | Deskripsi tanda tangan standar Image Metadata. |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id/) | Pengidentifikasi tanda tangan Image Metadata. Lihat kelas `GroupDocs.Signature.Domain.ImageMetadataSignatures` yang berisi Signature standar dengan nilai Id yang telah ditentukan. |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size/) | Ukuran nilai metadata. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Tanggal pembuatan tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | Implementasi [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) yang digunakan untuk mengenkripsi dan mendekripsi properti nilai tanda tangan. (diturunkan dari [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bendera yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Tinggi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bendera yang menunjukkan apakah komponen ini mewakili tanda tangan (`True`) atau konten dokumen (`False`). (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Posisi kiri tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Tanggal modifikasi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | Nama metadata unik. (diturunkan dari [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Nomor halaman tempat tanda tangan ditemukan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Pengidentifikasi unik tanda tangan, digunakan untuk memodifikasi tanda tangan dalam dokumen melalui operasi pembaruan atau penghapusan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Jenis tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Posisi atas tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | Tipe nilai metadata. (diturunkan dari [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | Objek metadata. (diturunkan dari [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Lebar tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Contoh

```python
from datetime import datetime

from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature


def sign_png():
    with Signature("sample.png") as signature:
        options = MetadataSignOptions()

        metadata_id = 41996
        options.add(ImageMetadataSignature(metadata_id, "Mr.Scherlock Holmes"))   # text
        options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
        options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # whole number
        options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # floating‑point number

        result = signature.sign("signed.png", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.id}")
```

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
