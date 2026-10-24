---
title: "문서 페이지 미리보기 생성"
linkTitle: "Generate document pages preview"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 항목에서는 .NET을 통해 Python용 GroupDocs.Signature로 다양한 옵션을 사용하여 문서 페이지를 이미지로 미리 보는 방법을 설명합니다."
type: docs
url: /ko/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
다음은 GroupDocs.Signature를 사용하여 문서 미리보기를 생성하는 단계입니다:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

create 함수가 반환하는 스트림은 페이지 이미지가 기록되는 즉시 자동으로 닫힙니다: 파일이 닫히고, `io.BytesIO`가 이미 완전한 이미지를 보유합니다. 각 완료된 이미지를 처리하거나 직접 리소스를 정리해야 하는 경우, 추가 인수로 release 함수를 전달하십시오 (참조: [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature는 각 페이지마다 create 함수를 한 번 호출하고 반환된 스트림에 페이지 이미지를 기록합니다: 쓰기 가능한 파일 객체, `io.BytesIO` 또는 .NET 스트림. `page_data` 매개변수는 `page_number`, 문서의 `file_name`, 그리고 `preview_format`을 포함하는 [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) 객체입니다.

페이지 번호는 0부터 시작합니다: `page_data.page_number`는 문서 첫 페이지에 대해 `0`입니다.

```python
def create_page_stream(page_data):
    # 0부터 시작: preview_page_0.png가 첫 페이지입니다
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

아카이브를 미리볼 때, 함수는 그 안에 있는 모든 문서의 페이지마다 호출됩니다. 각 문서마다 페이지 번호가 다시 `0`부터 시작하므로, 이미지를 이름 지정할 때 `page_data.file_name`도 사용하십시오.

## ReleasePageStream delegate implementation

release 함수는 동일한 `page_data`와 create 함수가 반환한 동일한 객체를 받습니다. 호출 시점에는 이미지가 완성되어 있습니다.

```python
def release_page_stream(page_data, page_stream):
    # page_stream은 create_page_stream이 반환한 객체입니다
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs "generate_document_preview" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # 페이지 번호는 0부터 시작합니다: preview_page_0.png가 첫 페이지입니다
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # 미리보기 옵션 객체 생성: 페이지당 하나의 PNG 이미지
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # 미리보기 생성
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "generate-document-preview-outputs.zip" >}}
```text
preview_page_0.png (75 KB)
preview_page_1.png (64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview/generate-document-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Generate document preview from stream with custom stream releasing delegate

이 예제는 스트림에서 문서를 읽고 페이지 이미지를 메모리에 보관합니다: create 함수는 `io.BytesIO`를 반환하고, release 함수는 완전한 이미지가 채워진 이를 받습니다.

{{< tabs "generate_document_preview_from_stream" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # 파일에 쓰는 대신 각 페이지 이미지를 메모리에 보관합니다
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream은 위에서 반환된 BytesIO이며, 이미 전체 이미지를 보유하고 있습니다
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # 두 함수를 모두 사용하여 미리보기 옵션 객체를 생성합니다
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # 미리보기 생성
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "generate-document-preview-from-stream.txt" >}}
```text
Page 0: 276044 bytes of JPEG
Page 1: 224194 bytes of JPEG
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_from_stream/generate-document-preview-from-stream.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate preview of particular pages

일부 페이지만 미리 보려면 `page_numbers`를 설정하십시오. 번호는 0부터 시작하므로 `[1]`은 두 번째 페이지를 선택합니다.

{{< tabs "generate_document_preview_of_selected_pages" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}.png", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_of_selected_pages():
    with Signature("sample.pdf") as signature:
        preview_options = PreviewOptions(create_page_stream, release_page_stream)
        # 페이지 번호는 0부터 시작합니다: [1]은 두 번째 페이지입니다.
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "preview_page_1.png" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

기본 해상도는 96 DPI입니다. 해상도를 [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/)의 세 번째 인수로 전달하거나 `resolution` 속성을 설정하십시오.

{{< tabs "generate_document_preview_with_resolution" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}_150dpi.jpg", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_with_resolution():
    with Signature("sample.pdf") as signature:
        resolution = 150
        # 미리 보기 옵션 객체를 생성합니다: 기본값 96 대신 150 DPI
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # 미리보기 생성
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab "generate-document-preview-with-resolution-outputs.zip" >}}
```text
preview_page_0_150dpi.jpg (495 KB)
preview_page_1_150dpi.jpg (425 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_with_resolution/generate-document-preview-with-resolution-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 온라인 앱을 사용할 수 있습니다.
