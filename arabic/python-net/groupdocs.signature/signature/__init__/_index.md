---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُنشئ كائن Signature جديد باستخدام مستند مقدم كتيار."
type: docs
url: /ar/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

يُنشئ كائن Signature جديد باستخدام مستند مقدم كتيار.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | دفق محتوى المستند. |

## __init__ {#document-load_options}

يُنشئ كائن [`Signature`](/signature/python-net/groupdocs.signature/signature/) جديد باستخدام تيار المستند وخيارات التحميل.

اعرف المزيد

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | دفق محتوى المستند. |
| load_options | `LoadOptions` | خيارات تحميل المستند. |

## __init__ {#document-settings}

يُنشئ كائن [`Signature`](/signature/python-net/groupdocs.signature/signature/) جديد باستخدام مستند مقدم عبر تيار و [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) اختيارية.

تعرف على المزيد:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | دفق محتوى المستند. |
| settings | `SignatureSettings` | إعدادات التوقيع. |

## __init__ {#document-load_options-settings}

يُنشئ كائن جديد من [`Signature`](/signature/python-net/groupdocs.signature/signature/) باستخدام تيار المستند، خيارات التحميل، وإعدادات التوقيع.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| document | `io.RawIOBase` | دفق محتوى المستند. |
| load_options | `LoadOptions` | خيارات تحميل المستند. |
| settings | `SignatureSettings` | إعدادات التوقيع. |

## __init__ {#file_path}

يُنشئ كائن جديد من [`Signature`](/signature/python-net/groupdocs.signature/signature/) باستخدام مستند مقدم عبر مسار الملف.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار ملف مطلق أو نسبي. |

### مثال

```python
from groupdocs.signature import Signature

# افتح مستندًا للتوقيع أو البحث أو التحقق
with Signature("sample.pdf") as signature:
    # العمل مع كائن التوقيع
    pass
```

## __init__ {#file_path-load_options}

يُنشئ كائن Signature جديد باستخدام المستند المقدم عبر مسار الملف وخيارات التحميل.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار ملف مطلق أو نسبي. |
| load_options | `LoadOptions` | خيارات تحميل المستند. |

### مثال

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # أداء عمليات التوقيع أو البحث أو التحقق
    pass
```

## __init__ {#file_path-settings}

يُنشئ كائن [`Signature`](/signature/python-net/groupdocs.signature/signature/) جديد باستخدام المستند المقدم عبر مسار ملف و [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) اختيارية.

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار ملف مطلق أو نسبي. |
| settings | `SignatureSettings` | إعدادات التوقيع. |

### مثال

```python
from groupdocs.signature import Signature

# افتح مستند PDF للتوقيع أو التحقق
with Signature("sample.pdf") as signature:
    # استخدم كائن التوقيع هنا (مثال: sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

يُنشئ كائن جديد من [`Signature`](/signature/python-net/groupdocs.signature/signature/) باستخدام مستند مقدم عبر مسار ملف، خيارات التحميل، وإعدادات التوقيع.

تعرف على المزيد:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار ملف مطلق أو نسبي. |
| load_options | `LoadOptions` | خيارات تحميل المستند. |
| settings | `SignatureSettings` | إعدادات التوقيع. |

### مثال

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # أداء عمليات التوقيع أو التحقق أو البحث
    pass
```

### انظر أيضًا
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
