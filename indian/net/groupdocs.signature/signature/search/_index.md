---
title: Search
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: द्वर दस्तवेज़ में हस्तक्षर क खज करत हैSearchOptionsgroupdocs.signature.options/searchoptions सूच.
type: docs
weight: 150
url: /hi/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

द्वारा दस्तावेज़ में हस्ताक्षर की खोज करता है[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) सूची.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchOptionsList | List`1 | खोज विकल्प संग्रह। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SearchResult`](../../../groupdocs.signature.domain/searchresult) पाए गए हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs.Signature का उपयोग करके दस्तावेज़ों में इलेक्ट्रॉनिक हस्ताक्षर खोजने के बारे में अधिक जानकारी: [सी # का उपयोग कर दस्तावेज़ के अंदर इलेक्ट्रॉनिक हस्ताक्षर कैसे खोजें I](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* ई-साइन प्रकार पर निर्भर इलेक्ट्रॉनिक हस्ताक्षर खोज के बारे में अधिक जानकारी: [GroupDocs.Signature के साथ इलेक्ट्रॉनिक हस्ताक्षर खोज के उन्नत उपयोग के मामले](https://docs.groupdocs.com/display/signaturenet/Searching)

### यह सभी देखें

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

द्वारा दस्तावेज़ में हस्ताक्षर की खोज करता है[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) विकल्प.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| searchOptions | SearchOptions | खोज विकल्प। |

### प्रतिलाभ की मात्रा

मिले हस्ताक्षरों की सूची लौटाता है।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs.Signature का उपयोग करके दस्तावेज़ों में इलेक्ट्रॉनिक हस्ताक्षर खोजने के बारे में अधिक जानकारी: [सी # का उपयोग कर दस्तावेज़ के अंदर इलेक्ट्रॉनिक हस्ताक्षर कैसे खोजें I](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* ई-साइन प्रकार पर निर्भर इलेक्ट्रॉनिक हस्ताक्षर खोज के बारे में अधिक जानकारी: [GroupDocs.Signature के साथ इलेक्ट्रॉनिक हस्ताक्षर खोज के उन्नत उपयोग के मामले](https://docs.groupdocs.com/display/signaturenet/Searching)

### यह सभी देखें

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

द्वारा दस्तावेज़ में सटीक प्रकार के हस्ताक्षरों की खोज करता है[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) मान.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureType | SignatureType | खोजने के लिए हस्ताक्षर का प्रकार। |

### प्रतिलाभ की मात्रा

सटीक प्रकार के साथ पाए गए हस्ताक्षरों की सूची लौटाता है।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs.Signature का उपयोग करके दस्तावेज़ों में इलेक्ट्रॉनिक हस्ताक्षर खोजने के बारे में अधिक जानकारी: [सी # का उपयोग कर दस्तावेज़ के अंदर इलेक्ट्रॉनिक हस्ताक्षर कैसे खोजें I](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* ई-साइन प्रकार पर निर्भर इलेक्ट्रॉनिक हस्ताक्षर खोज के बारे में अधिक जानकारी: [GroupDocs.Signature के साथ इलेक्ट्रॉनिक हस्ताक्षर खोज के उन्नत उपयोग के मामले](https://docs.groupdocs.com/display/signaturenet/Searching)

### यह सभी देखें

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

द्वारा दस्तावेज़ में निर्दिष्ट हस्ताक्षर प्रकारों की खोज करता है[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) मान.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureTypes | SignatureType[] | खोजने के लिए एक या कई प्रकार के हस्ताक्षर। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SearchResult`](../../../groupdocs.signature.domain/searchresult) पाए गए हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs.Signature का उपयोग करके दस्तावेज़ों में इलेक्ट्रॉनिक हस्ताक्षर खोजने के बारे में अधिक जानकारी: [सी # का उपयोग कर दस्तावेज़ के अंदर इलेक्ट्रॉनिक हस्ताक्षर कैसे खोजें I](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* ई-साइन प्रकार पर निर्भर इलेक्ट्रॉनिक हस्ताक्षर खोज के बारे में अधिक जानकारी: [GroupDocs.Signature के साथ इलेक्ट्रॉनिक हस्ताक्षर खोज के उन्नत उपयोग के मामले](https://docs.groupdocs.com/display/signaturenet/Searching)

### यह सभी देखें

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
