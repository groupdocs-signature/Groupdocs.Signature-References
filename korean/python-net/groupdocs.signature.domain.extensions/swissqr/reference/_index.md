---
title: "reference 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "채권자 결제 참조."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

채권자 결제 참조.

SwissQR IBAN에 대해 필수입니다 (CHxx30000xxxxxx부터 CHxx31999xxxxx까지의 범위에 해당하는 IBAN). 지정된 경우, 참조는 유효한 SwissQR 참조(ISR 참조 양식에 해당) 또는 ISO 11649("RFxxxx")에 따른 유효한 채권자 참조여야 합니다. 두 경우 모두 서식을 위한 공백을 포함할 수 있습니다.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### 또 보기
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
