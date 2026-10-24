---
title: "Método sign"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Firma el documento con SignOptions y guarda el resultado en un flujo."
type: docs
url: /es/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Firma el documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en un flujo.

```python
def sign(self, document, sign_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo del documento de salida. |
| sign_options | `SignOptions` | Las opciones de firma. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Observaciones:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Ejemplo

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

Firma un documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en un flujo usando los [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefinidos.

Aprende más
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo del documento de salida. |
| sign_options | `SignOptions` | Las opciones de firma. |
| save_options | `SaveOptions` | Las opciones de guardado. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Firma el documento con una colección de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en un flujo.

Aprende más

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo del documento de salida. |
| sign_options_list | `List[SignOptions]` | La lista de opciones de firma. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Firma el documento con una colección de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en un flujo usando los [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefinidos.

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo del documento de salida. |
| sign_options_list | `List[SignOptions]` | La lista de opciones de firma. |
| save_options | `SaveOptions` | Las opciones de guardado. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Observaciones:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Firme y guarde el resultado en un archivo nuevo; el documento original permanece sin cambios
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Firma el documento con SignOptions y guarda el resultado en la ruta de archivo especificada.

Aprende más

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo de salida. |
| sign_options | `SignOptions` | Las opciones de firma. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Ejemplo

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

Firma el documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en la ruta de archivo especificada usando los [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefinidos.

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo de salida. |
| sign_options | `SignOptions` | Las opciones de firma. |
| save_options | `SaveOptions` | Las opciones de guardado. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Abra el documento; el bloque with libera el archivo cuando termina
    with Signature("sample.pdf") as signature:
        # Una firma de texto a 100 píxeles de los bordes izquierdo y superior de la primera página
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Firme y guarde el resultado en un archivo nuevo; el documento original permanece sin cambios
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Firma el documento con una colección de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en la ruta de archivo especificada.

Más información:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo de salida. |
| sign_options_list | `List[SignOptions]` | La lista de opciones de firma. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Ejemplo

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

Firma el documento con una colección de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en la ruta de archivo especificada usando los [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefinidos.

Más información:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | La ruta del archivo de salida. |
| sign_options_list | `List[SignOptions]` | La lista de opciones de firma. |
| save_options | `SaveOptions` | Las opciones de guardado. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
