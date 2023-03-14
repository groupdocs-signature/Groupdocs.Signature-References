---
title: Delete
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: परत हस्तक्षर हटत हैBaseSignaturegroupdocs.signature.domain/basesignature दस्तवेज़ से.
type: docs
weight: 110
url: /hi/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

पारित हस्ताक्षर हटाता है[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) दस्तावेज़ से.

```csharp
public bool Delete(BaseSignature signature)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signature | BaseSignature | दस्तावेज़ से हटाई जाने वाली हस्ताक्षर वस्तु। |

### प्रतिलाभ की मात्रा

ऑपरेशन सफल होने पर सच हो जाता है।

### टिप्पणियों

**और अधिक जानें**

* सी#: में दस्तावेज़ से इलेक्ट्रॉनिक हस्ताक्षर को हटाने के तरीके के बारे में अधिक[GroupDocs.Signature के साथ दस्तावेज़ से ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* दस्तावेज़ eSignatures को हटाने के उन्नत उपयोग के मामले: [सी # में दस्तावेज़ से विभिन्न प्रकार के ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Deleting)

### यह सभी देखें

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

उत्तीर्ण हस्ताक्षरों की सूची हटाता है[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) दस्तावेज़ से.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatures | List`1 | दस्तावेज़ से हटाने के लिए हस्ताक्षरों की सूची। |

### प्रतिलाभ की मात्रा

डिलीट रिज़ल्ट लौटाता है[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) सफलतापूर्वक हटाए गए हस्ताक्षरों और असफल लोगों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* सी#: में दस्तावेज़ से इलेक्ट्रॉनिक हस्ताक्षर को हटाने के तरीके के बारे में अधिक[GroupDocs.Signature के साथ दस्तावेज़ से ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* दस्तावेज़ eSignatures को हटाने के उन्नत उपयोग के मामले: [सी # में दस्तावेज़ से विभिन्न प्रकार के ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Deleting)

### यह सभी देखें

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

निश्चित प्रकार के हस्ताक्षर हटाता है[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) दस्तावेज़ से. केवल हस्ताक्षर जो साइन विधि द्वारा जोड़े गए थे और हस्ताक्षर के रूप में चिह्नित किए गए थे[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) हटा दिया जाएगा। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: पाठ, छवि, डिजिटल, बारकोड, क्यूआर-कोड

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureType | SignatureType | दस्तावेज़ से हटाए जाने वाले हस्ताक्षर के प्रकार। |

### प्रतिलाभ की मात्रा

डिलीट रिज़ल्ट लौटाता है[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) सफलतापूर्वक हटाए गए हस्ताक्षरों और असफल लोगों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* सी#: में दस्तावेज़ से इलेक्ट्रॉनिक हस्ताक्षर को हटाने के तरीके के बारे में अधिक[GroupDocs.Signature के साथ दस्तावेज़ से विशिष्ट प्रकार के ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* दस्तावेज़ eSignatures को हटाने के उन्नत उपयोग के मामले: [सी # में दस्तावेज़ से विभिन्न प्रकार के ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Deleting)

### यह सभी देखें

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

विशिष्ट प्रकार की सूची के हस्ताक्षर हटाता है[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) दस्तावेज़ से. केवल हस्ताक्षर जो साइन विधि द्वारा जोड़े गए थे और हस्ताक्षर के रूप में चिह्नित किए गए थे[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) हटा दिया जाएगा। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: पाठ, छवि, डिजिटल, बारकोड, क्यूआर-कोड

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureTypes | List`1 | दस्तावेज़ से निकाले जाने वाले हस्ताक्षर प्रकारों की सूची। |

### प्रतिलाभ की मात्रा

डिलीट रिज़ल्ट लौटाता है[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) सफलतापूर्वक हटाए गए हस्ताक्षरों और असफल लोगों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* सी#: में दस्तावेज़ से इलेक्ट्रॉनिक हस्ताक्षर को हटाने के तरीके के बारे में अधिक[GroupDocs.Signature के साथ दस्तावेज़ से विशिष्ट प्रकार के ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* दस्तावेज़ eSignatures को हटाने के उन्नत उपयोग के मामले: [सी # में दस्तावेज़ से विभिन्न प्रकार के ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Deleting)

### यह सभी देखें

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

दस्तावेज़ से अपने विशिष्ट हस्ताक्षर आईडी द्वारा हस्ताक्षर हटाता है।

```csharp
public bool Delete(string signatureId)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureId | String | दस्तावेज़ से हटाए जाने वाले हस्ताक्षर की आईडी। |

### प्रतिलाभ की मात्रा

ऑपरेशन सफल होने पर सच हो जाता है।

### टिप्पणियों

**और अधिक जानें**

* सी#: में दस्तावेज़ से इलेक्ट्रॉनिक हस्ताक्षर को हटाने के तरीके के बारे में अधिक[GroupDocs.Signature के साथ दस्तावेज़ से ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* दस्तावेज़ eSignatures को हटाने के उन्नत उपयोग के मामले: [सी # में दस्तावेज़ से विभिन्न प्रकार के ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Deleting)

### यह सभी देखें

* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

उत्तीर्ण हस्ताक्षरों की सूची हटाता है[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) दस्तावेज़ से.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureIds | List`1 | दस्तावेज़ से हटाए जाने वाले हस्ताक्षरों के पहचानकर्ताओं की सूची। |

### प्रतिलाभ की मात्रा

डिलीट रिज़ल्ट लौटाता है[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) सफलतापूर्वक हटाए गए हस्ताक्षरों और असफल लोगों की सूची के साथ।

### टिप्पणियों

**और अधिक जानें**

* सी#: में दस्तावेज़ से इलेक्ट्रॉनिक हस्ताक्षर को हटाने के तरीके के बारे में अधिक[GroupDocs.Signature के साथ दस्तावेज़ से ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* दस्तावेज़ eSignatures को हटाने के उन्नत उपयोग के मामले: [सी # में दस्तावेज़ से विभिन्न प्रकार के ई-हस्ताक्षर कैसे हटाएं](https://docs.groupdocs.com/display/signaturenet/Deleting)

### यह सभी देखें

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* नाम स्थान [GroupDocs.Signature](../../signature)
* सभा [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
