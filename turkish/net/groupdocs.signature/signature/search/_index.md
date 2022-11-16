---
title: Search
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Şuna göre bir belgede imza ararSearchOptionsgroupdocs.signature.options/searchoptions liste.
type: docs
weight: 150
url: /tr/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Şuna göre bir belgede imza arar:[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) liste.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| searchOptionsList | List`1 | Arama seçenekleri koleksiyonu. |

### Geri dönüş değeri

örneğini döndürür[`SearchResult`](../../../groupdocs.signature.domain/searchresult) bulunan İmzaların listesiyle birlikte.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Signature kullanarak belgelerde elektronik imza arama hakkında daha fazla bilgi: [C# kullanarak belge içinde elektronik imzalar nasıl aranır?](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* eSign türüne bağlı elektronik imza araması hakkında daha fazla bilgi: [GroupDocs.Signature ile arama yapan elektronik imzaların gelişmiş kullanım örnekleri](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca bakınız

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Şuna göre bir belgede imza arar:[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) seçenekler.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| searchOptions | SearchOptions | Arama seçenekleri. |

### Geri dönüş değeri

Bulunan imzaların listesini döndürür.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Signature kullanarak belgelerde elektronik imza arama hakkında daha fazla bilgi: [C# kullanarak belge içinde elektronik imzalar nasıl aranır?](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* eSign türüne bağlı elektronik imza araması hakkında daha fazla bilgi: [GroupDocs.Signature ile arama yapan elektronik imzaların gelişmiş kullanım örnekleri](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca bakınız

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Şuna göre belgedeki tam imza türlerini arar:[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) değer.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| signatureType | SignatureType | Aranacak imzaların türü. |

### Geri dönüş değeri

Bulunan imzaların listesini tam türde döndürür.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Signature kullanarak belgelerde elektronik imza arama hakkında daha fazla bilgi: [C# kullanarak belge içinde elektronik imzalar nasıl aranır?](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* eSign türüne bağlı elektronik imza araması hakkında daha fazla bilgi: [GroupDocs.Signature ile arama yapan elektronik imzaların gelişmiş kullanım örnekleri](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca bakınız

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Şuna göre belgede belirtilen imza türlerini arar:[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) değer.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Bulunacak bir veya birkaç imza türü. |

### Geri dönüş değeri

örneğini döndürür[`SearchResult`](../../../groupdocs.signature.domain/searchresult) Bulunan imzaların listesiyle birlikte.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Signature kullanarak belgelerde elektronik imza arama hakkında daha fazla bilgi: [C# kullanarak belge içinde elektronik imzalar nasıl aranır?](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* eSign türüne bağlı elektronik imza araması hakkında daha fazla bilgi: [GroupDocs.Signature ile arama yapan elektronik imzaların gelişmiş kullanım örnekleri](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ayrıca bakınız

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
