---
title: "빠른 시작 가이드"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "가상 환경을 설정하고, groupdocs-signature-net을 설치한 후, 세 가지 최소 예제를 실행합니다: 텍스트 서명으로 PDF에 서명하고, 서명을 검색하며, 서명을 검증합니다."
type: docs
url: /ko/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


이 가이드는 GroupDocs.Signature for Python via .NET을 설정하고 사용을 시작하는 방법에 대한 간략한 개요를 제공합니다. 이 라이브러리는 몇 줄의 코드만으로 PDF, Word, Excel, PowerPoint, OpenDocument 및 이미지 파일에 전자 서명을 추가, 검색, 검증, 업데이트 및 제거합니다.

## Prerequisites

진행하려면 다음이 준비되어 있는지 확인하십시오:

1. [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/) 항목에 설명된 대로 구성된 환경. Linux 및 macOS에서는 몇 가지 시스템 패키지가 포함됩니다.
2. 선택적으로, 모든 제품 기능을 테스트하기 위한 [Temporary License](https://purchase.groupdocs.com/temporary-license/). 라이선스가 없으면 라이브러리는 평가 모드로 작동하며, 최대 두 페이지까지 문서를 처리하고 서명된 각 페이지에 평가 라인을 추가합니다. 자세한 내용은 [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/)를 참조하십시오.

## Set Up Your Development Environment

모범 사례를 위해 가상 환경을 사용하여 종속성을 관리하십시오. 자세한 내용은 [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) 가이드를 확인하세요.

### Create and Activate a Virtual Environment

가상 환경을 생성합니다:

{{< tabs "create-venv">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

활성화합니다:

{{< tabs "activate-venv">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs "install-package">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

버전을 고정하고 PyPI에 접근할 수 없을 때 설치하는 방법은 [Installation](/signature/python-net/guides/installation/)을 참조하세요.

## Example 1: Sign a PDF with a Text Signature

문서를 열고, 서명을 [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/)로 설명한 뒤, 서명된 복사본을 저장합니다.

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # 문서를 엽니다; with 블록은 종료될 때 파일을 해제합니다.
    with Signature("sample.pdf") as signature:
        # 첫 페이지의 왼쪽 및 위쪽 가장자리에서 100픽셀 떨어진 텍스트 서명
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 서명하고 결과를 새 파일에 저장합니다; 원본은 변경되지 않습니다.
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf`은(는) 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf)를 클릭하세요.

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

문서가 이미 가지고 있는 서명을 찾습니다. `search`는 찾고자 하는 서명 유형별로 하나씩 검색 옵션 목록을 받아 `result.signatures`에 반환합니다.

{{< tabs "search_document_for_signatures">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 각 페이지에서 텍스트 서명을 찾습니다.
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf`은(는) 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf)를 클릭하세요.

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

문서가 기대하는 서명을 가지고 있는지 확인합니다. 정확히 이 텍스트와 일치하는 텍스트 서명이 발견되면 검증에 성공합니다.

{{< tabs "verify_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf`은(는) 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf)를 클릭하세요.

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

각 예제를 샘플 파일 옆에 있는 별도의 `.py` 파일로 저장합니다. 폴더 구조는 다음과 비슷해야 합니다:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

해당 폴더에서 예제를 실행합니다:

{{< tabs \"run-the-app\">}}
{{< tab "Windows" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

작업이 끝나면 `deactivate`를 실행하거나 셸을 닫아 가상 환경을 비활성화합니다.

## Apply a License

`GROUPDOCS_LIC_PATH` 환경 변수를 라이선스 파일의 전체 경로로 설정하면 `groupdocs.signature`를 가져올 때 라이선스가 자동으로 적용됩니다. 코드는 필요하지 않습니다. 또는 다른 호출 전에 한 번 코드에서 적용할 수도 있습니다:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

이 [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) 항목에서는 두 가지 방법과 사용량 기반 라이선스에 대해 다룹니다.

## Next Steps

기본을 마친 후, 추가 리소스를 살펴보세요:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
