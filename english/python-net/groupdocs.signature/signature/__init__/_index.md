---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new Signature instance with a document provided as a stream."
type: docs
url: /python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Initializes a new Signature instance with a document provided as a stream.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The document content stream. |

## __init__ {#document-load_options}

Initializes a new [`Signature`](/signature/python-net/groupdocs.signature/signature/) instance with a document stream and load options.

Learn more

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The document content stream. |
| load_options | `LoadOptions` | The document load options. |

## __init__ {#document-settings}

Initializes a new [`Signature`](/signature/python-net/groupdocs.signature/signature/) instance with a document provided by a stream and optional [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Learn more:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The document content stream. |
| settings | `SignatureSettings` | The signature settings. |

## __init__ {#document-load_options-settings}

Initializes a new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature/) with a document stream, load options, and signature settings.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The document content stream. |
| load_options | `LoadOptions` | The document load options. |
| settings | `SignatureSettings` | The signature settings. |

## __init__ {#file_path}

Initializes a new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature/) with a document provided by file path.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | Absolute or relative file path. |

### Example

```python
from groupdocs.signature import Signature

# Open a document for signing, searching, or verification
with Signature("sample.pdf") as signature:
    # work with the signature object
    pass
```

## __init__ {#file_path-load_options}

Initializes a new Signature instance with the document provided by file path and load options.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | Absolute or relative file path. |
| load_options | `LoadOptions` | The document load options. |

### Example

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Perform signing, searching, or verification operations
    pass
```

## __init__ {#file_path-settings}

Initializes a new [`Signature`](/signature/python-net/groupdocs.signature/signature/) instance with the document provided by a file path and optional [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | Absolute or relative file path. |
| settings | `SignatureSettings` | The signature settings. |

### Example

```python
from groupdocs.signature import Signature

# Open a PDF document for signing or verification
with Signature("sample.pdf") as signature:
    # Use the signature instance here (e.g., sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

Initializes a new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature/) with a document provided by file path, load options, and signature settings.

Learn more:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | Absolute or relative file path. |
| load_options | `LoadOptions` | The document load options. |
| settings | `SignatureSettings` | The signature settings. |

### Example

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # perform signing, verification, or searching operations
    pass
```

### See Also
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
