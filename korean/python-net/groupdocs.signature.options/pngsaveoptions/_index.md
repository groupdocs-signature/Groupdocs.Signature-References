---
title: "PngSaveOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이미지 문서에 대한 PNG 저장 옵션입니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

이미지 문서에 대한 PNG 저장 옵션입니다.

PngSaveOptions 유형은 다음 멤버를 제공합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | PngSaveOptions를 기본값으로 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | 비트 깊이. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | `PngColorType` 의 유형. |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | 0-9 범위의 png 이미지 압축 레벨이며, 9는 최대 압축, 0은 저장 모드입니다. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | PNG 파일 저장 과정에서 사용되는 필터 유형 `PngFilterType`. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | PNG가 점진적으로 저장되는지 여부를 나타내는 progressive 플래그. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 출력 파일 경로에 확장자가 없을 때 자동으로 추가할지 여부를 결정하는 플래그입니다. 기본값은 False입니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 서명된 문서의 파일 형식입니다. (상속됨: [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 새 출력 파일로 기존 파일을 덮어쓸지 여부를 나타내는 플래그입니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 저장된 서명 문서를 보호하는 데 사용되는 비밀번호입니다. 이미지 문서에서는 지원되지 않습니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 서명된 문서를 보호된 상태로 저장할 때 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)의 비밀번호를 사용할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. 이미지 문서에서는 지원되지 않습니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
