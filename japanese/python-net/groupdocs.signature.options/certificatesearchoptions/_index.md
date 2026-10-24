---
title: "CertificateSearchOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "証明書メタデータ署名の検索オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/certificatesearchoptions/
is_root: false
weight: 60
---


## CertificateSearchOptions class

証明書メタデータ署名の検索オプションを表します。

詳細を見る

- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: Advanced search within Digital Certificate X509 documents (https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

CertificateSearchOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/) | `TextSearchOptions` クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/#text) | テキスト値を使用して TextSearchOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/match_type/) | 検索に使用されるテキスト一致タイプ。 |
| [text](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/text/) | 検索時に一致させる証明書プロパティのテキストです。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 各ドキュメントページで検索するかどうかを示すフラグです。デフォルトではこの値は True です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 検索対象のドキュメントページ番号（オプション）。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 署名検索の対象ページを指定するオプションです。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | ドキュメントレイアウト内のシェイプ位置を返すかどうかを示すフラグです。Word ドキュメントでのみ利用可能です。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` とマークされた署名のみを返すフラグです。デフォルトでは値は `False` で、指定された条件に一致するすべての署名が返されることを示します。(継承元: [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
