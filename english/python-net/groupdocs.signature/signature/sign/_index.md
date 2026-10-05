---
title: sign method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Signs document with SignOptions and saves result to a stream."
type: docs
url: /python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves result to a stream.

```python
def sign(self, document, sign_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The output document stream. |
| sign_options | `SignOptions` | The signature options. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Remarks:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Example

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

Signs a document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves the result to a stream using predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Learn more
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The output document stream. |
| sign_options | `SignOptions` | The signature options. |
| save_options | `SaveOptions` | The save options. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Signs document with a collection of [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves the result to a stream.

Learn more

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The output document stream. |
| sign_options_list | `List[SignOptions]` | The list of signature options. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Signs document with a collection of [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves the result to a stream using predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | The output document stream. |
| sign_options_list | `List[SignOptions]` | The list of signature options. |
| save_options | `SaveOptions` | The save options. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Remarks:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Sign and save the result to a new file; the source stays unchanged
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Signs document with SignOptions and saves result to specified file path.

Learn more

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The output file path. |
| sign_options | `SignOptions` | The signature options. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Example

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

Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves result to specified file path with predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The output file path. |
| sign_options | `SignOptions` | The signature options. |
| save_options | `SaveOptions` | The save options. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Open the document; the with-block releases the file when it ends
    with Signature("sample.pdf") as signature:
        # A text signature 100 pixels from the left and top edges of the first page
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Sign and save the result to a new file; the source stays unchanged
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Signs document with collection of [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves result to specified file path.

Learn more:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The output file path. |
| sign_options_list | `List[SignOptions]` | The list of signature options. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Example

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

Signs the document with a collection of [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves the result to the specified file path using predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/).

Learn more:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The output file path. |
| sign_options_list | `List[SignOptions]` | The list of signature options. |
| save_options | `SaveOptions` | The save options. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### See Also
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
