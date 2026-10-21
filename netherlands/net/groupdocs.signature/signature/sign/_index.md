---
title: "Sign"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "Ondertekent document met SignOptionsgroupdocs.signature.options/signoptions en slaat het resultaat op in een stream."
type: docs
weight: 160
url: /nl/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Ondertekent document met [`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De uitvoer‑document‑stream. |
| signOptions | SignOptions | De handtekeningopties. |

### Retourwaarde

Retourneert een instantie van [`SignResult`](../../../groupdocs.signature.domain/signresult) met een lijst van nieuw gemaakte handtekeningen.

### Opmerkingen

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Ondertekent document met [`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream met vooraf gedefinieerde [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De uitvoer‑document‑stream. |
| signOptions | SignOptions | De handtekeningopties. |
| saveOptions | SaveOptions | De opslag‑opties. |

### Retourwaarde

Retourneert een instantie van [`SignResult`](../../../groupdocs.signature.domain/signresult) met een lijst van nieuw gemaakte handtekeningen.

### Opmerkingen

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Ondertekent document met een collectie van [`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De uitvoer‑document‑stream. |
| signOptionsList | List`1 | De lijst met handtekeningopties. |

### Retourwaarde

Retourneert een instantie van [`SignResult`](../../../groupdocs.signature.domain/signresult) met een lijst van nieuw gemaakte handtekeningen.

### Opmerkingen

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Ondertekent document met een collectie van [`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op naar een stream met vooraf gedefinieerde [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De uitvoer‑document‑stream. |
| signOptionsList | List`1 | De lijst met handtekeningopties. |
| saveOptions | SaveOptions | De opslag‑opties. |

### Retourwaarde

Retourneert een instantie van [`SignResult`](../../../groupdocs.signature.domain/signresult) met een lijst van nieuw gemaakte handtekeningen.

### Opmerkingen

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Ondertekent document met [`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op naar het opgegeven bestandspad.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het uitvoerbestandspad. |
| signOptions | SignOptions | De handtekeningopties. |

### Retourwaarde

Retourneert een instantie van [`SignResult`](../../../groupdocs.signature.domain/signresult) met een lijst van nieuw gemaakte handtekeningen.

### Opmerkingen

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Ondertekent document met [`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het uitvoerbestandspad. |
| signOptions | SignOptions | De handtekeningopties. |
| saveOptions | SaveOptions | De opslag‑opties. |

### Retourwaarde

Retourneert een instantie van [`SignResult`](../../../groupdocs.signature.domain/signresult) met een lijst van nieuw gemaakte handtekeningen.

### Opmerkingen

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Ondertekent document met een collectie van [`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op naar het opgegeven bestandspad.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het uitvoerbestandspad. |
| signOptionsList | List`1 | De lijst met handtekeningopties. |

### Retourwaarde

Retourneert een instantie van [`SignResult`](../../../groupdocs.signature.domain/signresult) met een lijst van nieuw gemaakte handtekeningen.

### Opmerkingen

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Ondertekent document met een collectie van [`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het uitvoerbestandspad. |
| signOptionsList | List`1 | De lijst met handtekeningopties. |
| saveOptions | SaveOptions | De opslag‑opties. |

### Retourwaarde

Retourneert een instantie van [`SignResult`](../../../groupdocs.signature.domain/signresult) met een lijst van nieuw gemaakte handtekeningen.

### Opmerkingen

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
