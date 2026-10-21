---
title: "खोज"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "दस्तावेज़ में हस्ताक्षरों को SearchOptionsgroupdocs.signature.options/searchoptions सूची द्वारा खोजता है।"
type: docs
weight: 150
url: /hi/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

दस्तावेज़ में हस्ताक्षरों को [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) सूची द्वारा खोजता है।

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| searchOptionsList | List`1 | हस्ताक्षर विकल्प संग्रह। |

### वापसी मान

पाई गई हस्ताक्षरों की सूची के साथ [`SearchResult`](../../../groupdocs.signature.domain/searchresult) का उदाहरण लौटाता है।

### टिप्पणियाँ

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### संबंधित देखें

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#search_2}

प्रदान किए गए खोज विकल्पों का उपयोग करके दस्तावेज़ में हस्ताक्षरों को खोजता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है।

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| searchOptionsList | List`1 | हस्ताक्षरों की खोज के मानदंड को परिभाषित करने वाले [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) उदाहरणों की सूची। |
| predicate | Func`2 | पाई गई हस्ताक्षरों की सूची पर लागू करने के लिए फ़िल्टर प्रेडिकेट। |

### वापसी मान

निर्दिष्ट खोज विकल्पों से मेल खाने और प्रेडिकेट को संतुष्ट करने वाले हस्ताक्षरों को सम्मिलित करता हुआ एक [`SearchResult`](../../../groupdocs.signature.domain/searchresult) लौटाता है।

### टिप्पणियाँ

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### संबंधित देखें

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_5}

दस्तावेज़ में हस्ताक्षरों को [`SearchOptions`](../../../groupdocs.signature.options/searchoptions) विकल्पों द्वारा खोजता है।

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| searchOptions | SearchOptions | खोज विकल्प। |

### वापसी मान

पाई गई हस्ताक्षरों की सूची लौटाता है।

### टिप्पणियाँ

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### संबंधित देखें

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_4}

दस्तावेज़ में हस्ताक्षरों के सटीक प्रकार को [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) मान द्वारा खोजता है।

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signatureType | SignatureType | खोजने के लिए हस्ताक्षरों का प्रकार। |

### वापसी मान

सटीक प्रकार के साथ पाई गई हस्ताक्षरों की सूची लौटाता है।

### टिप्पणियाँ

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### संबंधित देखें

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

दस्तावेज़ में निर्दिष्ट हस्ताक्षर प्रकारों को [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) मान द्वारा खोजता है।

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signatureTypes | SignatureType[] | खोजने के लिए एक या कई प्रकार के हस्ताक्षर। |

### वापसी मान

वापस देता है [`SearchResult`](../../../groupdocs.signature.domain/searchresult) का उदाहरण जिसमें पाए गए हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### संबंधित देखें

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Search(Func&lt;BaseSignature, bool&gt;) {#search_3}

दस्तावेज़ में सभी उपलब्ध खोज विकल्पों का उपयोग करके हस्ताक्षरों की खोज करता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है।

```csharp
public List<BaseSignature> Search(Func<BaseSignature, bool> predicate)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| predicate | Func`2 | पाई गई हस्ताक्षरों की सूची पर लागू करने के लिए फ़िल्टर प्रेडिकेट। |

### वापसी मान

वापस देता है [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) के उदाहरणों की सूची जो प्रदान किए गए प्रेडिकेट को संतुष्ट करती है।

### टिप्पणियाँ

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### संबंधित देखें

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
