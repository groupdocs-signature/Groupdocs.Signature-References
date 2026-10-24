---
title: "verify 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "주어진 VerifyOptions 데이터로 문서 서명을 검증합니다."
type: docs
url: /ko/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

주어진 VerifyOptions 데이터로 문서 서명을 검증합니다.

GroupDocs.Signature를 사용한 전자 서명 문서 검증에 대한 자세한 내용:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| verify_options | `VerifyOptions` | 서명 검증 옵션. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options-predicate}

제공된 검증 옵션을 사용하여 문서 서명을 검증하고 지정된 술어에 따라 결과를 필터링합니다.

자세히 알아보기

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| verify_options | `VerifyOptions` | 서명 검증 옵션. |
| predicate | `Func[BaseSignature, bool]` | 검증해야 할 서명을 결정하는 필터 프레디케이트. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options, lambda s: True)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list}

VerifyOptions 데이터 목록으로 문서 서명을 검증합니다.

GroupDocs.Signature를 사용한 전자 서명 문서 검증에 대한 자세한 내용: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | 서명 검증 옵션 컬렉션. `GroupDocs.Signature.Options.VerifyOptionsCollection` 인스턴스. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list-predicate}

제공된 검증 옵션을 사용하여 문서 서명을 확인하고, 주어진 프레디케이트로 결과를 필터링합니다.

이 메서드는 먼저 검증 옵션에 일치하는 서명을 검색하고, 프레디케이트를 사용해 필터링한 다음, 필터링된 서명만 검증합니다.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | 서명 검증 옵션 컬렉션. |
| predicate | `Func[BaseSignature, bool]` | 검증해야 할 서명을 결정하는 필터 프레디케이트. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify([options], lambda s: s.text == "John Smith")
        print(f"Document is signed by John Smith: {result[0].is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
