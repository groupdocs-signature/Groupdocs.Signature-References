---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ مثيلاً جديداً من فئة Padding بقيم صفرية."
type: docs
url: /ar/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديداً من فئة Padding بقيم صفرية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.signature.domain import Padding

# إنشاء كائن حشو بالقيم الافتراضية (صفر)
default_padding = Padding()
```

## __init__ {#all}

ينشئ مثيلاً جديداً من فئة Padding باستخدام حجم الحشو المقدم لجميع الحواف.

```python
def __init__(self, all):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| all | `int` | عدد وحدات القياس التي ستُستخدم للحشو لجميع الحواف. |

### مثال

```python
# حشو موحد بقيمة 5 وحدات على جميع الجوانب
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

ينشئ مثيلاً جديداً من فئة Padding باستخدام أحجام الحشو المقدمة.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| left | `int` | حجم الحشو الأيسر. |
| right | `int` | حجم الحشو الأيمن. |
| top | `int` | حجم الحشو العلوي. |
| bottom | `int` | حجم الحشو السفلي. |

### مثال

```python
from groupdocs.signature.domain import Padding

# إنشاء حشو بإزاحات يمين وسفلي
margin = Padding(right=40, bottom=60)
```

### انظر أيضًا
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
