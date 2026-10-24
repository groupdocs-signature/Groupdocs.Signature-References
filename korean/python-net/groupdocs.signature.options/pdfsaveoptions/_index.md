---
title: "PdfSaveOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "PDF 문서에 대한 저장 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

PDF 문서에 대한 저장 옵션을 나타냅니다.

PdfSaveOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | PdfSaveOptions의 새 인스턴스를 기본값으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | PdfSaveOptions의 새 인스턴스를 지정된 출력 파일 형식으로 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | PdfSaveOptions의 새 인스턴스를 덮어쓰기 플래그와 함께 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | PdfSaveOptions의 새 인스턴스를 지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | 서명된 문서의 파일 형식입니다. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | 인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한입니다. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | 권한 설정을 변경하는 데 필요한 권한 비밀번호(주 비밀번호)입니다. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 출력 파일 경로에 확장자가 없을 때 자동으로 추가할지 여부를 결정하는 플래그입니다. 기본값은 False입니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 새 출력 파일로 기존 파일을 덮어쓸지 여부를 나타내는 플래그입니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 저장된 서명 문서를 보호하는 데 사용되는 비밀번호입니다. 이미지 문서에서는 지원되지 않습니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 서명된 문서를 보호된 상태로 저장할 때 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)의 비밀번호를 사용할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. 이미지 문서에서는 지원되지 않습니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
