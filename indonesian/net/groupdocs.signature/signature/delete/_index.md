---
title: Delete
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Menghapus tanda tangan yang diberikanBaseSignaturegroupdocs.signature.domain/basesignature dari dokumen.
type: docs
weight: 110
url: /id/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Menghapus tanda tangan yang diberikan[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dari dokumen.

```csharp
public bool Delete(BaseSignature signature)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| signature | BaseSignature | Objek tanda tangan yang akan dihapus dari dokumen. |

### Nilai Pengembalian

Mengembalikan nilai true jika operasi berhasil.

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara menghapus tanda tangan elektronik dari dokumen di C#: [Cara menghapus eSignature dari dokumen dengan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Kasus penggunaan lanjutan untuk menghapus tanda tangan elektronik dokumen: [Cara menghapus berbagai jenis eSignatures dari dokumen di C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat juga

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Menghapus daftar tanda tangan yang lulus[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dari dokumen.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| signatures | List`1 | Daftar tanda tangan untuk dihapus dari dokumen. |

### Nilai Pengembalian

Mengembalikan DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) dengan daftar tanda tangan yang berhasil dihapus dan yang gagal.

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara menghapus tanda tangan elektronik dari dokumen di C#: [Cara menghapus eSignature dari dokumen dengan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Kasus penggunaan lanjutan untuk menghapus tanda tangan elektronik dokumen: [Cara menghapus berbagai jenis eSignatures dari dokumen di C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat juga

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Menghapus tanda tangan dari jenis tertentu[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan dengan metode Sign dan ditandai sebagai Tanda Tangan[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) akan dihapus. Jenis tanda tangan berikut didukung: Teks, Gambar, Digital, Kode Batang, Kode QR

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| signatureType | SignatureType | Jenis tanda tangan yang akan dihapus dari dokumen. |

### Nilai Pengembalian

Mengembalikan DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) dengan daftar tanda tangan yang berhasil dihapus dan yang gagal.

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara menghapus tanda tangan elektronik dari dokumen di C#: [Cara menghapus eSignatures dengan tipe tertentu dari dokumen dengan GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Kasus penggunaan lanjutan untuk menghapus tanda tangan elektronik dokumen: [Cara menghapus berbagai jenis eSignatures dari dokumen di C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat juga

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Menghapus tanda tangan dari daftar jenis tertentu[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) dari dokumen. Hanya tanda tangan yang ditambahkan dengan metode Sign dan ditandai sebagai Tanda Tangan[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) akan dihapus. Jenis tanda tangan berikut didukung: Teks, Gambar, Digital, Kode Batang, Kode QR

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| signatureTypes | List`1 | Daftar jenis tanda tangan yang akan dihapus dari dokumen. |

### Nilai Pengembalian

Mengembalikan DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) dengan daftar tanda tangan yang berhasil dihapus dan yang gagal.

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara menghapus tanda tangan elektronik dari dokumen di C#: [Cara menghapus eSignatures dengan tipe tertentu dari dokumen dengan GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Kasus penggunaan lanjutan untuk menghapus tanda tangan elektronik dokumen: [Cara menghapus berbagai jenis eSignatures dari dokumen di C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat juga

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Menghapus tanda tangan dengan ID tanda tangan spesifiknya dari dokumen.

```csharp
public bool Delete(string signatureId)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| signatureId | String | Id tanda tangan yang akan dihapus dari dokumen. |

### Nilai Pengembalian

Mengembalikan nilai true jika operasi berhasil.

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara menghapus tanda tangan elektronik dari dokumen di C#: [Cara menghapus eSignature dari dokumen dengan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Kasus penggunaan lanjutan untuk menghapus tanda tangan elektronik dokumen: [Cara menghapus berbagai jenis eSignatures dari dokumen di C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat juga

* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Menghapus daftar tanda tangan yang lulus[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dari dokumen.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| signatureIds | List`1 | Daftar pengidentifikasi tanda tangan yang akan dihapus dari dokumen. |

### Nilai Pengembalian

Mengembalikan DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) dengan daftar tanda tangan yang berhasil dihapus dan yang gagal.

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang cara menghapus tanda tangan elektronik dari dokumen di C#: [Cara menghapus eSignature dari dokumen dengan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Kasus penggunaan lanjutan untuk menghapus tanda tangan elektronik dokumen: [Cara menghapus berbagai jenis eSignatures dari dokumen di C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Lihat juga

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
