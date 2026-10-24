---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de Signature con un documento proporcionado como flujo."
type: docs
url: /es/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Inicializa una nueva instancia de Signature con un documento proporcionado como flujo.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo de contenido del documento. |

## __init__ {#document-load_options}

Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un flujo de documento y opciones de carga.

Aprende más

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo de contenido del documento. |
| load_options | `LoadOptions` | Las opciones de carga del documento. |

## __init__ {#document-settings}

Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento proporcionado mediante un flujo y opcionalmente con [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Más información:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo de contenido del documento. |
| settings | `SignatureSettings` | La configuración de la firma. |

## __init__ {#document-load_options-settings}

Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un flujo de documento, opciones de carga y configuraciones de firma.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| document | `io.RawIOBase` | El flujo de contenido del documento. |
| load_options | `LoadOptions` | Las opciones de carga del documento. |
| settings | `SignatureSettings` | La configuración de la firma. |

## __init__ {#file_path}

Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento proporcionado por ruta de archivo.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | Ruta de archivo absoluta o relativa. |

### Ejemplo

```python
from groupdocs.signature import Signature

# Abrir un documento para firmar, buscar o verificar
with Signature("sample.pdf") as signature:
    # trabajar con el objeto de firma
    pass
```

## __init__ {#file_path-load_options}

Inicializa una nueva instancia de Signature con el documento proporcionado por ruta de archivo y opciones de carga.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | Ruta de archivo absoluta o relativa. |
| load_options | `LoadOptions` | Las opciones de carga del documento. |

### Ejemplo

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Realizar operaciones de firma, búsqueda o verificación
    pass
```

## __init__ {#file_path-settings}

Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con el documento proporcionado por una ruta de archivo y opcionalmente con [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | Ruta de archivo absoluta o relativa. |
| settings | `SignatureSettings` | La configuración de la firma. |

### Ejemplo

```python
from groupdocs.signature import Signature

# Abrir un documento PDF para firmar o verificar
with Signature("sample.pdf") as signature:
    # Utilizar la instancia de firma aquí (p. ej., firmar, verificar, buscar).
    pass
```

## __init__ {#file_path-load_options-settings}

Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento proporcionado por ruta de archivo, opciones de carga y configuraciones de firma.

Más información:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | Ruta de archivo absoluta o relativa. |
| load_options | `LoadOptions` | Las opciones de carga del documento. |
| settings | `SignatureSettings` | La configuración de la firma. |

### Ejemplo

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # realizar operaciones de firma, verificación o búsqueda.
    pass
```

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
