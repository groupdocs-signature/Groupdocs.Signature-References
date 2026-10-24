---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "지정된 매개변수로 대칭 알고리즘을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

지정된 매개변수로 대칭 알고리즘을 초기화합니다.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | 대칭 알고리즘 유형 지정 |
| key | `str` | 암호화 키 |
| salt | `str` | 암호화를 위한 암호 구문 |

## __init__ {#algorithm_type-key}

매개변수와 기본 암호 구문으로 대칭 알고리즘을 초기화합니다.

```python
def __init__(self, algorithm_type, key):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | 암호화 알고리즘 유형 |
| key | `str` | 암호화 키 |

### 또 보기
* class [`SymmetricEncryptionAttribute`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/)
