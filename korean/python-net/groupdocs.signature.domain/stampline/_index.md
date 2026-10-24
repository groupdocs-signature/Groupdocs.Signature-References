---
title: "StampLine 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "스탬프 선 속성을 지정합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

스탬프 선 속성을 지정합니다.

StampLine 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | 기본값으로 StampLine을 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | 서명의 배경 색상. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | 스탬프 라인 텍스트의 글꼴. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | 스탬프의 줄 높이. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | 스탬프 라인의 내부 테두리. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | 스탬프 라인의 외부 테두리. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | 스탬프 라인의 텍스트. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | 텍스트의 하단 의도. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | 서명의 텍스트 색상. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | 텍스트 반복 유형. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | 스탬프 라인의 가시성. |

### 예시

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# 스탬프 라인 만들기
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
