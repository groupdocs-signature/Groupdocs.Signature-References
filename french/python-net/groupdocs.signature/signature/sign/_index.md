---
title: "méthode sign"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Signe le document avec SignOptions et enregistre le résultat dans un flux."
type: docs
url: /fr/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Signe le document avec [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat dans un flux.

```python
def sign(self, document, sign_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux du document de sortie. |
| sign_options | `SignOptions` | Les options de signature. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Remarques :
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Exemple

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

Signe un document avec [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat dans un flux en utilisant les [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) prédéfinis.

En savoir plus
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux du document de sortie. |
| sign_options | `SignOptions` | Les options de signature. |
| save_options | `SaveOptions` | Les options d'enregistrement. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Signe le document avec une collection de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat dans un flux.

En savoir plus

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux du document de sortie. |
| sign_options_list | `List[SignOptions]` | La liste des options de signature. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Signe le document avec une collection de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat dans un flux en utilisant les [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) prédéfinis.

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux du document de sortie. |
| sign_options_list | `List[SignOptions]` | La liste des options de signature. |
| save_options | `SaveOptions` | Les options d'enregistrement. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Remarques :
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signez et enregistrez le résultat dans un nouveau fichier ; la source reste inchangée
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Signe le document avec SignOptions et enregistre le résultat à l'emplacement de fichier spécifié.

En savoir plus

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier de sortie. |
| sign_options | `SignOptions` | Les options de signature. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Exemple

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

Signe le document avec [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat à l'emplacement de fichier spécifié en utilisant les [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) prédéfinis.

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier de sortie. |
| sign_options | `SignOptions` | Les options de signature. |
| save_options | `SaveOptions` | Les options d'enregistrement. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Ouvrez le document ; le with‑block libère le fichier lorsqu’il se termine
    with Signature("sample.pdf") as signature:
        # Une signature texte à 100 pixels du bord gauche et du bord supérieur de la première page
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signez et enregistrez le résultat dans un nouveau fichier ; la source reste inchangée
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Signe le document avec une collection de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat à l'emplacement de fichier spécifié.

En savoir plus :
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier de sortie. |
| sign_options_list | `List[SignOptions]` | La liste des options de signature. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Exemple

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

Signe le document avec une collection de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) et enregistre le résultat à l'emplacement de fichier spécifié en utilisant les [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) prédéfinis.

En savoir plus :
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier de sortie. |
| sign_options_list | `List[SignOptions]` | La liste des options de signature. |
| save_options | `SaveOptions` | Les options d'enregistrement. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Voir aussi
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
