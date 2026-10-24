---
title: "ImageSearchOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이미지 서명에 대한 검색 옵션을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

이미지 서명에 대한 검색 옵션을 나타냅니다.

자세히 보기:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

ImageSearchOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | 기본값으로 ImageSearchOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | 검색 기준에 대한 이미지의 최대 크기(바이트). |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | 검색 중 고려되는 이미지 데이터의 최소 크기(바이트). 0이 아닌 값은 최소 크기를 지정합니다; 기본값은 0이며 검색 결과에 영향을 주지 않습니다. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | 서명의 이미지 콘텐츠가 반환되는지 여부를 결정하는 플래그. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | return_content 속성이 활성화된 경우 반환되는 이미지 콘텐츠의 파일 형식. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 각 문서 페이지에서 검색할지 여부를 나타내는 플래그입니다. 기본값은 True입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 검색을 위한 문서 페이지 번호(옵션). ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 서명 검색을 위한 페이지를 지정하는 옵션입니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 문서 레이아웃에서 도형 위치를 반환할지 여부를 나타내는 플래그입니다. Word 문서에서만 사용할 수 있습니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` 로 표시된 서명만 반환하는 플래그입니다. 기본값은 `False`이며, 이는 지정된 기준에 맞는 모든 서명이 반환됨을 의미합니다. ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)에서 상속됨) |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
