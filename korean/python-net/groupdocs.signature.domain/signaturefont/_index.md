---
title: "SignatureFont 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "SignatureFont 클래스는 텍스트 서명을 위한 글꼴 속성을 지정합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

SignatureFont 클래스는 텍스트 서명을 위한 글꼴 속성을 지정합니다.

SignatureFont 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | SignatureFont을 기본값으로 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | 글꼴 굵게 스타일. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | 글꼴 패밀리 이름. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | 글꼴 이탤릭 스타일. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | 글꼴 크기. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | 글꼴 취소선 스타일. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | 글꼴 밑줄 스타일. |

### 예시

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
`SignatureFont`을 사용하는 작업 가이드:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 또 보기
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
