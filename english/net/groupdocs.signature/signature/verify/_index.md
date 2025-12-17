---
title: Verify
second_title: GroupDocs.Signature for .NET API Reference
description: Verifies the document signatures with given VerifyOptions data.
type: docs
weight: 180
url: /net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Verifies the document signatures with given VerifyOptions data.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| verifyOptions | VerifyOptions | The signature verification options. |

### Return Value

Returns instance of [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### Remarks

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### See Also

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Verifies the document signatures using the provided verification options and filters the results based on the specified predicate. This method first searches for signatures matching the verification options, filters them using the predicate, and then verifies only those filtered signatures.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| verifyOptions | VerifyOptions | The signature verification options. |
| predicate | Func`2 | The filter predicate to determine which signatures should be verified. |

### Return Value

Returns a list of [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) instances that satisfy the provided predicate.

### Remarks

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### See Also

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Verifies the document signatures with list of VerifyOptions data.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Parameter | Type | Description |
| --- | --- | --- |
| verifyOptionsList | List`1 | The signature verification options collection. Instance of VerifyOptionsCollection. |

### Return Value

Returns instance of [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### Remarks

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### See Also

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Verifies the document signatures using all available verification options and filters the results based on the specified predicate. This method first searches for signatures matching the verification options, filters them using the predicate, and then verifies only those filtered signatures.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| verifyOptionsList | List`1 | The signature verification options collection. Instance of VerifyOptionsCollection. |
| predicate | Func`2 | The filter predicate to determine which signatures should be verified. |

### Return Value

Returns a list of [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) instances that satisfy the provided predicate.

### Remarks

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### See Also

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
