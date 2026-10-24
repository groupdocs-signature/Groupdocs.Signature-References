---
title: "SignatureFont sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "SignatureFont sınıfı, metin imzası için yazı tipi özelliklerini belirtir."
type: docs
url: /tr/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

SignatureFont sınıfı, metin imzası için yazı tipi özelliklerini belirtir.

SignatureFont türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | SignatureFont'ı varsayılan değerlerle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | Yazı tipinin kalın stili. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | Yazı tipi ailesi adı. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | Yazı tipinin italik stili. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | Yazı tipi boyutu. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | Yazı tipinin üstü çizili stili. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | Yazı tipinin alt çizgi stili. |

### Örnek

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
`SignatureFont` kullanan görev kılavuzları:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
