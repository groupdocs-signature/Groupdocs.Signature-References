---
title: "custom_sign_hash 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "사용자 정의 서명 구현을 사용하여 주어진 해시를 서명합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

사용자 정의 서명 구현을 사용하여 주어진 해시를 서명합니다.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signable_hash | `list[int]` | 서명될 해시 값. |
| hash_algorithm | `HashAlgorithm` | 해시를 생성하는 데 사용되는 해시 알고리즘. |
| signature_context | `SignatureContext` | 추가 서명 관련 옵션을 제공하는 컨텍스트. |

**Returns:** bytes: The signed hash as bytes.

### 또 보기
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
