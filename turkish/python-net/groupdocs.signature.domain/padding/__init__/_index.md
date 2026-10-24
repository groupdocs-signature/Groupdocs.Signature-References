---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Padding sınıfının yeni bir örneğini sıfır değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Padding sınıfının yeni bir örneğini sıfır değerlerle başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature.domain import Padding

# Varsayılan (sıfır) değerlerle bir dolgu nesnesi oluşturun
default_padding = Padding()
```

## __init__ {#all}

Padding sınıfının yeni bir örneğini tüm kenarlar için sağlanan dolgu boyutunu kullanarak başlatır.

```python
def __init__(self, all):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| all | `int` | Tüm kenarlar için dolgu amaçlı kullanılacak ölçü birimlerinin sayısı. |

### Örnek

```python
# Tüm kenarlarda 5 birimlik eşit dolgu
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Padding sınıfının yeni bir örneğini sağlanan dolgu boyutlarını kullanarak başlatır.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| left | `int` | Sol dolgu boyutu. |
| right | `int` | Sağ dolgu boyutu. |
| top | `int` | Üst dolgu boyutu. |
| bottom | `int` | Alt dolgu boyutu. |

### Örnek

```python
from groupdocs.signature.domain import Padding

# Sağ ve alt kaydırmalarla bir dolgu oluşturun
margin = Padding(right=40, bottom=60)
```

### Ayrıca Bakınız
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
