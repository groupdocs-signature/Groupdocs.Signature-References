---
title: "save_document_on_empty_update 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "Update 메서드에 업데이트할 서명이 없을 때 원본 문서를 다시 저장할지 여부를 결정하는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

`Update` 메서드에 업데이트할 서명이 없을 때 소스 문서를 다시 저장할지 여부를 결정하는 플래그입니다.

`True`(기본값)로 설정하면 서명이 업데이트되지 않아도 문서가 해당 히스토리 프로세스 로그(날짜 및 작업 유형)와 함께 저장됩니다. `False`로 설정하면 원본 문서는 전혀 수정되지 않습니다.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### 또 보기
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
