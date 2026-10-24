---
title: "include_standard_metadata_signatures 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "표준 문서 메타데이터 서명(예: Author, Owner, creation date, modified date)이 메타데이터 목록에 포함되는지 여부를 나타내는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

표준 문서 메타데이터 서명(예: Author, Owner, creation date, modified date)이 메타데이터 목록에 포함되는지 여부를 나타내는 플래그입니다.

False(기본값)로 설정하면 GetDocumentInfo는 이러한 메타데이터 서명을 포함하지 않습니다. True로 설정하면 문서 정보에 표준 메타데이터 서명이 포함됩니다.

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### 또 보기
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
