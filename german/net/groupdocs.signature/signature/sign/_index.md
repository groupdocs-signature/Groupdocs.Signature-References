---
title: "Sign"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Signiert das Dokument mit SignOptionsgroupdocs.signature.options/signoptions und speichert das Ergebnis in einen Stream."
type: docs
weight: 160
url: /de/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Signiert das Dokument mit [`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einen Stream.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Ausgabedokument-Stream. |
| signOptions | SignOptions | Die Signaturoptionen. |

### Rückgabewert

Gibt eine Instanz von [`SignResult`](../../../groupdocs.signature.domain/signresult) mit einer Liste neu erstellter Signaturen zurück.

### Hinweise

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Signiert das Dokument mit [`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Ausgabedokument-Stream. |
| signOptions | SignOptions | Die Signaturoptionen. |
| saveOptions | SaveOptions | Die Speicheroptionen. |

### Rückgabewert

Gibt eine Instanz von [`SignResult`](../../../groupdocs.signature.domain/signresult) mit einer Liste neu erstellter Signaturen zurück.

### Hinweise

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Signiert das Dokument mit einer Sammlung von [`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einen Stream.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Ausgabedokument-Stream. |
| signOptionsList | List`1 | Die Liste der Signaturoptionen. |

### Rückgabewert

Gibt eine Instanz von [`SignResult`](../../../groupdocs.signature.domain/signresult) mit einer Liste neu erstellter Signaturen zurück.

### Hinweise

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Signiert das Dokument mit einer Sammlung von [`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis in einen Stream mit vordefinierten [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Ausgabedokument-Stream. |
| signOptionsList | List`1 | Die Liste der Signaturoptionen. |
| saveOptions | SaveOptions | Die Speicheroptionen. |

### Rückgabewert

Gibt eine Instanz von [`SignResult`](../../../groupdocs.signature.domain/signresult) mit einer Liste neu erstellter Signaturen zurück.

### Hinweise

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Signiert das Dokument mit [`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis im angegebenen Dateipfad.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Ausgabedateipfad. |
| signOptions | SignOptions | Die Signaturoptionen. |

### Rückgabewert

Gibt eine Instanz von [`SignResult`](../../../groupdocs.signature.domain/signresult) mit einer Liste neu erstellter Signaturen zurück.

### Hinweise

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Signiert das Dokument mit [`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis im angegebenen Dateipfad mit vordefinierten [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Ausgabedateipfad. |
| signOptions | SignOptions | Die Signaturoptionen. |
| saveOptions | SaveOptions | Die Speicheroptionen. |

### Rückgabewert

Gibt eine Instanz von [`SignResult`](../../../groupdocs.signature.domain/signresult) mit einer Liste neu erstellter Signaturen zurück.

### Hinweise

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Signiert das Dokument mit einer Sammlung von [`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis im angegebenen Dateipfad.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Ausgabedateipfad. |
| signOptionsList | List`1 | Die Liste der Signaturoptionen. |

### Rückgabewert

Gibt eine Instanz von [`SignResult`](../../../groupdocs.signature.domain/signresult) mit einer Liste neu erstellter Signaturen zurück.

### Hinweise

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Signiert das Dokument mit einer Sammlung von [`SignOptions`](../../../groupdocs.signature.options/signoptions) und speichert das Ergebnis im angegebenen Dateipfad mit vordefinierten [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Ausgabedateipfad. |
| signOptionsList | List`1 | Die Liste der Signaturoptionen. |
| saveOptions | SaveOptions | Die Speicheroptionen. |

### Rückgabewert

Gibt eine Instanz von [`SignResult`](../../../groupdocs.signature.domain/signresult) mit einer Liste neu erstellter Signaturen zurück.

### Hinweise

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Siehe auch

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
