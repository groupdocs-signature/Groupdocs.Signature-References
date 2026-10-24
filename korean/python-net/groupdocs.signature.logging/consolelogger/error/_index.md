---
title: "error 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "콘솔에 오류 메시지를 기록합니다."
type: docs
url: /ko/python-net/groupdocs.signature.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

콘솔에 오류 메시지를 기록합니다.

Error 로그 메시지는 애플리케이션 흐름에서 복구할 수 없는 이벤트에 대한 정보를 제공합니다.

```python
def error(self, message, ex):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| message | `str` | error 메시지. |
| ex | `Exception` | 예외. |

| 발생 | 설명 |
| :- | :- |
| `ValueError` | `ex`가 None인 경우. |

### 또 보기
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
