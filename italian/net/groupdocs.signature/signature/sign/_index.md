---
title: "Firma"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Firma il documento con SignOptionsgroupdocs.signature.options/signoptions e salva il risultato in uno stream."
type: docs
weight: 160
url: /it/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Firma il documento con [`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato in uno stream.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Lo stream del documento di output. |
| signOptions | SignOptions | Le opzioni della firma. |

### Valore di ritorno

Restituisce un'istanza di [`SignResult`](../../../groupdocs.signature.domain/signresult) con l'elenco delle firme appena create.

### Osservazioni

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Vedi anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Firma il documento con [`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato in uno stream con i [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) predefiniti.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Lo stream del documento di output. |
| signOptions | SignOptions | Le opzioni della firma. |
| saveOptions | SaveOptions | Le opzioni di salvataggio. |

### Valore di ritorno

Restituisce un'istanza di [`SignResult`](../../../groupdocs.signature.domain/signresult) con l'elenco delle firme appena create.

### Osservazioni

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Vedi anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Firma il documento con una collezione di [`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato in uno stream.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Lo stream del documento di output. |
| signOptionsList | List`1 | Elenco delle opzioni di firma. |

### Valore di ritorno

Restituisce un'istanza di [`SignResult`](../../../groupdocs.signature.domain/signresult) con l'elenco delle firme appena create.

### Osservazioni

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Vedi anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Firma il documento con una raccolta di [`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato in uno stream con i [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) predefiniti.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Lo stream del documento di output. |
| signOptionsList | List`1 | Elenco delle opzioni di firma. |
| saveOptions | SaveOptions | Le opzioni di salvataggio. |

### Valore di ritorno

Restituisce un'istanza di [`SignResult`](../../../groupdocs.signature.domain/signresult) con l'elenco delle firme appena create.

### Osservazioni

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Vedi anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Firma il documento con [`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso file specificato.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso file di output. |
| signOptions | SignOptions | Le opzioni della firma. |

### Valore di ritorno

Restituisce un'istanza di [`SignResult`](../../../groupdocs.signature.domain/signresult) con l'elenco delle firme appena create.

### Osservazioni

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Vedi anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Firma il documento con [`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso file specificato con i [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) predefiniti.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso file di output. |
| signOptions | SignOptions | Le opzioni della firma. |
| saveOptions | SaveOptions | Le opzioni di salvataggio. |

### Valore di ritorno

Restituisce un'istanza di [`SignResult`](../../../groupdocs.signature.domain/signresult) con l'elenco delle firme appena create.

### Osservazioni

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Vedi anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Firma il documento con una raccolta di [`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso file specificato.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso file di output. |
| signOptionsList | List`1 | Elenco delle opzioni di firma. |

### Valore di ritorno

Restituisce un'istanza di [`SignResult`](../../../groupdocs.signature.domain/signresult) con l'elenco delle firme appena create.

### Osservazioni

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Vedi anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Firma il documento con una raccolta di [`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso file specificato con i [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) predefiniti.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso file di output. |
| signOptionsList | List`1 | Elenco delle opzioni di firma. |
| saveOptions | SaveOptions | Le opzioni di salvataggio. |

### Valore di ritorno

Restituisce un'istanza di [`SignResult`](../../../groupdocs.signature.domain/signresult) con l'elenco delle firme appena create.

### Osservazioni

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Vedi anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
