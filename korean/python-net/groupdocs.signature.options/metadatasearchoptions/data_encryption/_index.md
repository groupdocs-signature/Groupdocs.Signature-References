---
title: "data_encryption 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 옵션 컬렉션 내의 모든 메타데이터 서명을 복호화하는 데 사용되는 IDataEncryption 구현."
type: docs
url: /ko/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

이 옵션 컬렉션 내의 모든 메타데이터 서명을 복호화하는 데 사용되는 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) 구현입니다.

설정된 경우, 자체 DataEncryption이 할당되지 않은 모든 발견된 서명은 기본적으로 이 암호화를 사용합니다.

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### 또 보기
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
