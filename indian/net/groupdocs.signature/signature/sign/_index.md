---
title: Sign
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: दस्तवेज़ पर हस्तक्षर करत हैSignOptionsgroupdocs.signature.options/signoptions और परणम क स्ट्रम में सहेजत है
type: docs
weight: 160
url: /hi/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../../groupdocs.signature.options/signoptions) और परिणाम को स्ट्रीम में सहेजता है।

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptions | SignOptions | हस्ताक्षर विकल्प। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SignResult`](../../../groupdocs.signature.domain/signresult) नव निर्मित हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकार](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: में दस्तावेजों पर ई-हस्ताक्षर करने के तरीके के बारे में अधिक जानकारी[GroupDocs.Signature का उपयोग करके दस्तावेज़ों पर हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/Signing)

### यह सभी देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../../groupdocs.signature.options/signoptions)और परिणाम को पूर्वनिर्धारित स्ट्रीम में सहेजता है[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptions | SignOptions | हस्ताक्षर विकल्प। |
| saveOptions | SaveOptions | सेव विकल्प। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SignResult`](../../../groupdocs.signature.domain/signresult) नव निर्मित हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकार](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: में दस्तावेजों पर ई-हस्ताक्षर करने के तरीके के बारे में अधिक जानकारी[GroupDocs.Signature का उपयोग करके दस्तावेज़ों पर हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/Signing)
* इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों को सहेजने और सहेजने की प्रक्रिया को अनुकूलित करने के बारे में अधिक जानकारी: [GroupDocs.Signature का उपयोग करके सहेजने पर इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों को कैसे अनुकूलित करें](https://docs.groupdocs.com/display/signaturenet/Saving)

### यह सभी देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../../groupdocs.signature.options/signoptions) और परिणाम को स्ट्रीम में सहेजता है।

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptionsList | List`1 | हस्ताक्षर विकल्पों की सूची। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SignResult`](../../../groupdocs.signature.domain/signresult) नव निर्मित हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकार](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: में दस्तावेजों पर ई-हस्ताक्षर करने के तरीके के बारे में अधिक जानकारी[GroupDocs.Signature का उपयोग करके दस्तावेज़ों पर हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/Signing)

### यह सभी देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../../groupdocs.signature.options/signoptions)और परिणाम को पूर्वनिर्धारित स्ट्रीम में सहेजता है[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptionsList | List`1 | हस्ताक्षर विकल्पों की सूची। |
| saveOptions | SaveOptions | सेव विकल्प। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SignResult`](../../../groupdocs.signature.domain/signresult) नव निर्मित हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकार](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: में दस्तावेजों पर ई-हस्ताक्षर करने के तरीके के बारे में अधिक जानकारी[GroupDocs.Signature का उपयोग करके दस्तावेज़ों पर हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/Signing)
* इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों को सहेजने और सहेजने की प्रक्रिया को अनुकूलित करने के बारे में अधिक जानकारी: [GroupDocs.Signature का उपयोग करके सहेजने पर इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों को कैसे अनुकूलित करें](https://docs.groupdocs.com/display/signaturenet/Saving)

### यह सभी देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../../groupdocs.signature.options/signoptions) और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | आउटपुट फ़ाइल पथ। |
| signOptions | SignOptions | हस्ताक्षर विकल्प। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SignResult`](../../../groupdocs.signature.domain/signresult) नव निर्मित हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकार](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: में दस्तावेजों पर ई-हस्ताक्षर करने के तरीके के बारे में अधिक जानकारी[GroupDocs.Signature का उपयोग करके दस्तावेज़ों पर हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/Signing)

### यह सभी देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../../groupdocs.signature.options/signoptions) और परिणाम को पूर्वनिर्धारित के साथ निर्दिष्ट फ़ाइल पथ में सहेजता है[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | आउटपुट फ़ाइल पथ। |
| signOptions | SignOptions | हस्ताक्षर विकल्प। |
| saveOptions | SaveOptions | सेव विकल्प। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SignResult`](../../../groupdocs.signature.domain/signresult) नव निर्मित हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकार](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: में दस्तावेजों पर ई-हस्ताक्षर करने के तरीके के बारे में अधिक जानकारी[GroupDocs.Signature का उपयोग करके दस्तावेज़ों पर हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/Signing)
* इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों को सहेजने और सहेजने की प्रक्रिया को अनुकूलित करने के बारे में अधिक जानकारी: [GroupDocs.Signature का उपयोग करके सहेजने पर इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों को कैसे अनुकूलित करें](https://docs.groupdocs.com/display/signaturenet/Saving)

### यह सभी देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../../groupdocs.signature.options/signoptions) और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | आउटपुट फ़ाइल पथ। |
| signOptionsList | List`1 | हस्ताक्षर विकल्पों की सूची। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SignResult`](../../../groupdocs.signature.domain/signresult) नव निर्मित हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकार](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: में दस्तावेजों पर ई-हस्ताक्षर करने के तरीके के बारे में अधिक जानकारी[GroupDocs.Signature का उपयोग करके दस्तावेज़ों पर हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/Signing)

### यह सभी देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

संग्रह के साथ दस्तावेज़ पर हस्ताक्षर करता है[`SignOptions`](../../../groupdocs.signature.options/signoptions) और परिणाम को पूर्वनिर्धारित के साथ निर्दिष्ट फ़ाइल पथ में सहेजता है[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | आउटपुट फ़ाइल पथ। |
| signOptionsList | List`1 | हस्ताक्षर विकल्पों की सूची। |
| saveOptions | SaveOptions | सेव विकल्प। |

### प्रतिलाभ की मात्रा

का उदाहरण देता है[`SignResult`](../../../groupdocs.signature.domain/signresult) नव निर्मित हस्ताक्षरों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित इलेक्ट्रॉनिक हस्ताक्षर प्रकार](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: में दस्तावेजों पर ई-हस्ताक्षर करने के तरीके के बारे में अधिक जानकारी[GroupDocs.Signature का उपयोग करके दस्तावेज़ों पर हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/Signing)
* इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों को सहेजने और सहेजने की प्रक्रिया को अनुकूलित करने के बारे में अधिक जानकारी: [GroupDocs.Signature का उपयोग करके सहेजने पर इलेक्ट्रॉनिक रूप से हस्ताक्षरित दस्तावेज़ों को कैसे अनुकूलित करें](https://docs.groupdocs.com/display/signaturenet/Saving)

### यह सभी देखें

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
