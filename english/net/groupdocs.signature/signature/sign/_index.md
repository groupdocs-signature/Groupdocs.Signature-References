---
title: Sign
second_title: GroupDocs.Signature for .NET API Reference
description: Signs document with SignOptionsgroupdocs.signature.options/signoptions and saves result to a stream.
type: docs
weight: 160
url: /net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Signs document with [`SignOptions`](../../../groupdocs.signature.options/signoptions) and saves result to a stream.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The output document stream. |
| signOptions | SignOptions | The signature options. |

### Return Value

Returns instance of [`SignResult`](../../../groupdocs.signature.domain/signresult) with list of newly created signatures.

### Remarks

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### See Also

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Signs document with [`SignOptions`](../../../groupdocs.signature.options/signoptions) and saves result to a stream with predefined [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The output document stream. |
| signOptions | SignOptions | The signature options. |
| saveOptions | SaveOptions | The save options. |

### Return Value

Returns instance of [`SignResult`](../../../groupdocs.signature.domain/signresult) with list of newly created signatures.

### Remarks

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### See Also

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Signs document with collection of [`SignOptions`](../../../groupdocs.signature.options/signoptions) and saves result to a stream.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The output document stream. |
| signOptionsList | List`1 | The list of signature options. |

### Return Value

Returns instance of [`SignResult`](../../../groupdocs.signature.domain/signresult) with list of newly created signatures.

### Remarks

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### See Also

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Signs document with collection of [`SignOptions`](../../../groupdocs.signature.options/signoptions) and saves result to a stream with predefined [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The output document stream. |
| signOptionsList | List`1 | The list of signature options. |
| saveOptions | SaveOptions | The save options. |

### Return Value

Returns instance of [`SignResult`](../../../groupdocs.signature.domain/signresult) with list of newly created signatures.

### Remarks

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### See Also

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Signs document with [`SignOptions`](../../../groupdocs.signature.options/signoptions) and saves result to specified file path.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The output file path. |
| signOptions | SignOptions | The signature options. |

### Return Value

Returns instance of [`SignResult`](../../../groupdocs.signature.domain/signresult) with list of newly created signatures.

### Remarks

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### See Also

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Signs document with [`SignOptions`](../../../groupdocs.signature.options/signoptions) and saves result to specified file path with predefined [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The output file path. |
| signOptions | SignOptions | The signature options. |
| saveOptions | SaveOptions | The save options. |

### Return Value

Returns instance of [`SignResult`](../../../groupdocs.signature.domain/signresult) with list of newly created signatures.

### Remarks

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### See Also

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Signs document with collection of [`SignOptions`](../../../groupdocs.signature.options/signoptions) and saves result to specified file path.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The output file path. |
| signOptionsList | List`1 | The list of signature options. |

### Return Value

Returns instance of [`SignResult`](../../../groupdocs.signature.domain/signresult) with list of newly created signatures.

### Remarks

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### See Also

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Signs document with collection of [`SignOptions`](../../../groupdocs.signature.options/signoptions) and saves result to specified file path with predefined [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The output file path. |
| signOptionsList | List`1 | The list of signature options. |
| saveOptions | SaveOptions | The save options. |

### Return Value

Returns instance of [`SignResult`](../../../groupdocs.signature.domain/signresult) with list of newly created signatures.

### Remarks

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### See Also

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
