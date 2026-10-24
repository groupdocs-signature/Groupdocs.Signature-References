---
title: "DigitalVerifyOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서의 디지털 서명을 검증하기 위한 옵션을 보관합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

문서의 디지털 서명을 검증하기 위한 옵션을 보관합니다.

자세히 알아보기

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

DigitalVerifyOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | 기본값으로 DigitalVerifyOptions 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | 지정된 디지털 인증서 파일 경로로 DigitalVerifyOptions 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | 지정된 인증서 스트림으로 DigitalVerifyOptions 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | 인증서 파일 경로나 스트림에서 가져온 X509Certificate2 인증서. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | 디지털 인증서의 파일 경로. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | 디지털 인증서의 스트림. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | 검증할 디지털 서명의 주석. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | 검증할 서명 연락처. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | 검증할 인증서의 발급자 이름. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | 검증할 서명 위치. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | 필요한 경우 디지털 인증서의 비밀번호. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | 검증할 디지털 서명의 이유. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | 검증할 디지털 서명의 날짜 및 시간 범위 시작. None 값은 무시됩니다. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | 검증할 디지털 서명의 날짜 및 시간 범위 종료. null 값은 무시됩니다. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | 검증할 인증서의 주체 구분 이름; 검증은 서명의 주체 이름이 이 대소문자 구분 값과 포함되는지 또는 일치하는지 확인합니다. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 각 문서 페이지를 검증할지 여부를 나타내는 플래그. 기본값은 True입니다. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 대체 서명 옵션 검증을 위한 추가 확장자. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 유효한 속성 플래그. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 검증할 문서 페이지 번호; 설정되지 않으면 문서의 모든 페이지가 첫 번째 발생에 대해 검증됩니다(최소값은 1). (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 검증할 페이지를 지정하기 위한 페이지 옵션입니다. (상속됨: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | 머리글/바닥글에 서명을 검증하는 데 사용되는 문서 레이아웃의 도형 위치입니다. (상속됨: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
