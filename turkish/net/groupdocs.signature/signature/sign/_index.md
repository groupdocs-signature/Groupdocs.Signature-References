---
title: "İmzala"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Belgeyi SignOptionsgroupdocs.signature.options/signoptions ile imzalar ve sonucu bir akışa kaydeder."
type: docs
weight: 160
url: /tr/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Belgeyi [`SignOptions`](../../../groupdocs.signature.options/signoptions) ile imzalar ve sonucu bir akışa kaydeder.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | Stream | Çıktı belge akışı. |
| signOptions | SignOptions | İmza seçenekleri. |

### Dönüş Değeri

[`SignResult`](../../../groupdocs.signature.domain/signresult) örneğini, yeni oluşturulan imzaların listesiyle döndürür.

### Açıklamalar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ayrıca Bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Belgeyi [`SignOptions`](../../../groupdocs.signature.options/signoptions) ile imzalar ve sonucu önceden tanımlı [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) ile bir akışa kaydeder.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | Stream | Çıktı belge akışı. |
| signOptions | SignOptions | İmza seçenekleri. |
| saveOptions | SaveOptions | Kaydetme seçenekleri. |

### Dönüş Değeri

[`SignResult`](../../../groupdocs.signature.domain/signresult) örneğini, yeni oluşturulan imzaların listesiyle döndürür.

### Açıklamalar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ayrıca Bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Belgeyi [`SignOptions`](../../../groupdocs.signature.options/signoptions) koleksiyonu ile imzalar ve sonucu bir akışa kaydeder.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | Stream | Çıktı belge akışı. |
| signOptionsList | List`1 | İmza seçeneklerinin listesi. |

### Dönüş Değeri

[`SignResult`](../../../groupdocs.signature.domain/signresult) örneğini, yeni oluşturulan imzaların listesiyle döndürür.

### Açıklamalar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ayrıca Bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Belgeyi [`SignOptions`](../../../groupdocs.signature.options/signoptions) koleksiyonu ile imzalar ve sonucu önceden tanımlı [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) ile bir akışa kaydeder.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | Stream | Çıktı belge akışı. |
| signOptionsList | List`1 | İmza seçeneklerinin listesi. |
| saveOptions | SaveOptions | Kaydetme seçenekleri. |

### Dönüş Değeri

[`SignResult`](../../../groupdocs.signature.domain/signresult) örneğini, yeni oluşturulan imzaların listesiyle döndürür.

### Açıklamalar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ayrıca Bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Belgeyi [`SignOptions`](../../../groupdocs.signature.options/signoptions) ile imzalar ve sonucu belirtilen dosya yoluna kaydeder.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | Dize | Çıktı dosya yolu. |
| signOptions | SignOptions | İmza seçenekleri. |

### Dönüş Değeri

[`SignResult`](../../../groupdocs.signature.domain/signresult) örneğini, yeni oluşturulan imzaların listesiyle döndürür.

### Açıklamalar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ayrıca Bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Belgeyi [`SignOptions`](../../../groupdocs.signature.options/signoptions) ile imzalar ve sonucu belirtilen dosya yoluna önceden tanımlı [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) ile kaydeder.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | Dize | Çıktı dosya yolu. |
| signOptions | SignOptions | İmza seçenekleri. |
| saveOptions | SaveOptions | Kaydetme seçenekleri. |

### Dönüş Değeri

[`SignResult`](../../../groupdocs.signature.domain/signresult) örneğini, yeni oluşturulan imzaların listesiyle döndürür.

### Açıklamalar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ayrıca Bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Belgeyi [`SignOptions`](../../../groupdocs.signature.options/signoptions) koleksiyonu ile imzalar ve sonucu belirtilen dosya yoluna kaydeder.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | Dize | Çıktı dosya yolu. |
| signOptionsList | List`1 | İmza seçeneklerinin listesi. |

### Dönüş Değeri

[`SignResult`](../../../groupdocs.signature.domain/signresult) örneğini, yeni oluşturulan imzaların listesiyle döndürür.

### Açıklamalar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ayrıca Bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Belgeyi [`SignOptions`](../../../groupdocs.signature.options/signoptions) koleksiyonu ile imzalar ve sonucu belirtilen dosya yoluna önceden tanımlı [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) ile kaydeder.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | Dize | Çıktı dosya yolu. |
| signOptionsList | List`1 | İmza seçeneklerinin listesi. |
| saveOptions | SaveOptions | Kaydetme seçenekleri. |

### Dönüş Değeri

[`SignResult`](../../../groupdocs.signature.domain/signresult) örneğini, yeni oluşturulan imzaların listesiyle döndürür.

### Açıklamalar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ayrıca Bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
