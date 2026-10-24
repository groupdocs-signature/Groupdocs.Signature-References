---
title: "data_encryption 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "IDataEncryption의 구현은 이 옵션 컬렉션의 모든 메타데이터 서명을 암호화하는 데 사용됩니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

이 옵션 컬렉션의 모든 메타데이터 서명을 암호화하는 데 사용되는 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) 구현입니다.

설정된 경우, 추가된 모든 서명은 기본적으로 이 암호화를 사용하지만 자체 DataEncryption이 할당된 경우는 제외됩니다.

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
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
