---
title: "テキスト電子署名の検索"
linkTitle: "Texts"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "このトピックでは、.NET API を介した Python 用 GroupDocs.Signature を使用して、文書ページ内のテキスト電子署名を検索する方法を説明します。"
type: docs
url: /ja/python-net/guides/search-for-text-e-signatures/
is_root: false
weight: 90
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) class to specify different options for searching Text electronic signatures within documents.

GroupDocs.Signature API を使用してテキスト電子署名を検索する手順は次のとおりです：

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) object according to your requirements and specify additional search options (if needed).
* Call the [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass a list with the [TextSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsearchoptions) to it. The `signatures` property of the returned [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult) holds the found [TextSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignature) objects.

この例は、Python を使用して文書内のテキスト電子署名を検索する方法を示しています。各署名の `signature_implementation` プロパティは、署名が文書にどのように追加されたか（ページコンテンツ（`NATIVE`）、注釈、フォームフィールドなど）を示します。

{{< tabs "search_text" >}}
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
{{< tab \"signed.pdf\" >}}

`signed.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには[ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf)をクリックしてください。

{{< /tab >}}
{{< tab "search-text.txt" >}}
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

以下は、より高度な検索オプションの使用方法を示す例です：検索対象のページ、[TextMatchType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textmatchtype) によるテキストの一致、そして検索対象となる [TextSignatureImplementation](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/textsignatureimplementation)。

{{< tabs "search_text_with_filters" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

def search_text_with_filters():
    with Signature("signed.pdf") as signature:
        options = TextSearchOptions()
        # 最初のページのみを検索します（ページ番号は 1 から開始）
        options.all_pages = False
        options.page_number = 1
        # "John" を含むテキスト署名のみを返します…
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS
        # …そしてページコンテンツの一部であるもの
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
{{< tab \"signed.pdf\" >}}

`signed.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには[ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/signed.pdf)をクリックしてください。

{{< /tab >}}
{{< tab "search-text-with-filters.txt" >}}
```text
Found 1 matching text signature(s)
'John Smith' on page 1 at (50, 379), size 189x30
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-text-e-signatures/search_text_with_filters/search-text-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## More Resources

### GitHub Examples

上記のコードを簡単に実行して、GitHub のサンプルで機能を実際に確認できます:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

フル機能の Python ライブラリに加えて、シンプルで強力な無料オンラインアプリも提供しています。

PDF、Word、Excel、PowerPoint、その他のドキュメントに署名するには、**[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** のオンラインアプリを使用できます。
