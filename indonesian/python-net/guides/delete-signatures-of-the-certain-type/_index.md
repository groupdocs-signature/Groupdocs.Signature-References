---
title: "Hapus tanda tangan dengan tipe tertentu"
linkTitle: "Certain Type"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Artikel ini menjelaskan cara menghapus tanda tangan elektronik dengan tipe tertentu menggunakan API GroupDocs.Signature."
type: docs
url: /id/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Harap diketahui bahwa metode [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) mengubah dokumen yang sama yang diberikan ke konstruktor kelas [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature), sehingga contoh di bawah ini menyalin dokumen yang ditandatangani terlebih dahulu dan menghapus tanda tangan dari salinan tersebut.

## How to delete signatures of the certain type from the document
Berikut langkah-langkah untuk menghapus tanda tangan dengan tipe tertentu dari dokumen menggunakan GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

Contoh ini menunjukkan cara menghapus semua tanda tangan teks dari dokumen. Hanya tanda tangan yang ditambahkan oleh GroupDocs.Signature yang dihapus; teks asli dokumen tetap sebagaimana adanya.

{{< tabs "delete_signatures_by_type" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() menyimpan perubahan ke dalam dokumen yang terbuka, jadi kerjakan pada salinan
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Hapus semua tanda tangan teks dalam dokumen
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab "signed.docx" >}}

`signed.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "all_text_signatures_deleted.docx" >}}
```text
Binary file (DOCX, 147 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/delete_signatures_by_type/all_text_signatures_deleted.docx)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi online dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
