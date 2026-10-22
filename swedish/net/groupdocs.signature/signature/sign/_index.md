---
title: "Sign"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Signerar dokument med SignOptionsgroupdocs.signature.options/signoptions och sparar resultatet till en ström."
type: docs
weight: 160
url: /sv/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Signerar dokument med [`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Ström för utdata-dokumentet. |
| signOptions | SignOptions | Signaturalternativen. |

### Returvärde

Returnerar en instans av [`SignResult`](../../../groupdocs.signature.domain/signresult) med en lista över nyss skapade signaturer.

### Anmärkningar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Signerar dokument med [`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström med fördefinierade [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Ström för utdata-dokumentet. |
| signOptions | SignOptions | Signaturalternativen. |
| saveOptions | SaveOptions | Sparalternativen. |

### Returvärde

Returnerar en instans av [`SignResult`](../../../groupdocs.signature.domain/signresult) med en lista över nyss skapade signaturer.

### Anmärkningar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Signerar dokument med en samling av [`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Ström för utdata-dokumentet. |
| signOptionsList | List`1 | Listan över signaturalternativ. |

### Returvärde

Returnerar en instans av [`SignResult`](../../../groupdocs.signature.domain/signresult) med en lista över nyss skapade signaturer.

### Anmärkningar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Signerar dokument med en samling av [`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till en ström med fördefinierade [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Ström för utdata-dokumentet. |
| signOptionsList | List`1 | Listan över signaturalternativ. |
| saveOptions | SaveOptions | Sparalternativen. |

### Returvärde

Returnerar en instans av [`SignResult`](../../../groupdocs.signature.domain/signresult) med en lista över nyss skapade signaturer.

### Anmärkningar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Signerar dokument med [`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Utdatafilens sökväg. |
| signOptions | SignOptions | Signaturalternativen. |

### Returvärde

Returnerar en instans av [`SignResult`](../../../groupdocs.signature.domain/signresult) med en lista över nyss skapade signaturer.

### Anmärkningar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Signerar dokument med [`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg med fördefinierade [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Utdatafilens sökväg. |
| signOptions | SignOptions | Signaturalternativen. |
| saveOptions | SaveOptions | Sparalternativen. |

### Returvärde

Returnerar en instans av [`SignResult`](../../../groupdocs.signature.domain/signresult) med en lista över nyss skapade signaturer.

### Anmärkningar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Signerar dokument med en samling av [`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Utdatafilens sökväg. |
| signOptionsList | List`1 | Listan över signaturalternativ. |

### Returvärde

Returnerar en instans av [`SignResult`](../../../groupdocs.signature.domain/signresult) med en lista över nyss skapade signaturer.

### Anmärkningar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Signerar dokument med en samling av [`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg med fördefinierade [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Utdatafilens sökväg. |
| signOptionsList | List`1 | Listan över signaturalternativ. |
| saveOptions | SaveOptions | Sparalternativen. |

### Returvärde

Returnerar en instans av [`SignResult`](../../../groupdocs.signature.domain/signresult) med en lista över nyss skapade signaturer.

### Anmärkningar

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
