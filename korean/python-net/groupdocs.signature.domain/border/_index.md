---
title: "Border 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "테두리 모양을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

테두리 모양을 나타냅니다.

Border 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | IClonable 인터페이스를 구현합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | 서명의 테두리 색상. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | 서명 테두리 스타일. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | 서명 테두리 투명도는 0.0(불투명)에서 1.0(투명)까지이며, 기본값은 0(불투명)입니다. |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | 테두리 가시성. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | 서명 테두리 두께. |

### 예시

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
`Border`를(을) 사용하는 작업 가이드:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
