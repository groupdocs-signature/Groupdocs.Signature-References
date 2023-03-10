---
title: Sign
second_title: GroupDocs.Signature voor .NET API-referentie
description: Ondertekent document metSignOptionsgroupdocs.signature.options/signoptions en slaat het resultaat op in een stream.
type: docs
weight: 160
url: /nl/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Ondertekent document met[`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De uitvoerdocumentstroom. |
| signOptions | SignOptions | De ondertekeningsopties. |

### Winstwaarde

Retourneert instantie van[`SignResult`](../../../groupdocs.signature.domain/signresult) met lijst van nieuw aangemaakte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature: [Typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Meer over hoe eSign documenteert in C#: [Documenten elektronisch ondertekenen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Ondertekent document met[`SignOptions`](../../../groupdocs.signature.options/signoptions)en slaat het resultaat op in een stream met vooraf gedefinieerde[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De uitvoerdocumentstroom. |
| signOptions | SignOptions | De ondertekeningsopties. |
| saveOptions | SaveOptions | De bewaaropties. |

### Winstwaarde

Retourneert instantie van[`SignResult`](../../../groupdocs.signature.domain/signresult) met lijst van nieuw aangemaakte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature: [Typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Meer over hoe eSign documenteert in C#: [Documenten elektronisch ondertekenen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Meer over het opslaan van elektronisch ondertekende documenten en het aanpassen van het opslagproces: [Elektronisch ondertekende documenten aanpassen bij het opslaan met behulp van GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Ondertekent document met verzameling van[`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in een stream.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De uitvoerdocumentstroom. |
| signOptionsList | List`1 | De lijst met ondertekeningsopties. |

### Winstwaarde

Retourneert instantie van[`SignResult`](../../../groupdocs.signature.domain/signresult) met lijst van nieuw aangemaakte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature: [Typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Meer over hoe eSign documenteert in C#: [Documenten elektronisch ondertekenen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Ondertekent document met verzameling van[`SignOptions`](../../../groupdocs.signature.options/signoptions)en slaat het resultaat op in een stream met vooraf gedefinieerde[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De uitvoerdocumentstroom. |
| signOptionsList | List`1 | De lijst met ondertekeningsopties. |
| saveOptions | SaveOptions | De bewaaropties. |

### Winstwaarde

Retourneert instantie van[`SignResult`](../../../groupdocs.signature.domain/signresult) met lijst van nieuw aangemaakte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature: [Typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Meer over hoe eSign documenteert in C#: [Documenten elektronisch ondertekenen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Meer over het opslaan van elektronisch ondertekende documenten en het aanpassen van het opslagproces: [Elektronisch ondertekende documenten aanpassen bij het opslaan met behulp van GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Ondertekent document met[`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in het opgegeven bestandspad.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het uitvoerbestandspad. |
| signOptions | SignOptions | De ondertekeningsopties. |

### Winstwaarde

Retourneert instantie van[`SignResult`](../../../groupdocs.signature.domain/signresult) met lijst van nieuw aangemaakte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature: [Typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Meer over hoe eSign documenteert in C#: [Documenten elektronisch ondertekenen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Ondertekent document met[`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in het opgegeven bestandspad met vooraf gedefinieerd[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het uitvoerbestandspad. |
| signOptions | SignOptions | De ondertekeningsopties. |
| saveOptions | SaveOptions | De bewaaropties. |

### Winstwaarde

Retourneert instantie van[`SignResult`](../../../groupdocs.signature.domain/signresult) met lijst van nieuw aangemaakte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature: [Typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Meer over hoe eSign documenteert in C#: [Documenten elektronisch ondertekenen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Meer over het opslaan van elektronisch ondertekende documenten en het aanpassen van het opslagproces: [Elektronisch ondertekende documenten aanpassen bij het opslaan met behulp van GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Ondertekent document met verzameling van[`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in het opgegeven bestandspad.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het uitvoerbestandspad. |
| signOptionsList | List`1 | De lijst met ondertekeningsopties. |

### Winstwaarde

Retourneert instantie van[`SignResult`](../../../groupdocs.signature.domain/signresult) met lijst van nieuw aangemaakte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature: [Typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Meer over hoe eSign documenteert in C#: [Documenten elektronisch ondertekenen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Ondertekent document met verzameling van[`SignOptions`](../../../groupdocs.signature.options/signoptions) en slaat het resultaat op in het opgegeven bestandspad met vooraf gedefinieerd[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het uitvoerbestandspad. |
| signOptionsList | List`1 | De lijst met ondertekeningsopties. |
| saveOptions | SaveOptions | De bewaaropties. |

### Winstwaarde

Retourneert instantie van[`SignResult`](../../../groupdocs.signature.domain/signresult) met lijst van nieuw aangemaakte handtekeningen.

### Opmerkingen

**Kom meer te weten**

* Meer over typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature: [Typen elektronische handtekeningen die worden ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Meer over hoe eSign documenteert in C#: [Documenten elektronisch ondertekenen met GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Meer over het opslaan van elektronisch ondertekende documenten en het aanpassen van het opslagproces: [Elektronisch ondertekende documenten aanpassen bij het opslaan met behulp van GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Zie ook

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* naamruimte [GroupDocs.Signature](../../signature)
* montage [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
