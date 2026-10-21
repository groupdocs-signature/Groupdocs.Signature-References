---
title: "Sign"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "SignOptionsgroupdocs.signature.options/signoptions के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को स्ट्रीम में सहेजता है।"
type: docs
weight: 160
url: /hi/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को स्ट्रीम में सहेजता है।

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| document | Stream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptions | SignOptions | हस्ताक्षर विकल्प। |

### वापसी मान

[`SignResult`](../../../groupdocs.signature.domain/signresult) का उदाहरण लौटाता है जिसमें नई बनाई गई हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### संबंधित देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) के साथ दस्तावेज़ पर हस्ताक्षर करता है और पूर्वनिर्धारित [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) के साथ परिणाम को स्ट्रीम में सहेजता है।

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| document | Stream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptions | SignOptions | हस्ताक्षर विकल्प। |
| saveOptions | SaveOptions | सहेजने के विकल्प। |

### वापसी मान

[`SignResult`](../../../groupdocs.signature.domain/signresult) का उदाहरण लौटाता है जिसमें नई बनाई गई हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### संबंधित देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) के संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को स्ट्रीम में सहेजता है।

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| document | Stream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptionsList | List`1 | हस्ताक्षर विकल्पों की सूची। |

### वापसी मान

[`SignResult`](../../../groupdocs.signature.domain/signresult) का उदाहरण लौटाता है जिसमें नई बनाई गई हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### संबंधित देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

दस्तावेज़ को संग्रह के साथ [`SignOptions`](../../../groupdocs.signature.options/signoptions) का उपयोग करके साइन करता है और परिणाम को पूर्वनिर्धारित [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) के साथ एक स्ट्रीम में सहेजता है।

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| document | Stream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptionsList | List`1 | हस्ताक्षर विकल्पों की सूची। |
| saveOptions | SaveOptions | सहेजने के विकल्प। |

### वापसी मान

[`SignResult`](../../../groupdocs.signature.domain/signresult) का उदाहरण लौटाता है जिसमें नई बनाई गई हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### संबंधित देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

दस्तावेज़ को [`SignOptions`](../../../groupdocs.signature.options/signoptions) का उपयोग करके साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है।

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | आउटपुट फ़ाइल पथ। |
| signOptions | SignOptions | हस्ताक्षर विकल्प। |

### वापसी मान

[`SignResult`](../../../groupdocs.signature.domain/signresult) का उदाहरण लौटाता है जिसमें नई बनाई गई हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### संबंधित देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

दस्तावेज़ को [`SignOptions`](../../../groupdocs.signature.options/signoptions) का उपयोग करके साइन करता है और परिणाम को पूर्वनिर्धारित [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) के साथ निर्दिष्ट फ़ाइल पथ पर सहेजता है।

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | आउटपुट फ़ाइल पथ। |
| signOptions | SignOptions | हस्ताक्षर विकल्प। |
| saveOptions | SaveOptions | सहेजने के विकल्प। |

### वापसी मान

[`SignResult`](../../../groupdocs.signature.domain/signresult) का उदाहरण लौटाता है जिसमें नई बनाई गई हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### संबंधित देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

दस्तावेज़ को संग्रह के साथ [`SignOptions`](../../../groupdocs.signature.options/signoptions) का उपयोग करके साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है।

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | आउटपुट फ़ाइल पथ। |
| signOptionsList | List`1 | हस्ताक्षर विकल्पों की सूची। |

### वापसी मान

[`SignResult`](../../../groupdocs.signature.domain/signresult) का उदाहरण लौटाता है जिसमें नई बनाई गई हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### संबंधित देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

दस्तावेज़ को संग्रह के साथ [`SignOptions`](../../../groupdocs.signature.options/signoptions) का उपयोग करके साइन करता है और परिणाम को पूर्वनिर्धारित [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) के साथ निर्दिष्ट फ़ाइल पथ पर सहेजता है।

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | आउटपुट फ़ाइल पथ। |
| signOptionsList | List`1 | हस्ताक्षर विकल्पों की सूची। |
| saveOptions | SaveOptions | सहेजने के विकल्प। |

### वापसी मान

[`SignResult`](../../../groupdocs.signature.domain/signresult) का उदाहरण लौटाता है जिसमें नई बनाई गई हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### संबंधित देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
