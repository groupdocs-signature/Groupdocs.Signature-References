---
title: "Padding 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "요소와 연관된 패딩 또는 마진 정보를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

요소와 연관된 패딩 또는 마진 정보를 나타냅니다.

Padding 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Padding 클래스의 새 인스턴스를 0값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Padding 클래스의 새 인스턴스를 제공된 패딩 크기를 모든 가장자리에 적용하여 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Padding 클래스의 새 인스턴스를 제공된 패딩 크기를 사용하여 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | 이 객체의 복사본을 가져옵니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | 모든 가장자리에 대한 패딩 값입니다. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | 아래쪽 가장자리에 대한 패딩 값입니다. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | 오른쪽 및 왼쪽 가장자리에 대한 결합된 패딩 값입니다. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | 왼쪽 가장자리에 대한 패딩 값입니다. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | 오른쪽 가장자리에 대한 패딩 값입니다. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | 위쪽 가장자리에 대한 패딩 값입니다. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | 위쪽 및 아래쪽 가장자리에 대한 결합된 패딩 값입니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | 패딩이 없는 Padding 객체를 제공합니다. |

### 예시

```python
from groupdocs.signature.domain import Padding

# 모든 면에 5 단위의 균일한 패딩
uniform = Padding(5)

# 오른쪽 및 아래쪽에 대한 특정 패딩
custom = Padding(right=40, bottom=60)
```

### Guides
`Padding`을 사용하는 작업 가이드:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
