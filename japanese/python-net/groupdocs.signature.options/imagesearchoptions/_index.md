---
title: "ImageSearchOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "画像署名の検索オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

画像署名の検索オプションを表します。

詳しくは以下をご覧ください:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

ImageSearchOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | デフォルト値で ImageSearchOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | 検索条件の画像の最大サイズ（バイト単位）。 |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | 検索時に考慮される画像データの最小サイズ（バイト単位）。0 以外の値は最小サイズを指定します。デフォルトは 0 で、検索結果に影響しません。 |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | 署名の画像コンテンツを返すかどうかを決定するフラグ。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | `return_content` プロパティが有効なときに返される画像コンテンツのファイルタイプです。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 各ドキュメントページで検索するかどうかを示すフラグです。デフォルトではこの値は True です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 検索対象のドキュメントページ番号（オプション）。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 署名検索の対象ページを指定するオプションです。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | ドキュメントレイアウト内のシェイプ位置を返すかどうかを示すフラグです。Word ドキュメントでのみ利用可能です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` とマークされた署名のみを返すフラグです。デフォルトでは値は `False` で、指定された条件に一致するすべての署名が返されることを示します。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### 例

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

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
