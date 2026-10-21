---
title: "Cari"
second_title: "Referensi API GroupDocs.Signature untuk .NET"
description: "Mencari tanda tangan dalam dokumen dengan daftar SearchOptionsgroupdocs.signature.options/searchoptions."
type: docs
weight: 150
url: /id/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Mencari tanda tangan dalam dokumen dengan daftar [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchOptionsList | List`1 | Koleksi opsi pencarian. |

### Nilai Kembali

Mengembalikan instance dari [`SearchResult`](../../../groupdocs.signature.domain/searchresult) dengan daftar tanda tangan yang ditemukan.

### Catatan

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat Juga

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

Mencari tanda tangan dalam dokumen menggunakan opsi pencarian yang disediakan dan menyaring hasil berdasarkan predikat yang ditentukan.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchOptionsList | List`1 | Daftar [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) yang mendefinisikan kriteria pencarian tanda tangan. |
| predicate | Func`2 | Predicate filter yang diterapkan pada daftar tanda tangan yang ditemukan. |

### Nilai Kembali

Mengembalikan sebuah [`SearchResult`](../../../groupdocs.signature.domain/searchresult) yang berisi tanda tangan yang cocok dengan opsi pencarian yang ditentukan dan memenuhi predicate.

### Catatan

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat Juga

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

Mencari tanda tangan dalam dokumen dengan opsi [`SearchOptions`](../../../groupdocs.signature.options/searchoptions).

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchOptions | SearchOptions | Opsi pencarian. |

### Nilai Kembali

Mengembalikan daftar tanda tangan yang ditemukan.

### Catatan

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat Juga

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

Mencari tipe tepat tanda tangan dalam dokumen dengan nilai [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureType | SignatureType | Tipe tanda tangan yang akan dicari. |

### Nilai Kembali

Mengembalikan daftar tanda tangan yang ditemukan dengan tipe tepat.

### Catatan

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat Juga

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Mencari tipe tanda tangan yang ditentukan dalam dokumen dengan nilai [`SignatureType`](../../../groupdocs.signature.domain/signaturetype).

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Satu atau beberapa jenis tanda tangan untuk ditemukan. |

### Nilai Kembali

Mengembalikan instance dari [`SearchResult`](../../../groupdocs.signature.domain/searchresult) dengan daftar tanda tangan yang ditemukan.

### Catatan

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat Juga

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

Mencari tanda tangan dalam dokumen menggunakan semua opsi pencarian yang tersedia dan menyaring hasil berdasarkan predikat yang ditentukan.

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| predicate | Func`2 | Predicate filter yang diterapkan pada daftar tanda tangan yang ditemukan. |

### Nilai Kembali

Mengembalikan daftar instance [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) yang memenuhi predikat yang diberikan.

### Catatan

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Lihat Juga

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
