---
title: "save_document_on_empty_delete 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "Delete 메서드에 제거할 영향을 받은 서명이 없을 때 소스 문서를 다시 저장할지 여부를 결정하는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Delete 메서드에 제거할 영향을 받은 서명이 없을 때 소스 문서를 다시 저장할지 여부를 결정하는 플래그입니다.

True(기본값)인 경우 서명이 제거되지 않아도 문서가 히스토리 로그(날짜 및 작업 유형)와 함께 저장됩니다; False인 경우 원본 문서는 변경되지 않은 채로 남습니다.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### 또 보기
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
