---
title: "JpegSaveOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이미지 문서에 대한 JPEG 저장 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

이미지 문서에 대한 JPEG 저장 옵션을 나타냅니다.

JpegSaveOptions 유형은 다음 멤버를 제공합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | JpegSaveOptions를 기본값으로 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | 무손실 JPEG 이미지의 채널당 비트 수. 지원되는 값은 채널당 2비트에서 8비트까지입니다. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | JPEG 이미지의 색상 유형. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | JPEG 파일 주석. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | 압축 유형. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | 이미지 품질. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | `JpegOptions.BitsPerChannel` 의 n비트 값에 8비트 값을 맞추기 위해 사용되는 샘플 반올림 모드. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 출력 파일 경로에 확장자가 없을 때 자동으로 추가할지 여부를 결정하는 플래그입니다. 기본값은 False입니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 서명된 문서의 파일 형식입니다. (상속됨: [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 새 출력 파일로 기존 파일을 덮어쓸지 여부를 나타내는 플래그입니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 저장된 서명 문서를 보호하는 데 사용되는 비밀번호입니다. 이미지 문서에서는 지원되지 않습니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 서명된 문서를 보호된 상태로 저장할 때 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)의 비밀번호를 사용할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. 이미지 문서에서는 지원되지 않습니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
