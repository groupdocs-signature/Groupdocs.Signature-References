---
title: "Methode sign"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Signiert ein Dokument mit SignOptions und speichert das Ergebnis in einen Stream."
type: docs
url: /de/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Signiert das Dokument mit [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis in einen Stream.

```python
def sign(self, document, sign_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Ausgabedokument-Stream. |
| sign_options | `SignOptions` | Die Signaturoptionen. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Hinweise:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Beispiel

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

Signiert ein Dokument mit [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis in einen Stream unter Verwendung vordefinierter [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Mehr erfahren
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Ausgabedokument-Stream. |
| sign_options | `SignOptions` | Die Signaturoptionen. |
| save_options | `SaveOptions` | Die Speicheroptionen. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Signiert das Dokument mit einer Sammlung von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis in einen Stream.

Mehr erfahren

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Ausgabedokument-Stream. |
| sign_options_list | `List[SignOptions]` | Die Liste der Signaturoptionen. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Signiert das Dokument mit einer Sammlung von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis in einen Stream unter Verwendung vordefinierter [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document | `io.RawIOBase` | Der Ausgabedokument-Stream. |
| sign_options_list | `List[SignOptions]` | Die Liste der Signaturoptionen. |
| save_options | `SaveOptions` | Die Speicheroptionen. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Hinweise:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signieren Sie und speichern Sie das Ergebnis in einer neuen Datei; die Quelle bleibt unverändert.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Signiert das Dokument mit SignOptions und speichert das Ergebnis im angegebenen Dateipfad.

Mehr erfahren

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Ausgabedateipfad. |
| sign_options | `SignOptions` | Die Signaturoptionen. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Beispiel

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

Signiert das Dokument mit [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis im angegebenen Dateipfad unter Verwendung vordefinierter [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Ausgabedateipfad. |
| sign_options | `SignOptions` | Die Signaturoptionen. |
| save_options | `SaveOptions` | Die Speicheroptionen. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Öffnen Sie das Dokument; der with-Block gibt die Datei frei, wenn er endet.
    with Signature("sample.pdf") as signature:
        # Eine Textsignatur 100 Pixel von den linken und oberen Rändern der ersten Seite entfernt.
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signieren Sie und speichern Sie das Ergebnis in einer neuen Datei; die Quelle bleibt unverändert.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Signiert das Dokument mit einer Sammlung von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis im angegebenen Dateipfad.

Mehr erfahren:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Ausgabedateipfad. |
| sign_options_list | `List[SignOptions]` | Die Liste der Signaturoptionen. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Beispiel

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

Signiert das Dokument mit einer Sammlung von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis im angegebenen Dateipfad unter Verwendung vordefinierter [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Mehr erfahren:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Ausgabedateipfad. |
| sign_options_list | `List[SignOptions]` | Die Liste der Signaturoptionen. |
| save_options | `SaveOptions` | Die Speicheroptionen. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
