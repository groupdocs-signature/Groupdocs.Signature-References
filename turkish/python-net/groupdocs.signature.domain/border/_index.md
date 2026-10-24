---
title: "Border sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Sınır görünümünü temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Sınır görünümünü temsil eder.

Border türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | IClonable arabirimini uygular. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | İmzanın kenar rengi. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | İmza kenar stili. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | İmza kenar şeffaflığı, 0.0 (opak) ile 1.0 (şeffaf) arasında değişir, varsayılan değer 0 (opak)dır. |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | Kenarın görünürlüğü. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | İmza kenarının kalınlığı. |

### Örnek

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
`Border` kullanan görev kılavuzları:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
