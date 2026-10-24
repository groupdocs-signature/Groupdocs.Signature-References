---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует новый экземпляр класса Padding со значениями, равными нулю."
type: docs
url: /ru/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса Padding со значениями, равными нулю.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.signature.domain import Padding

# Создать объект отступа с значениями по умолчанию (ноль)
default_padding = Padding()
```

## __init__ {#all}

Инициализирует новый экземпляр класса Padding, используя заданный размер отступа для всех сторон.

```python
def __init__(self, all):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| all | `int` | Количество единиц измерения, используемых для отступа всех граней. |

### Пример

```python
# Однородный отступ в 5 единиц со всех сторон
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Инициализирует новый экземпляр класса Padding, используя заданные размеры отступов.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| left | `int` | Размер левого отступа. |
| right | `int` | Размер правого отступа. |
| top | `int` | Размер верхнего отступа. |
| bottom | `int` | Размер нижнего отступа. |

### Пример

```python
from groupdocs.signature.domain import Padding

# Создать отступ с правыми и нижними смещениями
margin = Padding(right=40, bottom=60)
```

### См. также
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
