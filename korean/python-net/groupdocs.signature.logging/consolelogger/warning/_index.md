---
title: "warning 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "경고 메시지를 콘솔에 출력합니다."
type: docs
url: /ko/python-net/groupdocs.signature.logging/consolelogger/warning/
is_root: false
weight: 1070
---


## warning {#message}

콘솔에 경고 메시지를 기록합니다. 경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 및 복구 가능한 이벤트에 대한 정보를 제공합니다.

```python
def warning(self, message):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| message | `str` | warning 메시지. |

| 발생 | 설명 |
| :- | :- |
| `ValueError` | 만약 `message`가 None이면. |

### 또 보기
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
