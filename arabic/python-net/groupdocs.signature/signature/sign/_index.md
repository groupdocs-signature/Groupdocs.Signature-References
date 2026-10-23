---
title: "طريقة sign"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يوقع المستند باستخدام SignOptions ويحفظ النتيجة إلى تدفق."
type: docs
url: /ar/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

يوقع المستند باستخدام [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة في تدفق.

```python
def sign(self, document, sign_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | تدفق المستند الناتج. |
| sign_options | `SignOptions` | خيارات التوقيع. |

**Returns:** SignResult: Instance containing list of newly created signatures.

ملاحظات:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### مثال

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

يوقع مستندًا باستخدام [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة في تدفق باستخدام [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) المحددة مسبقًا.

اعرف المزيد
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | تدفق المستند الناتج. |
| sign_options | `SignOptions` | خيارات التوقيع. |
| save_options | `SaveOptions` | خيارات الحفظ. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

يوقع المستند بمجموعة من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة في تدفق.

اعرف المزيد

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | تدفق المستند الناتج. |
| sign_options_list | `List[SignOptions]` | قائمة خيارات التوقيع. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

يوقع المستند بمجموعة من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة في تدفق باستخدام [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) المحددة مسبقًا.

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | تدفق المستند الناتج. |
| sign_options_list | `List[SignOptions]` | قائمة خيارات التوقيع. |
| save_options | `SaveOptions` | خيارات الحفظ. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

ملاحظات:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # وقّع واحفظ النتيجة في ملف جديد؛ يبقى المصدر دون تغيير
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

يوقع المستند باستخدام SignOptions ويحفظ النتيجة إلى مسار الملف المحدد.

اعرف المزيد

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار ملف الإخراج. |
| sign_options | `SignOptions` | خيارات التوقيع. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### مثال

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

يوقع المستند باستخدام [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة إلى مسار الملف المحدد باستخدام [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) المحددة مسبقًا.

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار ملف الإخراج. |
| sign_options | `SignOptions` | خيارات التوقيع. |
| save_options | `SaveOptions` | خيارات الحفظ. |

**Returns:** SignResult: Instance with list of newly created signatures.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # افتح المستند؛ الـwith‑block يحرر الملف عند انتهائه
    with Signature("sample.pdf") as signature:
        # توقيع نصي على بعد 100 بكسل من الحافة اليسرى والعلوية للصفحة الأولى
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # وقّع واحفظ النتيجة في ملف جديد؛ يبقى المصدر دون تغيير
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

يوقع المستند بمجموعة من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة إلى مسار الملف المحدد.

تعرف على المزيد:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار ملف الإخراج. |
| sign_options_list | `List[SignOptions]` | قائمة خيارات التوقيع. |

**Returns:** SignResult: Instance with list of newly created signatures.

### مثال

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

يوقع المستند بمجموعة من [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) ويحفظ النتيجة إلى مسار الملف المحدد باستخدام [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) المحددة مسبقًا.

تعرف على المزيد:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار ملف الإخراج. |
| sign_options_list | `List[SignOptions]` | قائمة خيارات التوقيع. |
| save_options | `SaveOptions` | خيارات الحفظ. |

**Returns:** SignResult: Instance with list of newly created signatures.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### انظر أيضًا
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
