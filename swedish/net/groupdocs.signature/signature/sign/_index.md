---
title: Sign
second_title: GroupDocs.Signature för .NET API-referens
description: Signerar dokument medSignOptionsgroupdocs.signature.options/signoptions och sparar resultatet i en stream.
type: docs
weight: 160
url: /sv/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Signerar dokument med[`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet i en stream.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Utdatadokumentströmmen. |
| signOptions | SignOptions | Signaturalternativen. |

### Returvärde

Returnerar instans av[`SignResult`](../../../groupdocs.signature.domain/signresult) med lista över nyskapade signaturer.

### Anmärkningar

**Läs mer**

* Mer om elektroniska signaturtyper som stöds av GroupDocs.Signatur: [Elektroniska signaturtyper som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Mer om hur eSign-dokument i C#: [Hur man e-signerar dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Signerar dokument med[`SignOptions`](../../../groupdocs.signature.options/signoptions)och sparar resultatet till en ström med fördefinierade[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Utdatadokumentströmmen. |
| signOptions | SignOptions | Signaturalternativen. |
| saveOptions | SaveOptions | Spara alternativen. |

### Returvärde

Returnerar instans av[`SignResult`](../../../groupdocs.signature.domain/signresult) med lista över nyskapade signaturer.

### Anmärkningar

**Läs mer**

* Mer om elektroniska signaturtyper som stöds av GroupDocs.Signatur: [Elektroniska signaturtyper som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Mer om hur eSign-dokument i C#: [Hur man e-signerar dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Mer om hur du sparar elektroniskt signerade dokument och anpassar sparprocessen: [Hur man anpassar elektroniskt signerade dokument vid spara med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Signerar dokument med samling av[`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet i en stream.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Utdatadokumentströmmen. |
| signOptionsList | List`1 | Listan över signaturalternativ. |

### Returvärde

Returnerar instans av[`SignResult`](../../../groupdocs.signature.domain/signresult) med lista över nyskapade signaturer.

### Anmärkningar

**Läs mer**

* Mer om elektroniska signaturtyper som stöds av GroupDocs.Signatur: [Elektroniska signaturtyper som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Mer om hur eSign-dokument i C#: [Hur man e-signerar dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Signerar dokument med samling av[`SignOptions`](../../../groupdocs.signature.options/signoptions)och sparar resultatet till en ström med fördefinierade[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Utdatadokumentströmmen. |
| signOptionsList | List`1 | Listan över signaturalternativ. |
| saveOptions | SaveOptions | Spara alternativen. |

### Returvärde

Returnerar instans av[`SignResult`](../../../groupdocs.signature.domain/signresult) med lista över nyskapade signaturer.

### Anmärkningar

**Läs mer**

* Mer om elektroniska signaturtyper som stöds av GroupDocs.Signatur: [Elektroniska signaturtyper som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Mer om hur eSign-dokument i C#: [Hur man e-signerar dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Mer om hur du sparar elektroniskt signerade dokument och anpassar sparprocessen: [Hur man anpassar elektroniskt signerade dokument vid spara med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Signerar dokument med[`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Utdatafilens sökväg. |
| signOptions | SignOptions | Signaturalternativen. |

### Returvärde

Returnerar instans av[`SignResult`](../../../groupdocs.signature.domain/signresult) med lista över nyskapade signaturer.

### Anmärkningar

**Läs mer**

* Mer om elektroniska signaturtyper som stöds av GroupDocs.Signatur: [Elektroniska signaturtyper som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Mer om hur eSign-dokument i C#: [Hur man e-signerar dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Signerar dokument med[`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg med fördefinierad[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Utdatafilens sökväg. |
| signOptions | SignOptions | Signaturalternativen. |
| saveOptions | SaveOptions | Spara alternativen. |

### Returvärde

Returnerar instans av[`SignResult`](../../../groupdocs.signature.domain/signresult) med lista över nyskapade signaturer.

### Anmärkningar

**Läs mer**

* Mer om elektroniska signaturtyper som stöds av GroupDocs.Signatur: [Elektroniska signaturtyper som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Mer om hur eSign-dokument i C#: [Hur man e-signerar dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Mer om hur du sparar elektroniskt signerade dokument och anpassar sparprocessen: [Hur man anpassar elektroniskt signerade dokument vid spara med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Signerar dokument med samling av[`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Utdatafilens sökväg. |
| signOptionsList | List`1 | Listan över signaturalternativ. |

### Returvärde

Returnerar instans av[`SignResult`](../../../groupdocs.signature.domain/signresult) med lista över nyskapade signaturer.

### Anmärkningar

**Läs mer**

* Mer om elektroniska signaturtyper som stöds av GroupDocs.Signatur: [Elektroniska signaturtyper som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Mer om hur eSign-dokument i C#: [Hur man e-signerar dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Signerar dokument med samling av[`SignOptions`](../../../groupdocs.signature.options/signoptions) och sparar resultatet till angiven filsökväg med fördefinierad[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Utdatafilens sökväg. |
| signOptionsList | List`1 | Listan över signaturalternativ. |
| saveOptions | SaveOptions | Spara alternativen. |

### Returvärde

Returnerar instans av[`SignResult`](../../../groupdocs.signature.domain/signresult) med lista över nyskapade signaturer.

### Anmärkningar

**Läs mer**

* Mer om elektroniska signaturtyper som stöds av GroupDocs.Signatur: [Elektroniska signaturtyper som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Mer om hur eSign-dokument i C#: [Hur man e-signerar dokument med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Mer om hur du sparar elektroniskt signerade dokument och anpassar sparprocessen: [Hur man anpassar elektroniskt signerade dokument vid spara med GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Se även

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namnutrymme [GroupDocs.Signature](../../signature)
* hopsättning [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
