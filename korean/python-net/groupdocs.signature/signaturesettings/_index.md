---
title: "SignatureSettings 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "Signature 동작을 맞춤화하기 위한 설정을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

[`Signature`](/signature/python-net/groupdocs.signature/signature/) 동작을 사용자 정의하기 위한 설정을 나타냅니다.

SignatureSettings 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | 기본값으로 기본 SignatureSettings 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Logger 구현을 사용하여 기본 SignatureSettings 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | 문서 처리 중에 사용되는 기본 문화권. 기본값은 "en-US"입니다. |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | 표준 문서 메타데이터 서명(예: Author, Owner, creation date, modified date)이 메타데이터 목록에 포함되는지 여부를 나타내는 플래그입니다. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | 로그 레벨 플래그로, 어떤 종류의 메시지가 [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/)에 전달되는지 결정합니다. |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | 로깅(Errors, Warnings, Traces)에 사용되는 로거 구현입니다. [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Delete 메서드에 제거할 영향을 받은 서명이 없을 때 소스 문서를 다시 저장할지 여부를 결정하는 플래그입니다. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | `Update` 메서드에 업데이트할 서명이 없을 때 소스 문서를 다시 저장할지 여부를 결정하는 플래그입니다. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | 삭제된 서명이 문서 정보 결과에 포함되는지 여부를 결정하는 플래그입니다. 각 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)에는 삭제 여부를 나타내는 `Deleted` 플래그가 있습니다. |

### 또 보기
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
