---
title: "バーコード電子署名を検索する"
linkTitle: "Barcodes"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "この記事では、.NET API を介した Python 用 GroupDocs.Signature を使用して、ドキュメントページ内のバーコード電子署名を検索する方法を説明します。"
type: docs
url: /ja/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

バーコード署名は、機械がスキャンして読み取れるデータの視覚的表現です。通常、幅が異なる平行な黒線と白い間隔で構成されます。バーコードは一般的に以下の目的で使用されます：
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

[Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) クラスは、ドキュメント内のバーコード署名を検索できる [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) メソッドを提供します。使用方法は以下の通りです：

1. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) クラスの新しいインスタンスを作成し、ソースドキュメントのパスをパラメータとして渡します。
2. 必要なオプションを指定して [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) オブジェクトをインスタンス化します。
3. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) クラスのインスタンスの [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) メソッドを呼び出し、[BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) を含むリストを渡します。
4. 検索結果を処理します：返された [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) の `signatures` プロパティには、見つかった [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) オブジェクトが格納されています。

ドキュメント内でバーコード署名を検索する例を以下に示します：

{{< tabs \"search_barcodes\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # ドキュメントのすべてのページでバーコード署名を検索する
        result = signature.search([BarcodeSearchOptions()])

        print(f"Found {len(result.signatures)} barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}' "
                  f"at ({barcode.left}, {barcode.top}), size {barcode.width}x{barcode.height}")

if __name__ == "__main__":
    search_barcodes()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) をクリックしてください。

{{< /tab >}}
{{< tab \"search-barcodes.txt\" >}}
```text
Found 2 barcode signature(s)
Page 1: Code128 barcode '123456789012' at (400, 375), size 170x45
Page 1: Code39 barcode 'JS-2026' at (400, 430), size 170x45
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes/search-barcodes.txt)
{{< /tab >}}
{{< /tabs >}}

## Advanced Search Options

[BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) クラスは、検索範囲を絞り込むためのプロパティを提供します：

- `encode_type` returns only barcodes of the given type, for example `BarcodeTypes.CODE128`;
- `text` and `match_type` return only barcodes whose text matches;
- `all_pages` and `page_number` search a single page instead of the whole document (page numbers start at 1);
- `return_content` and `return_content_type` also return the barcode image.

{{< tabs "search_barcodes_with_filters" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes_with_filters():
    with Signature("signed.pdf") as signature:
        options = BarcodeSearchOptions()
        # 最初のページのみ検索
        options.all_pages = False
        options.page_number = 1
        # テキストが "1234" で始まる Code 128 バーコードのみ返す
        options.encode_type = BarcodeTypes.CODE128
        options.text = "1234"
        options.match_type = TextMatchType.STARTS_WITH

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}'")

if __name__ == "__main__":
    search_barcodes_with_filters()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "search-barcodes-with-filters.txt" >}}
```text
Found 1 matching barcode signature(s)
Page 1: Code128 barcode '123456789012'
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes_with_filters/search-barcodes-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## Additional Resources

### GitHub Examples

上記のコードを簡単に実行し、サンプルで機能の動作を確認できます:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

完全な Python ライブラリと共に、シンプルながら強力な無料アプリを提供しています。

無料のオンラインアプリでドキュメント内のバーコード署名を検索できます:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
