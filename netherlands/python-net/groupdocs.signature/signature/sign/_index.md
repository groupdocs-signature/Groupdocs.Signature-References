---
title: "sign methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Ondertekent document met SignOptions en slaat het resultaat op in een stream."
type: docs
url: /nl/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Ondertekent het document met [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op in een stream.

```python
def sign(self, document, sign_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De uitvoer documentstream. |
| sign_options | `SignOptions` | De handtekeningopties. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Opmerkingen:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Voorbeeld

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

Ondertekent een document met [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op in een stream met behulp van vooraf gedefinieerde [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Meer informatie
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De uitvoer documentstream. |
| sign_options | `SignOptions` | De handtekeningopties. |
| save_options | `SaveOptions` | De opslagopties. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Ondertekent het document met een verzameling van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op in een stream.

Meer informatie

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De uitvoer documentstream. |
| sign_options_list | `List[SignOptions]` | De lijst met handtekeningopties. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Ondertekent het document met een verzameling van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op in een stream met behulp van vooraf gedefinieerde [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De uitvoer documentstream. |
| sign_options_list | `List[SignOptions]` | De lijst met handtekeningopties. |
| save_options | `SaveOptions` | De opslagopties. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Opmerkingen:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Onderteken en sla het resultaat op in een nieuw bestand; de bron blijft ongewijzigd
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Ondertekent het document met SignOptions en slaat het resultaat op naar het opgegeven bestandspad.

Meer informatie

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het uitvoerbestandspad. |
| sign_options | `SignOptions` | De handtekeningopties. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Voorbeeld

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

Ondertekent het document met [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het uitvoerbestandspad. |
| sign_options | `SignOptions` | De handtekeningopties. |
| save_options | `SaveOptions` | De opslagopties. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Open het document; het with-blok geeft het bestand vrij wanneer het eindigt
    with Signature("sample.pdf") as signature:
        # Een teksthandtekening 100 pixels vanaf de linker- en bovenrand van de eerste pagina
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Onderteken en sla het resultaat op in een nieuw bestand; de bron blijft ongewijzigd
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Ondertekent het document met een verzameling van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op naar het opgegeven bestandspad.

Meer informatie:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het uitvoerbestandspad. |
| sign_options_list | `List[SignOptions]` | De lijst met handtekeningopties. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Voorbeeld

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

Ondertekent het document met een verzameling van [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) en slaat het resultaat op naar het opgegeven bestandspad met vooraf gedefinieerde [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Meer informatie:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het uitvoerbestandspad. |
| sign_options_list | `List[SignOptions]` | De lijst met handtekeningopties. |
| save_options | `SaveOptions` | De opslagopties. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
