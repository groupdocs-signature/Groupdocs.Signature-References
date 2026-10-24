---
title: "DigitalVBA 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "스프레드시트 VBA 프로젝트에 대한 디지털 서명을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

스프레드시트 VBA 프로젝트에 대한 디지털 서명을 나타냅니다.

스프레드시트 문서 형식(`Xlsm` 또는 `Xltm` 등)에서 VBA 프로젝트에 서명할 수 있는 기능을 제공합니다. 여러 개의 [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) 확장이 [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)에 추가된 경우, 서명 시 첫 번째만 사용됩니다.

DigitalVBA 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | 인증서 파일을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | 인증서 스트림을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | 이 객체의 복사본을 가져옵니다. ([`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | `CertificateStream`이 지정되지 않은 경우에만 사용되는 디지털 인증서 파일 경로입니다. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | 디지털 인증서 스트림입니다. 이 속성이 지정되면 항상 CertificateFilePath 대신 사용됩니다. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | 서명 주석입니다. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | 디지털 인증서의 비밀번호입니다. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | VBA 프로젝트만 서명할지 여부를 결정하는 설정입니다. True인 경우 스프레드시트 문서 자체는 서명되지 않고 VBA 프로젝트만 서명됩니다. |

### 예시

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # 스프레드시트 내 매크로 서명
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # VBA 프로젝트를 디지털 서명하기 위한 확장 추가
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # VBA 프로젝트 서명 부분이 추가되었는지 확인
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### 또 보기
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
