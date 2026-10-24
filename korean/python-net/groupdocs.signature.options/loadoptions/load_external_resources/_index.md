---
title: "load_external_resources 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서가 외부 리소스를 로드할지 여부를 결정하는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

문서가 외부 리소스를 로드할지 여부를 결정하는 플래그입니다. 이 속성은 더 이상 사용되지 않으며, 반대 의미를 갖는 [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/)를 대신 사용하십시오.

LoadExternalResources = True는 `SkipExternalResources` = False와 동일하고, LoadExternalResources = False는 `SkipExternalResources` = True와 동일합니다. 기본값은 False이며, 이는 명시적으로 허용되지 않는 한 외부 리소스가 로드되지 않음을 의미합니다.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### 또 보기
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
