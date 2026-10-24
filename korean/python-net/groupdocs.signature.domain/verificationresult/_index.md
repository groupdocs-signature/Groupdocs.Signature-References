---
title: "VerificationResult 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "검증 프로세스 결과를 보관하는 인스턴스를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

검증 프로세스 결과를 보관하는 인스턴스를 나타냅니다.

VerificationResult 형식은 다음 멤버를 노출합니다:

### 속성
| 속성 | 설명 |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | 대상 문서 크기. 검증을 위해 이 변수는 항상 0을 포함합니다. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | 검증 과정에서 실패한 서명 목록. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | 검증 결과; 검증 과정이 성공하면 True, 그렇지 않으면 False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | 프로세스 실행 시간(밀리초). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | 원본 문서 크기(바이트). |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | 성공적으로 검증된 서명 목록 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | 처리된 서명의 총 수. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
