---
title: "SaveOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서를 서명하기 위해 저장할 때 추가 옵션(예: password)을 지정합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

문서를 서명하기 위해 저장할 때 추가 옵션(예: password)을 지정합니다.

SaveOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | 기본값으로 SaveOptions 클래스의 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | 지정된 출력 유형 및 덮어쓰기 플래그로 SaveOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 출력 파일 경로에 확장자가 없을 때 자동으로 추가할지 여부를 결정하는 플래그입니다. 기본값은 False입니다. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 새 출력 파일로 기존 파일을 덮어쓸지 여부를 나타내는 플래그입니다. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 저장된 서명 문서를 보호하는 데 사용되는 비밀번호입니다. 이미지 문서에서는 지원되지 않습니다. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 서명된 문서를 보호된 상태로 저장할 때 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)에서 비밀번호를 사용할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. 이미지 문서에서는 지원되지 않습니다. |

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
