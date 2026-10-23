---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de Signature avec un document fourni sous forme de flux."
type: docs
url: /fr/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Initialise une nouvelle instance de Signature avec un document fourni sous forme de flux.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux de contenu du document. |

## __init__ {#document-load_options}

Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un flux de document et des options de chargement.

En savoir plus

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux de contenu du document. |
| load_options | `LoadOptions` | Les options de chargement du document. |

## __init__ {#document-settings}

Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un document fourni par un flux et des [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) optionnels.

En savoir plus :

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux de contenu du document. |
| settings | `SignatureSettings` | Les paramètres de signature. |

## __init__ {#document-load_options-settings}

Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un flux de document, des options de chargement et les paramètres de signature.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux de contenu du document. |
| load_options | `LoadOptions` | Les options de chargement du document. |
| settings | `SignatureSettings` | Les paramètres de signature. |

## __init__ {#file_path}

Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un document fourni par chemin de fichier.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Chemin de fichier absolu ou relatif. |

### Exemple

```python
from groupdocs.signature import Signature

# Ouvrir un document pour la signature, la recherche ou la vérification
with Signature("sample.pdf") as signature:
    # travailler avec l'objet de signature
    pass
```

## __init__ {#file_path-load_options}

Initialise une nouvelle instance de Signature avec le document fourni par chemin de fichier et des options de chargement.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Chemin de fichier absolu ou relatif. |
| load_options | `LoadOptions` | Les options de chargement du document. |

### Exemple

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Effectuer des opérations de signature, de recherche ou de vérification
    pass
```

## __init__ {#file_path-settings}

Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec le document fourni par un chemin de fichier et des [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) optionnels.

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Chemin de fichier absolu ou relatif. |
| settings | `SignatureSettings` | Les paramètres de signature. |

### Exemple

```python
from groupdocs.signature import Signature

# Ouvrir un document PDF pour la signature ou la vérification
with Signature("sample.pdf") as signature:
    # Utilisez l'instance de signature ici (par ex., sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

Initialise une nouvelle instance de [`Signature`](/signature/python-net/groupdocs.signature/signature/) avec un document fourni par chemin de fichier, des options de chargement et les paramètres de signature.

En savoir plus :
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Chemin de fichier absolu ou relatif. |
| load_options | `LoadOptions` | Les options de chargement du document. |
| settings | `SignatureSettings` | Les paramètres de signature. |

### Exemple

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # effectuer des opérations de signature, de vérification ou de recherche
    pass
```

### Voir aussi
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
