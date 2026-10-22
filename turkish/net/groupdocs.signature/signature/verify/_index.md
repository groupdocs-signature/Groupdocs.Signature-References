---
title: "Doğrula"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Belge imzalarını verilen VerifyOptions verileriyle doğrular."
type: docs
weight: 180
url: /tr/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Belge imzalarını verilen VerifyOptions verileriyle doğrular.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| verifyOptions | VerifyOptions | İmza doğrulama seçenekleri. |

### Dönüş Değeri

[`VerificationResult`](../../../groupdocs.signature.domain/verificationresult) örneğini döndürür. VerificationResult.IsValid özelliği, doğrulama işlemi başarılıysa true döndürür.

### Açıklamalar

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Ayrıca Bakınız

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Belge imzalarını sağlanan doğrulama seçeneklerini kullanarak doğrular ve sonuçları belirtilen koşula göre filtreler. Bu yöntem önce doğrulama seçenekleriyle eşleşen imzaları arar, bunları koşula göre filtreler ve ardından yalnızca filtrelenen imzaları doğrular.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| verifyOptions | VerifyOptions | İmza doğrulama seçenekleri. |
| predicate | Func`2 | Doğrulanacak imzaları belirlemek için filtre koşulu. |

### Dönüş Değeri

Sağlanan koşulu sağlayan [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) örneklerinin bir listesini döndürür.

### Açıklamalar

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Ayrıca Bakınız

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Belge imzalarını VerifyOptions verileri listesiyle doğrular.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| verifyOptionsList | List`1 | İmza doğrulama seçenekleri koleksiyonu. VerifyOptionsCollection örneği. |

### Dönüş Değeri

[`VerificationResult`](../../../groupdocs.signature.domain/verificationresult) örneğini döndürür. VerificationResult.IsValid özelliği, doğrulama işlemi başarılıysa true döndürür.

### Açıklamalar

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Ayrıca Bakınız

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Belge imzalarını mevcut tüm doğrulama seçeneklerini kullanarak doğrular ve sonuçları belirtilen koşula göre filtreler. Bu yöntem önce doğrulama seçenekleriyle eşleşen imzaları arar, bunları koşula göre filtreler ve ardından yalnızca filtrelenen imzaları doğrular.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| verifyOptionsList | List`1 | İmza doğrulama seçenekleri koleksiyonu. VerifyOptionsCollection örneği. |
| predicate | Func`2 | Doğrulanacak imzaları belirlemek için filtre koşulu. |

### Dönüş Değeri

Sağlanan koşulu sağlayan [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) örneklerinin bir listesini döndürür.

### Açıklamalar

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Ayrıca Bakınız

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
