---
title: "Verify"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "दिए गए VerifyOptions डेटा के साथ दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है।"
type: docs
weight: 180
url: /hi/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

दिए गए VerifyOptions डेटा के साथ दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है।

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| verifyOptions | VerifyOptions | हस्ताक्षर सत्यापन विकल्प। |

### वापसी मान

[`VerificationResult`](../../../groupdocs.signature.domain/verificationresult) का उदाहरण लौटाता है। प्रॉपर्टी VerificationResult.IsValid सत्यापन प्रक्रिया सफल होने पर true लौटाती है।

### टिप्पणियाँ

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### संबंधित देखें

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

प्रदान किए गए सत्यापन विकल्पों का उपयोग करके दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है। यह विधि पहले सत्यापन विकल्पों से मेल खाने वाले हस्ताक्षरों को खोजती है, उन्हें प्रेडिकेट द्वारा फ़िल्टर करती है, और फिर केवल उन फ़िल्टर किए गए हस्ताक्षरों को सत्यापित करती है।

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| verifyOptions | VerifyOptions | हस्ताक्षर सत्यापन विकल्प। |
| predicate | Func`2 | कौन से हस्ताक्षरों को सत्यापित किया जाना चाहिए, यह निर्धारित करने के लिए फ़िल्टर प्रेडिकेट। |

### वापसी मान

वापस देता है [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) के उदाहरणों की सूची जो प्रदान किए गए प्रेडिकेट को संतुष्ट करती है।

### टिप्पणियाँ

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### संबंधित देखें

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

VerifyOptions डेटा की सूची के साथ दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है।

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| verifyOptionsList | List`1 | हस्ताक्षर सत्यापन विकल्प संग्रह। VerifyOptionsCollection का उदाहरण। |

### वापसी मान

[`VerificationResult`](../../../groupdocs.signature.domain/verificationresult) का उदाहरण लौटाता है। प्रॉपर्टी VerificationResult.IsValid सत्यापन प्रक्रिया सफल होने पर true लौटाती है।

### टिप्पणियाँ

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### संबंधित देखें

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

सभी उपलब्ध सत्यापन विकल्पों का उपयोग करके दस्तावेज़ के हस्ताक्षरों को सत्यापित करता है और निर्दिष्ट प्रेडिकेट के आधार पर परिणामों को फ़िल्टर करता है। यह विधि पहले सत्यापन विकल्पों से मेल खाने वाले हस्ताक्षरों को खोजती है, उन्हें प्रेडिकेट द्वारा फ़िल्टर करती है, और फिर केवल उन फ़िल्टर किए गए हस्ताक्षरों को सत्यापित करती है।

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| verifyOptionsList | List`1 | हस्ताक्षर सत्यापन विकल्प संग्रह। VerifyOptionsCollection का उदाहरण। |
| predicate | Func`2 | कौन से हस्ताक्षरों को सत्यापित किया जाना चाहिए, यह निर्धारित करने के लिए फ़िल्टर प्रेडिकेट। |

### वापसी मान

वापस देता है [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) के उदाहरणों की सूची जो प्रदान किए गए प्रेडिकेट को संतुष्ट करती है।

### टिप्पणियाँ

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### संबंधित देखें

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
