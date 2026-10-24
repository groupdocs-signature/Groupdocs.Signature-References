---
title: "log_level 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "로그 레벨 플래그는 SignatureSettings.Logger에 전달되는 메시지 종류를 결정합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

로그 레벨 플래그로, 어떤 종류의 메시지가 [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/)에 전달되는지 결정합니다.

값은 결합할 수 있는 `LogLevel` 플래그 집합이며, 예를 들어 `LogLevel.Error | LogLevel.Warning`와 같습니다. `LogLevel.None`은 아무 것도 기록하지 않습니다. 기본값은 `LogLevel.All`이며, 오류, 경고 및 추적을 기록합니다.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### 또 보기
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
