---
title: "Sign"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Menandatangani dokumen dengan SignOptionsgroupdocs.signature.options/signoptions dan menyimpan hasil ke aliran."
type: docs
weight: 160
url: /id/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Menandatangani dokumen dengan [`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke aliran.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Stream | Aliran dokumen output. |
| signOptions | SignOptions | Opsi tanda tangan. |

### Nilai Kembali

Mengembalikan instance dari [`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Catatan

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Lihat Juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Menandatangani dokumen dengan [`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke aliran dengan [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) yang telah ditentukan sebelumnya.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Stream | Aliran dokumen output. |
| signOptions | SignOptions | Opsi tanda tangan. |
| saveOptions | SaveOptions | Opsi penyimpanan. |

### Nilai Kembali

Mengembalikan instance dari [`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Catatan

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Lihat Juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Menandatangani dokumen dengan koleksi [`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke aliran.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Stream | Aliran dokumen output. |
| signOptionsList | List`1 | Daftar opsi tanda tangan. |

### Nilai Kembali

Mengembalikan instance dari [`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Catatan

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Lihat Juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Menandatangani dokumen dengan koleksi [`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke aliran dengan [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) yang telah ditentukan sebelumnya.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Stream | Aliran dokumen output. |
| signOptionsList | List`1 | Daftar opsi tanda tangan. |
| saveOptions | SaveOptions | Opsi penyimpanan. |

### Nilai Kembali

Mengembalikan instance dari [`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Catatan

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Lihat Juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Menandatangani dokumen dengan [`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file output. |
| signOptions | SignOptions | Opsi tanda tangan. |

### Nilai Kembali

Mengembalikan instance dari [`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Catatan

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Lihat Juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Menandatangani dokumen dengan [`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) yang telah ditentukan sebelumnya.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file output. |
| signOptions | SignOptions | Opsi tanda tangan. |
| saveOptions | SaveOptions | Opsi penyimpanan. |

### Nilai Kembali

Mengembalikan instance dari [`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Catatan

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Lihat Juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Menandatangani dokumen dengan koleksi [`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file output. |
| signOptionsList | List`1 | Daftar opsi tanda tangan. |

### Nilai Kembali

Mengembalikan instance dari [`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Catatan

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Lihat Juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Menandatangani dokumen dengan koleksi [`SignOptions`](../../../groupdocs.signature.options/signoptions) dan menyimpan hasil ke jalur file yang ditentukan dengan [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) yang telah ditentukan sebelumnya.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file output. |
| signOptionsList | List`1 | Daftar opsi tanda tangan. |
| saveOptions | SaveOptions | Opsi penyimpanan. |

### Nilai Kembali

Mengembalikan instance dari [`SignResult`](../../../groupdocs.signature.domain/signresult) dengan daftar tanda tangan yang baru dibuat.

### Catatan

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Lihat Juga

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
