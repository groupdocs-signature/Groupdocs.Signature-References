---
title: "Metodo sign"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Firma il documento con SignOptions e salva il risultato in un flusso."
type: docs
url: /it/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Firma il documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato in uno stream.

```python
def sign(self, document, sign_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso del documento di output. |
| sign_options | `SignOptions` | Le opzioni di firma. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Osservazioni:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#document-sign_options-save_options}

Firma un documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato in uno stream utilizzando i [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefiniti.

Maggiori informazioni
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso del documento di output. |
| sign_options | `SignOptions` | Le opzioni di firma. |
| save_options | `SaveOptions` | Le opzioni di salvataggio. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Firma il documento con una raccolta di [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato in uno stream.

Maggiori informazioni

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso del documento di output. |
| sign_options_list | `List[SignOptions]` | L'elenco delle opzioni di firma. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Firma il documento con una raccolta di [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato in uno stream utilizzando i [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefiniti.

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| document | `io.RawIOBase` | Il flusso del documento di output. |
| sign_options_list | `List[SignOptions]` | L'elenco delle opzioni di firma. |
| save_options | `SaveOptions` | Le opzioni di salvataggio. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Osservazioni:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Firma e salva il risultato in un nuovo file; l'origine rimane invariata
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Firma il documento con SignOptions e salva il risultato nel percorso file specificato.

Maggiori informazioni

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file di output. |
| sign_options | `SignOptions` | Le opzioni di firma. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options-save_options}

Firma il documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato nel percorso file specificato utilizzando i [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefiniti.

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file di output. |
| sign_options | `SignOptions` | Le opzioni di firma. |
| save_options | `SaveOptions` | Le opzioni di salvataggio. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Apri il documento; il with-block rilascia il file al termine
    with Signature("sample.pdf") as signature:
        # Una firma di testo a 100 pixel dal bordo sinistro e superiore della prima pagina
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Firma e salva il risultato in un nuovo file; l'origine rimane invariata
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Firma il documento con una raccolta di [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato nel percorso file specificato.

Per saperne di più:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file di output. |
| sign_options_list | `List[SignOptions]` | L'elenco delle opzioni di firma. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    options.left = 100
    options.top = 100
    result = signature.sign("signed_sample.pdf", options)
    print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list-save_options}

Firma il documento con una raccolta di [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) e salva il risultato nel percorso file specificato utilizzando i [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefiniti.

Per saperne di più:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il percorso del file di output. |
| sign_options_list | `List[SignOptions]` | L'elenco delle opzioni di firma. |
| save_options | `SaveOptions` | Le opzioni di salvataggio. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Vedi anche
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
