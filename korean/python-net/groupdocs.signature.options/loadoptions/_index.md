---
title: "LoadOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "LoadOptions 클래스는 문서를 서명하기 위해 열 때 추가 옵션(예: password)을 지정할 수 있게 합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

LoadOptions 클래스는 문서를 서명하기 위해 열 때 추가 옵션(예: password)을 지정할 수 있게 합니다.

파일이 암호화된 경우 `password` 속성을 문서 비밀번호로 설정합니다.

LoadOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | 지정된 파일 유형으로 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | 로드 옵션과 연결된 파일 유형이며, 기본값은 [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/)입니다. |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | 문서가 외부 리소스를 로드할지 여부를 결정하는 플래그입니다. 이 속성은 더 이상 사용되지 않으며, 반대 의미를 갖는 [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/)를 대신 사용하십시오. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | 보호된 문서를 열고 서명된 문서를 보호된 상태로 저장하는 데 사용되는 비밀번호입니다. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | 인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한입니다. PDF 문서에만 적용됩니다. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | 문서가 외부 리소스를 로드하지 않도록 하는 플래그입니다. 기본값은 True이며, [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/)와 일치하는 경우를 제외하고 외부 리소스는 로드되지 않습니다. |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/)가 true인 경우에도 로드되는 외부 리소스의 주소 조각 목록입니다. 기본값은 빈 리스트입니다. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
