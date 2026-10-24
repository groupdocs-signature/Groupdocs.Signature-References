---
title: "sign-metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Signerar dokument med SignOptions och sparar resultatet till en ström."
type: docs
url: /sv/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Signerar dokument med [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till ett flöde.

```python
def sign(self, document, sign_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Ström för utdata-dokumentet. |
| sign_options | `SignOptions` | Signaturalternativen. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Anmärkningar:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Exempel

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

Signerar ett dokument med [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till ett flöde med fördefinierade [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Läs mer
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Ström för utdata-dokumentet. |
| sign_options | `SignOptions` | Signaturalternativen. |
| save_options | `SaveOptions` | Sparalternativen. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Signerar dokument med en samling av [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till ett flöde.

Läs mer

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Ström för utdata-dokumentet. |
| sign_options_list | `List[SignOptions]` | Listan med signaturalternativ. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Signerar dokument med en samling av [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till ett flöde med fördefinierade [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Ström för utdata-dokumentet. |
| sign_options_list | `List[SignOptions]` | Listan med signaturalternativ. |
| save_options | `SaveOptions` | Sparalternativen. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Anmärkningar:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signera och spara resultatet till en ny fil; källfilen förblir oförändrad.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Signerar dokument med SignOptions och sparar resultatet till angiven filsökväg.

Läs mer

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen för utdatafilen. |
| sign_options | `SignOptions` | Signaturalternativen. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Exempel

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

Signerar dokument med [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till angiven filsökväg med fördefinierade [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen för utdatafilen. |
| sign_options | `SignOptions` | Signaturalternativen. |
| save_options | `SaveOptions` | Sparalternativen. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Öppna dokumentet; with-blocket frigör filen när det avslutas
    with Signature("sample.pdf") as signature:
        # En textsignatur 100 pixlar från vänster- och överkanten på den första sidan.
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Signera och spara resultatet till en ny fil; källfilen förblir oförändrad.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Signerar dokument med en samling av [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till angiven filsökväg.

Läs mer:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen för utdatafilen. |
| sign_options_list | `List[SignOptions]` | Listan med signaturalternativ. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Exempel

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

Signerar dokumentet med en samling av [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) och sparar resultatet till den angivna filsökvägen med fördefinierade [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Läs mer:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen för utdatafilen. |
| sign_options_list | `List[SignOptions]` | Listan med signaturalternativ. |
| save_options | `SaveOptions` | Sparalternativen. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Se även
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
