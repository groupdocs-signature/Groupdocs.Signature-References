---
title: "MetadataSearchOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名の検索オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

メタデータ署名の検索オプションを表します。

ドキュメント内のメタデータ署名の検索を構成するオプションを提供します。

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

MetadataSearchOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | デフォルト値で MetadataSearchOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | このオプションコレクション内のすべてのメタデータ署名を復号化するために使用される [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) の実装です。 |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | ドキュメント統計や情報などの組み込みドキュメントプロパティが検索結果に含まれるかどうかを示すフラグです。 |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | 検索および一致させるメタデータ署名名です。 |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | `name` プロパティが設定されている場合にのみ適用される、検索に使用されるメタデータ名の一致タイプです。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 各ドキュメントページで検索するかどうかを示すフラグです。デフォルトではこの値は True です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 検索対象のドキュメントページ番号（オプション）。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 署名検索の対象ページを指定するオプションです。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | ドキュメントレイアウト内のシェイプ位置を返すかどうかを示すフラグです。Word ドキュメントでのみ利用可能です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` とマークされた署名のみを返すフラグです。デフォルトでは値は `False` で、指定された条件に一致するすべての署名が返されることを示します。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
