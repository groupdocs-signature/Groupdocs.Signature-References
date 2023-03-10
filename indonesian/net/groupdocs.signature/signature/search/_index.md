---
title: Search
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Mencari tanda tangan dalam dokumen menurutSearchOptionsgroupdocs.signature.options/searchoptions daftar.
type: docs
weight: 150
url: /id/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Mencari tanda tangan dalam dokumen menurut[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) daftar.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| searchOptionsList | List`1 | Koleksi opsi pencarian. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SearchResult`](../../../groupdocs.signature.domain/searchresult) dengan daftar Tanda Tangan yang ditemukan.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang mencari tanda tangan elektronik dalam dokumen menggunakan GroupDocs.Signature: [Cara mencari tanda tangan elektronik di dalam dokumen menggunakan C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Lebih lanjut tentang pencarian tanda tangan elektronik tergantung pada jenis eSign: [Kasus penggunaan lanjutan pencarian tanda tangan elektronik dengan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat juga

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Mencari tanda tangan dalam dokumen menurut[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) opsi.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| searchOptions | SearchOptions | Opsi pencarian. |

### Nilai Pengembalian

Mengembalikan daftar tanda tangan yang ditemukan.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang mencari tanda tangan elektronik dalam dokumen menggunakan GroupDocs.Signature: [Cara mencari tanda tangan elektronik di dalam dokumen menggunakan C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Lebih lanjut tentang pencarian tanda tangan elektronik tergantung pada jenis eSign: [Kasus penggunaan lanjutan pencarian tanda tangan elektronik dengan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat juga

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Mencari jenis tanda tangan yang tepat dalam dokumen menurut[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) nilai.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| signatureType | SignatureType | Jenis tanda tangan yang akan dicari. |

### Nilai Pengembalian

Mengembalikan daftar tanda tangan yang ditemukan dengan jenis yang tepat.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang mencari tanda tangan elektronik dalam dokumen menggunakan GroupDocs.Signature: [Cara mencari tanda tangan elektronik di dalam dokumen menggunakan C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Lebih lanjut tentang pencarian tanda tangan elektronik tergantung pada jenis eSign: [Kasus penggunaan lanjutan pencarian tanda tangan elektronik dengan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat juga

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Mencari jenis tanda tangan tertentu dalam dokumen menurut[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) nilai.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Satu atau beberapa jenis tanda tangan untuk ditemukan. |

### Nilai Pengembalian

Mengembalikan contoh dari[`SearchResult`](../../../groupdocs.signature.domain/searchresult) dengan daftar tanda tangan yang ditemukan.

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang mencari tanda tangan elektronik dalam dokumen menggunakan GroupDocs.Signature: [Cara mencari tanda tangan elektronik di dalam dokumen menggunakan C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Lebih lanjut tentang pencarian tanda tangan elektronik tergantung pada jenis eSign: [Kasus penggunaan lanjutan pencarian tanda tangan elektronik dengan GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat juga

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* ruang nama [GroupDocs.Signature](../../signature)
* perakitan [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
