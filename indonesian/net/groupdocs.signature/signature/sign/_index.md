---
title: Sign
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Menandatangani dokumen denganSignOptionsgroupdocs.signature.options/signoptions dan simpan hasilnya ke aliran.
type: docs
weight: 160
url: /id/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Menandatangani dokumen dengan[`SignOptions`](../../../groupdocs.signature.options/signoptions) dan simpan hasilnya ke aliran.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran dokumen keluaran. |
| signOptions | SignOptions | Opsi tanda tangan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis tanda tangan elektronik yang didukung oleh GroupDocs.Signature: [Jenis tanda tangan elektronik didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Lebih lanjut tentang cara menandatangani dokumen elektronik di C#: [Cara menandatangani dokumen menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Lihat juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Menandatangani dokumen dengan[`SignOptions`](../../../groupdocs.signature.options/signoptions)dan menyimpan hasil ke aliran dengan standar[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran dokumen keluaran. |
| signOptions | SignOptions | Opsi tanda tangan. |
| saveOptions | SaveOptions | Opsi simpan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis tanda tangan elektronik yang didukung oleh GroupDocs.Signature: [Jenis tanda tangan elektronik didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Lebih lanjut tentang cara menandatangani dokumen elektronik di C#: [Cara menandatangani dokumen menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Lebih lanjut tentang cara menyimpan dokumen yang ditandatangani secara elektronik dan menyesuaikan proses penyimpanan: [Cara menyesuaikan dokumen yang ditandatangani secara elektronik saat disimpan menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Lihat juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Menandatangani dokumen dengan koleksi[`SignOptions`](../../../groupdocs.signature.options/signoptions) dan simpan hasilnya ke aliran.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran dokumen keluaran. |
| signOptionsList | List`1 | Daftar opsi tanda tangan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis tanda tangan elektronik yang didukung oleh GroupDocs.Signature: [Jenis tanda tangan elektronik didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Lebih lanjut tentang cara menandatangani dokumen elektronik di C#: [Cara menandatangani dokumen menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Lihat juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Menandatangani dokumen dengan koleksi[`SignOptions`](../../../groupdocs.signature.options/signoptions)dan menyimpan hasil ke aliran dengan standar[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran dokumen keluaran. |
| signOptionsList | List`1 | Daftar opsi tanda tangan. |
| saveOptions | SaveOptions | Opsi simpan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis tanda tangan elektronik yang didukung oleh GroupDocs.Signature: [Jenis tanda tangan elektronik didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Lebih lanjut tentang cara menandatangani dokumen elektronik di C#: [Cara menandatangani dokumen menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Lebih lanjut tentang cara menyimpan dokumen yang ditandatangani secara elektronik dan menyesuaikan proses penyimpanan: [Cara menyesuaikan dokumen yang ditandatangani secara elektronik saat disimpan menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Lihat juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Menandatangani dokumen dengan[`SignOptions`](../../../groupdocs.signature.options/signoptions) dan simpan hasilnya ke jalur file yang ditentukan.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file keluaran. |
| signOptions | SignOptions | Opsi tanda tangan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis tanda tangan elektronik yang didukung oleh GroupDocs.Signature: [Jenis tanda tangan elektronik didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Lebih lanjut tentang cara menandatangani dokumen elektronik di C#: [Cara menandatangani dokumen menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Lihat juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Menandatangani dokumen dengan[`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan yang telah ditentukan sebelumnya[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file keluaran. |
| signOptions | SignOptions | Opsi tanda tangan. |
| saveOptions | SaveOptions | Opsi simpan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis tanda tangan elektronik yang didukung oleh GroupDocs.Signature: [Jenis tanda tangan elektronik didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Lebih lanjut tentang cara menandatangani dokumen elektronik di C#: [Cara menandatangani dokumen menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Lebih lanjut tentang cara menyimpan dokumen yang ditandatangani secara elektronik dan menyesuaikan proses penyimpanan: [Cara menyesuaikan dokumen yang ditandatangani secara elektronik saat disimpan menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Lihat juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Menandatangani dokumen dengan koleksi[`SignOptions`](../../../groupdocs.signature.options/signoptions) dan simpan hasilnya ke jalur file yang ditentukan.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file keluaran. |
| signOptionsList | List`1 | Daftar opsi tanda tangan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis tanda tangan elektronik yang didukung oleh GroupDocs.Signature: [Jenis tanda tangan elektronik didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Lebih lanjut tentang cara menandatangani dokumen elektronik di C#: [Cara menandatangani dokumen menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Lihat juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Menandatangani dokumen dengan koleksi[`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan yang telah ditentukan sebelumnya[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file keluaran. |
| signOptionsList | List`1 | Daftar opsi tanda tangan. |
| saveOptions | SaveOptions | Opsi simpan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis tanda tangan elektronik yang didukung oleh GroupDocs.Signature: [Jenis tanda tangan elektronik didukung oleh GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Lebih lanjut tentang cara menandatangani dokumen elektronik di C#: [Cara menandatangani dokumen menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Lebih lanjut tentang cara menyimpan dokumen yang ditandatangani secara elektronik dan menyesuaikan proses penyimpanan: [Cara menyesuaikan dokumen yang ditandatangani secara elektronik saat disimpan menggunakan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Lihat juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
