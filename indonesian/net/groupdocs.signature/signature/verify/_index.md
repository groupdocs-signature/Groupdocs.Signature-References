---
title: "Verifikasi"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan."
type: docs
weight: 180
url: /id/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Opsi verifikasi tanda tangan. |

### Nilai Kembali

Mengembalikan instance dari [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Properti VerificationResult.IsValid mengembalikan true jika proses verifikasi berhasil.

### Catatan

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Lihat Juga

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Memverifikasi tanda tangan dokumen menggunakan opsi verifikasi yang disediakan dan menyaring hasil berdasarkan predikat yang ditentukan. Metode ini pertama mencari tanda tangan yang cocok dengan opsi verifikasi, menyaringnya menggunakan predikat, dan kemudian memverifikasi hanya tanda tangan yang telah disaring tersebut.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Opsi verifikasi tanda tangan. |
| predicate | Func`2 | Predicate filter untuk menentukan tanda tangan mana yang harus diverifikasi. |

### Nilai Kembali

Mengembalikan daftar instance [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) yang memenuhi predikat yang diberikan.

### Catatan

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Lihat Juga

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Memverifikasi tanda tangan dokumen dengan daftar data VerifyOptions.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| verifyOptionsList | List`1 | Koleksi opsi verifikasi tanda tangan. Instance dari VerifyOptionsCollection. |

### Nilai Kembali

Mengembalikan instance dari [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Properti VerificationResult.IsValid mengembalikan true jika proses verifikasi berhasil.

### Catatan

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Lihat Juga

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Memverifikasi tanda tangan dokumen menggunakan semua opsi verifikasi yang tersedia dan menyaring hasil berdasarkan predikat yang ditentukan. Metode ini pertama mencari tanda tangan yang cocok dengan opsi verifikasi, menyaringnya menggunakan predikat, dan kemudian memverifikasi hanya tanda tangan yang telah disaring tersebut.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| verifyOptionsList | List`1 | Koleksi opsi verifikasi tanda tangan. Instance dari VerifyOptionsCollection. |
| predicate | Func`2 | Predicate filter untuk menentukan tanda tangan mana yang harus diverifikasi. |

### Nilai Kembali

Mengembalikan daftar instance [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) yang memenuhi predikat yang diberikan.

### Catatan

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Lihat Juga

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
