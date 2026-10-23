---
title: "طريقة verify"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة."
type: docs
url: /ar/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة.

المزيد حول التحقق من المستندات الموقعة إلكترونيًا باستخدام GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| verify_options | `VerifyOptions` | خيارات التحقق من التوقيع. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options-predicate}

يتحقق من توقيعات المستند باستخدام خيارات التحقق المقدمة ويصفي النتائج بناءً على الشرط المحدد.

اعرف المزيد

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| verify_options | `VerifyOptions` | خيارات التحقق من التوقيع. |
| predicate | `Func[BaseSignature, bool]` | دالة الترشيح لتحديد أي التوقيعات يجب التحقق منها. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options, lambda s: True)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list}

يتحقق من توقيعات المستند باستخدام قائمة من بيانات VerifyOptions.

المزيد حول التحقق من المستندات الموقعة إلكترونيًا باستخدام GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | مجموعة خيارات التحقق من التوقيع. مثال من `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list-predicate}

يتحقق من توقيعات المستند باستخدام خيارات التحقق المقدمة ويُفلتر النتائج باستخدام الشرط المحدد.

تبحث الطريقة أولاً عن التوقيعات التي تطابق خيارات التحقق، ثم تقوم بترشيحها باستخدام الدالة، ثم تتحقق فقط من تلك التوقيعات المصفاة.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | مجموعة خيارات التحقق من التوقيع. |
| predicate | `Func[BaseSignature, bool]` | دالة الترشيح لتحديد أي التوقيعات يجب التحقق منها. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify([options], lambda s: s.text == "John Smith")
        print(f"Document is signed by John Smith: {result[0].is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### انظر أيضًا
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
