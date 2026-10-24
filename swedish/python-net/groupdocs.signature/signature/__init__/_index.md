---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny Signature-instans med ett dokument som tillhandahålls som en ström."
type: docs
url: /sv/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Initierar en ny Signature-instans med ett dokument som tillhandahålls som en ström.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Dokumentets innehållsström. |

## __init__ {#document-load_options}

Initierar en ny [`Signature`](/signature/python-net/groupdocs.signature/signature/) instans med ett dokumentflöde och inläsningsalternativ.

Läs mer

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Dokumentets innehållsström. |
| load_options | `LoadOptions` | Dokumentets laddningsalternativ. |

## __init__ {#document-settings}

Initierar en ny [`Signature`](/signature/python-net/groupdocs.signature/signature/) instans med ett dokument som tillhandahålls av ett flöde och valfria [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Läs mer:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Dokumentets innehållsström. |
| settings | `SignatureSettings` | Signaturinställningarna. |

## __init__ {#document-load_options-settings}

Initierar en ny instans av [`Signature`](/signature/python-net/groupdocs.signature/signature/) med ett dokumentflöde, inläsningsalternativ och signaturinställningar.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| document | `io.RawIOBase` | Dokumentets innehållsström. |
| load_options | `LoadOptions` | Dokumentets laddningsalternativ. |
| settings | `SignatureSettings` | Signaturinställningarna. |

## __init__ {#file_path}

Initierar en ny instans av [`Signature`](/signature/python-net/groupdocs.signature/signature/) med ett dokument som tillhandahålls via filväg.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Absolut eller relativ filsökväg. |

### Exempel

```python
from groupdocs.signature import Signature

# Öppna ett dokument för signering, sökning eller verifiering
with Signature("sample.pdf") as signature:
    # arbeta med signaturobjektet
    pass
```

## __init__ {#file_path-load_options}

Initierar en ny Signature-instans med dokumentet som tillhandahålls via filväg och inläsningsalternativ.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Absolut eller relativ filsökväg. |
| load_options | `LoadOptions` | Dokumentets laddningsalternativ. |

### Exempel

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Utför signerings-, sök- eller verifieringsoperationer
    pass
```

## __init__ {#file_path-settings}

Initierar en ny [`Signature`](/signature/python-net/groupdocs.signature/signature/) instans med dokumentet som tillhandahålls via en filväg och valfria [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Absolut eller relativ filsökväg. |
| settings | `SignatureSettings` | Signaturinställningarna. |

### Exempel

```python
from groupdocs.signature import Signature

# Öppna ett PDF-dokument för signering eller verifiering
with Signature("sample.pdf") as signature:
    # Använd signaturinstansen här (t.ex. signera, verifiera, söka)
    pass
```

## __init__ {#file_path-load_options-settings}

Initierar en ny instans av [`Signature`](/signature/python-net/groupdocs.signature/signature/) med ett dokument som tillhandahålls via filväg, inläsningsalternativ och signaturinställningar.

Läs mer:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Absolut eller relativ filsökväg. |
| load_options | `LoadOptions` | Dokumentets laddningsalternativ. |
| settings | `SignatureSettings` | Signaturinställningarna. |

### Exempel

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # utföra signerings-, verifierings- eller sökoperationer
    pass
```

### Se även
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
