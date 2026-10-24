---
title: "allow_not_yet_valid 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "유효 기간이 아직 시작되지 않은 인증서로 서명하도록 허용하는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

유효 기간이 아직 시작되지 않은 인증서로 서명하도록 허용하는 플래그입니다. 기본값은 False이며, 이러한 인증서로 서명하면 `GroupDocsSignatureException`이 발생하고 문서는 서명되지 않습니다.

검증자는 인증서가 유효해지기 전에 만든 서명을 유효하지 않다고 보고합니다. 이러한 인증서는 일반적으로 나중 날짜에 발급되었거나 컴퓨터 시계가 잘못된 경우입니다. 이 플래그가 True이면 문서가 서명되고, [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)에 설정된 로거에 경고가 기록됩니다.

인증서는 UTC 기준 현재 시간과 비교됩니다. 이 플래그는 유효 기간이 끝난 인증서를 제어하는 [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/)와 동일한 인증서에 적용됩니다.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### 또 보기
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
