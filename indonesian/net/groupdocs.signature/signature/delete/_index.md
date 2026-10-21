---
title: "Delete"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Menghapus tanda tangan yang diberikan BaseSignaturegroupdocs.signature.domain/basesignature dari dokumen."
type: docs
weight: 110
url: /id/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Menghapus tanda tangan yang diberikan [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dari dokumen.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signature | BaseSignature | Objek tanda tangan yang akan dihapus dari dokumen. |

### Nilai Kembali

Mengembalikan true jika operasi berhasil.

### Catatan

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat Juga

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Menghapus daftar tanda tangan yang diberikan [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dari dokumen.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tanda tangan | List`1 | Daftar tanda tangan untuk dihapus dari dokumen. |

### Nilai Kembali

Mengembalikan DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) dengan daftar tanda tangan yang berhasil dihapus dan yang gagal.

### Catatan

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat Juga

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Menghapus tanda tangan dengan tipe tertentu [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan oleh metode Sign dan ditandai sebagai Signatures [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) yang akan dihapus. Tipe tanda tangan berikut didukung: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureType | SignatureType | Tipe tanda tangan yang akan dihapus dari dokumen. |

### Nilai Kembali

Mengembalikan DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) dengan daftar tanda tangan yang berhasil dihapus dan yang gagal.

### Catatan

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat Juga

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Menghapus tanda tangan dari daftar tipe tertentu [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan oleh metode Sign dan ditandai sebagai Signatures [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) yang akan dihapus. Tipe tanda tangan berikut didukung: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureTypes | List`1 | Daftar tipe tanda tangan yang akan dihapus dari dokumen. |

### Nilai Kembali

Mengembalikan DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) dengan daftar tanda tangan yang berhasil dihapus dan yang gagal.

### Catatan

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat Juga

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Menghapus tanda tangan berdasarkan Id tanda tangan spesifiknya dari dokumen.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureId | String | Id dari tanda tangan yang akan dihapus dari dokumen. |

### Nilai Kembali

Mengembalikan true jika operasi berhasil.

### Catatan

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat Juga

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Menghapus daftar tanda tangan yang diberikan [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dari dokumen.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureIds | List`1 | Daftar pengidentifikasi tanda tangan yang akan dihapus dari dokumen. |

### Nilai Kembali

Mengembalikan DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) dengan daftar tanda tangan yang berhasil dihapus dan yang gagal.

### Catatan

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat Juga

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
