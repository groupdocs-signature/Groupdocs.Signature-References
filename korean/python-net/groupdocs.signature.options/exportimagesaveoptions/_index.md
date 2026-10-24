---
title: "ExportImageSaveOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서를 이미지로 내보내기 위한 저장 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

문서를 이미지로 내보내기 위한 저장 옵션을 나타냅니다.

ExportImageSaveOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | ExportAsImageSaveOptions 클래스를 기본값으로 새 인스턴스를 초기화합니다. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | 지정된 파일 형식으로 ExportAsImageSaveOptions의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | 이미지 테두리 설정. 기본값으로 이 값은 설정되지 않습니다. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | 각 페이지를 내보내는 플래그. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | 내보낸 이미지의 열 수. 이미지를 한 줄에 배치해야 할 경우 이 속성을 사용하십시오. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | 내보낼 문서 페이지 번호(최소값은 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | 서명할 페이지를 지정하는 옵션. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | 문서 페이지가 TIFF 이미지의 서로 다른 프레임에 배치됩니다. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 출력 파일 경로에 확장자가 없을 때 자동으로 추가할지 여부를 결정하는 플래그입니다. 기본값은 False입니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 서명된 문서의 파일 형식입니다. (상속됨: [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 새 출력 파일로 기존 파일을 덮어쓸지 여부를 나타내는 플래그입니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 저장된 서명 문서를 보호하는 데 사용되는 비밀번호입니다. 이미지 문서에서는 지원되지 않습니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 서명된 문서를 보호된 상태로 저장할 때 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)의 비밀번호를 사용할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. 이미지 문서에서는 지원되지 않습니다. (상속됨: [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
