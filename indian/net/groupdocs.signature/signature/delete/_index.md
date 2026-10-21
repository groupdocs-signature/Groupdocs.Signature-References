---
title: "Delete"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "दस्तावेज़ से पास किए गए हस्ताक्षर BaseSignaturegroupdocs.signature.domain/basesignature को हटाता है।"
type: docs
weight: 110
url: /hi/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

दस्तावेज़ से पास किए गए हस्ताक्षर [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) को हटाता है।

```csharp
public bool Delete(BaseSignature signature)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| हस्ताक्षर | BaseSignature | दस्तावेज़ से हटाए जाने वाला हस्ताक्षर ऑब्जेक्ट। |

### वापसी मान

यदि ऑपरेशन सफल रहा तो true लौटाता है।

### टिप्पणियाँ

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### संबंधित देखें

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) को हटाता है।

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| हस्ताक्षर | List`1 | दस्तावेज़ से हटाने के लिए हस्ताक्षरों की सूची। |

### वापसी मान

वापस देता है DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) जिसमें सफलतापूर्वक हटाए गए हस्ताक्षरों और विफल हुए हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### संबंधित देखें

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

दस्तावेज़ से निश्चित प्रकार के हस्ताक्षर [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) को हटाता है। केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए हैं और हस्ताक्षर [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) के रूप में चिह्नित हैं, हटाए जाएंगे। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signatureType | SignatureType | दस्तावेज़ से हटाए जाने वाले हस्ताक्षरों का प्रकार। |

### वापसी मान

वापस देता है DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) जिसमें सफलतापूर्वक हटाए गए हस्ताक्षरों और विफल हुए हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### संबंधित देखें

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

दस्तावेज़ से निश्चित प्रकारों की सूची के हस्ताक्षर [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) को हटाता है। केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए हैं और हस्ताक्षर [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) के रूप में चिह्नित हैं, हटाए जाएंगे। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signatureTypes | List`1 | दस्तावेज़ से हटाए जाने वाले हस्ताक्षर प्रकारों की सूची। |

### वापसी मान

वापस देता है DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) जिसमें सफलतापूर्वक हटाए गए हस्ताक्षरों और विफल हुए हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### संबंधित देखें

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

दस्तावेज़ से उसके विशिष्ट हस्ताक्षर Id द्वारा हस्ताक्षर को हटाता है।

```csharp
public bool Delete(string signatureId)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signatureId | String | दस्तावेज़ से हटाए जाने वाले हस्ताक्षर की Id। |

### वापसी मान

यदि ऑपरेशन सफल रहा तो true लौटाता है।

### टिप्पणियाँ

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### संबंधित देखें

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) को हटाता है।

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| signatureIds | List`1 | दस्तावेज़ से हटाए जाने वाले हस्ताक्षरों के पहचानकर्ताओं की सूची। |

### वापसी मान

वापस देता है DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) जिसमें सफलतापूर्वक हटाए गए हस्ताक्षरों और विफल हुए हस्ताक्षरों की सूची होती है।

### टिप्पणियाँ

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### संबंधित देखें

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
