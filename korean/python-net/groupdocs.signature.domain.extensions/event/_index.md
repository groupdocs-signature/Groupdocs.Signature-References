---
title: "Event 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "표준 QR 코드 이벤트 세부 정보를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

표준 QR 코드 이벤트 세부 정보를 나타냅니다.

Event 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Event 인스턴스를 기본값으로 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | 이 Event를 다른 Event와 동등성 비교합니다. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Event의 해시 코드를 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | 이벤트의 설명. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | 이벤트 종료 날짜 및 시간. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | 이벤트 위치. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | 이벤트 시작 날짜 및 시간. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | 이벤트 제목. |

### 예시

```python
from datetime import datetime
from groupdocs.signature.domain.extensions import Event

event_qr = Event()
event_qr.title = "Meeting"
event_qr.description = "Productivity issues"
event_qr.location = "room 408"
event_qr.start_date = datetime(2022, 6, 19, 15, 30, 0)
event_qr.end_date = datetime(2022, 6, 19, 17, 0, 0)
```

### 또 보기
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
