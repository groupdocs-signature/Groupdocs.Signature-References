---
title: "텍스트 전자 서명 검색"
linkTitle: "Texts"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 항목에서는 .NET API를 통해 Python용 GroupDocs.Signature를 사용하여 문서 페이지 내에서 텍스트 전자 서명을 검색하는 방법을 설명합니다."
type: docs
url: /ko/python-net/guides/search-for-text-e-signatures/
is_root: false
weight: 90
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) class to specify different options for searching Text electronic signatures within documents.

GroupDocs.Signature API를 사용하여 텍스트 전자 서명을 검색하는 단계는 다음과 같습니다:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) object according to your requirements and specify additional search options (if needed).
* Call the [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass a list with the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) to it. The `signatures` property of the returned [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult) holds the found [TextSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignature) objects.

이 예제는 Python을 사용하여 문서에서 텍스트 전자 서명을 검색하는 방법을 보여줍니다. 각 서명의 `signature_implementation` 속성은 서명이 문서에 어떻게 추가되었는지를 나타냅니다: 페이지 내용(`NATIVE`), 주석, 양식 필드 등으로.

{{< tabs \"search_text\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_text():
    with Signature("signed.pdf") as signature:
        result = signature.search([TextSearchOptions()])

        print(f"Found {len(result.signatures)} text signature(s)")
        for text_signature in result.signatures:
            print(f"{text_signature.signature_implementation.name} text signature '{text_signature.text}' "
                  f"on page {text_signature.page_number} at ({text_signature.left}, {text_signature.top}), "
                  f"size {text_signature.width}x{text_signature.height}")

if __name__ == "__main__":
    search_text()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab \"search-text.txt\" >}}
```text
Found 3 text signature(s)
ANNOTATION text signature 'Approved' on page 1 at (50, 480), size 90x22
FORM_FIELD text signature 'John Smith' on page 1 at (50, 530), size 190x22
NATIVE text signature 'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text/search-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Advanced Search Options

다음은 더 고급 검색 옵션을 사용하는 예시입니다: 검색할 페이지, [TextMatchType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textmatchtype)와 일치시킬 텍스트, 그리고 찾을 [TextSignatureImplementation](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignatureimplementation)를 보여줍니다.

{{< tabs \"search_text_with_filters\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

def search_text_with_filters():
    with Signature("signed.pdf") as signature:
        options = TextSearchOptions()
        # 첫 번째 페이지만 검색합니다 (페이지 번호는 1부터 시작합니다)
        options.all_pages = False
        options.page_number = 1
        # Return only text signatures that contain \"John\"...
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS
        # ...그리고 페이지 내용의 일부인 경우
        options.signature_implementation = TextSignatureImplementation.NATIVE

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching text signature(s)")
        for text_signature in result.signatures:
            print(f"'{text_signature.text}' on page {text_signature.page_number} "
                  f"at ({text_signature.left}, {text_signature.top}), "
                  f"size {text_signature.width}x{text_signature.height}")

if __name__ == "__main__":
    search_text_with_filters()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf`는 이 예제에 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab \"search-text-with-filters.txt\" >}}
```text
Found 1 matching text signature(s)
'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text_with_filters/search-text-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## More Resources

### GitHub Examples

위 코드를 쉽게 실행하여 GitHub 예제에서 기능이 작동하는 모습을 확인할 수 있습니다:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

전체 기능을 갖춘 Python 라이브러리와 함께, 간단하지만 강력한 무료 온라인 앱을 제공합니다.

PDF, Word, Excel, PowerPoint 및 기타 문서에 서명하려면 **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**의 온라인 앱을 사용할 수 있습니다.
