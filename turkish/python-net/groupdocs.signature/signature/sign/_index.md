---
title: "sign yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belgeyi SignOptions ile imzalar ve sonucu bir akışa kaydeder."
type: docs
url: /tr/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Belgeyi [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ile imzalar ve sonucu bir akışa kaydeder.

```python
def sign(self, document, sign_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Çıktı belge akışı. |
| sign_options | `SignOptions` | İmza seçenekleri. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Açıklamalar:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Örnek

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

Bir belgeyi [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ile imzalar ve önceden tanımlı [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) kullanarak sonucu bir akışa kaydeder.

Daha fazla bilgi edinin
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Çıktı belge akışı. |
| sign_options | `SignOptions` | İmza seçenekleri. |
| save_options | `SaveOptions` | Kaydetme seçenekleri. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Belgeyi bir [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) koleksiyonu ile imzalar ve sonucu bir akışa kaydeder.

Daha fazla bilgi edinin

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Çıktı belge akışı. |
| sign_options_list | `List[SignOptions]` | İmza seçenekleri listesi. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Belgeyi bir [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) koleksiyonu ile imzalar ve önceden tanımlı [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) kullanarak sonucu bir akışa kaydeder.

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| document | `io.RawIOBase` | Çıktı belge akışı. |
| sign_options_list | `List[SignOptions]` | İmza seçenekleri listesi. |
| save_options | `SaveOptions` | Kaydetme seçenekleri. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Açıklamalar:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # İmzala ve sonucu yeni bir dosyaya kaydet; kaynak değişmeden kalır
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Belgeyi SignOptions ile imzalar ve sonucu belirtilen dosya yoluna kaydeder.

Daha fazla bilgi edinin

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Çıktı dosya yolu. |
| sign_options | `SignOptions` | İmza seçenekleri. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Örnek

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

Belgeyi [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ile imzalar ve önceden tanımlı [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) kullanarak sonucu belirtilen dosya yoluna kaydeder.

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Çıktı dosya yolu. |
| sign_options | `SignOptions` | İmza seçenekleri. |
| save_options | `SaveOptions` | Kaydetme seçenekleri. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Belgeyi açın; with-blok, dosyayı sona erdiğinde serbest bırakır
    with Signature("sample.pdf") as signature:
        # İlk sayfanın sol ve üst kenarlarından 100 piksel uzakta bir metin imzası
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # İmzala ve sonucu yeni bir dosyaya kaydet; kaynak değişmeden kalır
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Belgeyi bir [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) koleksiyonu ile imzalar ve sonucu belirtilen dosya yoluna kaydeder.

Daha fazla bilgi:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Çıktı dosya yolu. |
| sign_options_list | `List[SignOptions]` | İmza seçenekleri listesi. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Örnek

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

Belgeyi bir [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) koleksiyonu ile imzalar ve önceden tanımlı [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) kullanarak sonucu belirtilen dosya yoluna kaydeder.

Daha fazla bilgi:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Çıktı dosya yolu. |
| sign_options_list | `List[SignOptions]` | İmza seçenekleri listesi. |
| save_options | `SaveOptions` | Kaydetme seçenekleri. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Ayrıca Bakınız
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
