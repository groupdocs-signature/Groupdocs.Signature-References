---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belge bir akış olarak sağlandığında yeni bir Signature örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Belge bir akış olarak sağlandığında yeni bir Signature örneği başlatır.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belgenin içerik akışı. |

## __init__ {#document-load_options}

Belge akışı ve yükleme seçenekleriyle yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır.

Daha fazla bilgi edinin

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belgenin içerik akışı. |
| load_options | `LoadOptions` | Belge yükleme seçenekleri. |

## __init__ {#document-settings}

Bir akış tarafından sağlanan belge ve isteğe bağlı [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) ile yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır.

Daha fazla bilgi:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belgenin içerik akışı. |
| settings | `SignatureSettings` | İmza ayarları. |

## __init__ {#document-load_options-settings}

Belge akışı, yükleme seçenekleri ve imza ayarlarıyla yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Belgenin içerik akışı. |
| load_options | `LoadOptions` | Belge yükleme seçenekleri. |
| settings | `SignatureSettings` | İmza ayarları. |

## __init__ {#file_path}

Dosya yolu ile sağlanan belgeyle yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Mutlak ya da göreceli dosya yolu. |

### Örnek

```python
from groupdocs.signature import Signature

# İmzalama, arama veya doğrulama için bir belge açın
with Signature("sample.pdf") as signature:
    # İmza nesnesiyle çalışın
    pass
```

## __init__ {#file_path-load_options}

Dosya yolu ve yükleme seçenekleriyle sağlanan belgeyle yeni bir Signature örneği başlatır.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Mutlak ya da göreceli dosya yolu. |
| load_options | `LoadOptions` | Belge yükleme seçenekleri. |

### Örnek

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # İmzalama, arama veya doğrulama işlemlerini gerçekleştirin
    pass
```

## __init__ {#file_path-settings}

Dosya yolu ile sağlanan belge ve isteğe bağlı [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) ile yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır.

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Mutlak ya da göreceli dosya yolu. |
| settings | `SignatureSettings` | İmza ayarları. |

### Örnek

```python
from groupdocs.signature import Signature

# İmzalama veya doğrulama için bir PDF belgesi açın
with Signature("sample.pdf") as signature:
    # İmza örneğini burada kullanın (ör. imzala, doğrula, ara)
    pass
```

## __init__ {#file_path-load_options-settings}

Dosya yolu, yükleme seçenekleri ve imza ayarlarıyla sağlanan belgeyle yeni bir [`Signature`](/signature/python-net/groupdocs.signature/signature/) örneği başlatır.

Daha fazla bilgi:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Mutlak ya da göreceli dosya yolu. |
| load_options | `LoadOptions` | Belge yükleme seçenekleri. |
| settings | `SignatureSettings` | İmza ayarları. |

### Örnek

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # imzalama, doğrulama veya arama işlemlerini gerçekleştirin
    pass
```

### Ayrıca Bakınız
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
