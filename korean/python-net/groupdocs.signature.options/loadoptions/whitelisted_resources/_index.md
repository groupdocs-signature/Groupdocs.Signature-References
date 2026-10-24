---
title: "whitelisted_resources 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "LoadOptions.SkipExternalResources가 true일 때에도 로드되는 외부 리소스 주소 조각들의 목록입니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

[`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/)가 true인 경우에도 로드되는 외부 리소스의 주소 조각 목록입니다. 기본값은 빈 리스트입니다.

리소스는 전체 주소에 조각 중 하나가 포함될 때 로드됩니다. 비교는 대소문자를 구분하지 않으며, 빈 조각은 무시됩니다. `\"https://cdn.example.com/images/\"`와 같은 긴 조각을 선호하세요: 짧은 조각도 해당 조각을 포함하는 다른 주소와 일치할 수 있습니다.

이 속성을 `None`으로 설정하면 목록이 비워집니다. [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/)가 false인 경우에는 목록이 영향을 주지 않으며, 이때는 모든 외부 리소스가 로드됩니다.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### 또 보기
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
