---
title: Sign
second_title: Riferimento API GroupDocs.Signature per .NET
description: Firma il documento conSignOptionsgroupdocs.signature.options/signoptions e salva il risultato in un flusso.
type: docs
weight: 160
url: /it/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Firma il documento con[`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato in un flusso.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso del documento di output. |
| signOptions | SignOptions | Le opzioni di firma. |

### Valore di ritorno

Restituisce l'istanza di[`SignResult`](../../../groupdocs.signature.domain/signresult) con elenco delle firme appena create.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di firma elettronica supportati da GroupDocs.Signature: [Tipi di firme elettroniche supportati da GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Ulteriori informazioni su come eSign documenti in C#: [Come firmare documenti elettronici utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Guarda anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Firma il documento con[`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato in un flusso con predefinito[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso del documento di output. |
| signOptions | SignOptions | Le opzioni di firma. |
| saveOptions | SaveOptions | Le opzioni di salvataggio. |

### Valore di ritorno

Restituisce l'istanza di[`SignResult`](../../../groupdocs.signature.domain/signresult) con elenco delle firme appena create.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di firma elettronica supportati da GroupDocs.Signature: [Tipi di firme elettroniche supportati da GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Ulteriori informazioni su come eSign documenti in C#: [Come firmare documenti elettronici utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Ulteriori informazioni su come salvare documenti firmati elettronicamente e personalizzare il processo di salvataggio: [Come personalizzare i documenti firmati elettronicamente durante il salvataggio utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Guarda anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Segni documento con raccolta di[`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato in un flusso.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso del documento di output. |
| signOptionsList | List`1 | L'elenco delle opzioni di firma. |

### Valore di ritorno

Restituisce l'istanza di[`SignResult`](../../../groupdocs.signature.domain/signresult) con elenco delle firme appena create.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di firma elettronica supportati da GroupDocs.Signature: [Tipi di firme elettroniche supportati da GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Ulteriori informazioni su come eSign documenti in C#: [Come firmare documenti elettronici utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Guarda anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Segni documento con raccolta di[`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato in un flusso con predefinito[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso del documento di output. |
| signOptionsList | List`1 | L'elenco delle opzioni di firma. |
| saveOptions | SaveOptions | Le opzioni di salvataggio. |

### Valore di ritorno

Restituisce l'istanza di[`SignResult`](../../../groupdocs.signature.domain/signresult) con elenco delle firme appena create.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di firma elettronica supportati da GroupDocs.Signature: [Tipi di firme elettroniche supportati da GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Ulteriori informazioni su come eSign documenti in C#: [Come firmare documenti elettronici utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Ulteriori informazioni su come salvare documenti firmati elettronicamente e personalizzare il processo di salvataggio: [Come personalizzare i documenti firmati elettronicamente durante il salvataggio utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Guarda anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Firma il documento con[`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso del file specificato.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file di output. |
| signOptions | SignOptions | Le opzioni di firma. |

### Valore di ritorno

Restituisce l'istanza di[`SignResult`](../../../groupdocs.signature.domain/signresult) con elenco delle firme appena create.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di firma elettronica supportati da GroupDocs.Signature: [Tipi di firme elettroniche supportati da GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Ulteriori informazioni su come eSign documenti in C#: [Come firmare documenti elettronici utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Guarda anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Firma il documento con[`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso del file specificato con predefinito[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file di output. |
| signOptions | SignOptions | Le opzioni di firma. |
| saveOptions | SaveOptions | Le opzioni di salvataggio. |

### Valore di ritorno

Restituisce l'istanza di[`SignResult`](../../../groupdocs.signature.domain/signresult) con elenco delle firme appena create.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di firma elettronica supportati da GroupDocs.Signature: [Tipi di firme elettroniche supportati da GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Ulteriori informazioni su come eSign documenti in C#: [Come firmare documenti elettronici utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Ulteriori informazioni su come salvare documenti firmati elettronicamente e personalizzare il processo di salvataggio: [Come personalizzare i documenti firmati elettronicamente durante il salvataggio utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Guarda anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Segni documento con raccolta di[`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso del file specificato.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file di output. |
| signOptionsList | List`1 | L'elenco delle opzioni di firma. |

### Valore di ritorno

Restituisce l'istanza di[`SignResult`](../../../groupdocs.signature.domain/signresult) con elenco delle firme appena create.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di firma elettronica supportati da GroupDocs.Signature: [Tipi di firme elettroniche supportati da GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Ulteriori informazioni su come eSign documenti in C#: [Come firmare documenti elettronici utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Guarda anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Segni documento con raccolta di[`SignOptions`](../../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso del file specificato con predefinito[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file di output. |
| signOptionsList | List`1 | L'elenco delle opzioni di firma. |
| saveOptions | SaveOptions | Le opzioni di salvataggio. |

### Valore di ritorno

Restituisce l'istanza di[`SignResult`](../../../groupdocs.signature.domain/signresult) con elenco delle firme appena create.

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sui tipi di firma elettronica supportati da GroupDocs.Signature: [Tipi di firme elettroniche supportati da GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Ulteriori informazioni su come eSign documenti in C#: [Come firmare documenti elettronici utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Ulteriori informazioni su come salvare documenti firmati elettronicamente e personalizzare il processo di salvataggio: [Come personalizzare i documenti firmati elettronicamente durante il salvataggio utilizzando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Guarda anche

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
