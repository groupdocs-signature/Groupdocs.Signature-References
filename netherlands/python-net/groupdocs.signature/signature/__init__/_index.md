---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw Signature‑object met een document dat als stream wordt aangeleverd."
type: docs
url: /nl/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Initialiseert een nieuw Signature‑object met een document dat als stream wordt aangeleverd.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De documentinhoudstroom. |

## __init__ {#document-load_options}

Initialiseert een nieuw [`Signature`](/signature/python-net/groupdocs.signature/signature/) object met een document‑stream en laadopties.

Meer informatie

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De documentinhoudstroom. |
| load_options | `LoadOptions` | De documentlaadopties. |

## __init__ {#document-settings}

Initialiseert een nieuw [`Signature`](/signature/python-net/groupdocs.signature/signature/) object met een document dat via een stream wordt aangeleverd en optionele [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Meer informatie:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De documentinhoudstroom. |
| settings | `SignatureSettings` | De handtekeninginstellingen. |

## __init__ {#document-load_options-settings}

Initialiseert een nieuw exemplaar van [`Signature`](/signature/python-net/groupdocs.signature/signature/) met een document‑stream, laadopties en [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| document | `io.RawIOBase` | De documentinhoudstroom. |
| load_options | `LoadOptions` | De documentlaadopties. |
| settings | `SignatureSettings` | De handtekeninginstellingen. |

## __init__ {#file_path}

Initialiseert een nieuw exemplaar van [`Signature`](/signature/python-net/groupdocs.signature/signature/) met een document dat via een bestandspad wordt aangeleverd.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Absoluut of relatief bestandspad. |

### Voorbeeld

```python
from groupdocs.signature import Signature

# Open een document voor ondertekenen, zoeken of verifiëren
with Signature("sample.pdf") as signature:
    # werken met het handtekeningobject
    pass
```

## __init__ {#file_path-load_options}

Initialiseert een nieuw Signature‑object met het document dat via een bestandspad wordt aangeleverd en laadopties.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Absoluut of relatief bestandspad. |
| load_options | `LoadOptions` | De documentlaadopties. |

### Voorbeeld

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Voer ondertekenings-, zoek- of verificatiebewerkingen uit
    pass
```

## __init__ {#file_path-settings}

Initialiseert een nieuw [`Signature`](/signature/python-net/groupdocs.signature/signature/) object met het document dat via een bestandspad wordt aangeleverd en optionele [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Absoluut of relatief bestandspad. |
| settings | `SignatureSettings` | De handtekeninginstellingen. |

### Voorbeeld

```python
from groupdocs.signature import Signature

# Open een PDF-document voor ondertekenen of verifiëren
with Signature("sample.pdf") as signature:
    # Gebruik hier de handtekeninginstantie (bijv., ondertekenen, verifiëren, zoeken)
    pass
```

## __init__ {#file_path-load_options-settings}

Initialiseert een nieuw exemplaar van [`Signature`](/signature/python-net/groupdocs.signature/signature/) met een document dat via een bestandspad wordt aangeleverd, laadopties en [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Meer informatie:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Absoluut of relatief bestandspad. |
| load_options | `LoadOptions` | De documentlaadopties. |
| settings | `SignatureSettings` | De handtekeninginstellingen. |

### Voorbeeld

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # ondertekenings-, verificatie- of zoekbewerkingen uitvoeren
    pass
```

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
