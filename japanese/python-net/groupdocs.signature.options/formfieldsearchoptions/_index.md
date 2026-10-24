---
title: "FormFieldSearchOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "フォームフィールド署名の検索オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

フォームフィールド署名の検索オプションを表します。

詳しくは以下をご覧ください:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

FormFieldSearchOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | FormFieldSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | 検索時にフォームフィールド署名名と一致させるために使用される正規表現パターンです。 |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | 検索対象のフォームフィールド署名のタイプです。デフォルト値は None です。 |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | 検索対象のフォームフィールド署名の値です。デフォルトは None です。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 各ドキュメントページで検索するかどうかを示すフラグです。デフォルトではこの値は True です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 検索対象のドキュメントページ番号（オプション）。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 署名検索の対象ページを指定するオプションです。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | ドキュメントレイアウト内のシェイプ位置を返すかどうかを示すフラグです。Word ドキュメントでのみ利用可能です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` とマークされた署名のみを返すフラグです。デフォルトでは値は `False` で、指定された条件に一致するすべての署名が返されることを示します。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # "ApprovedBy" という名前のテキストフィールドのみを返します
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
