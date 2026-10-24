---
title: "CertificateVerifyOptions クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "証明書ドキュメントを検証するオプションを保持します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

証明書ドキュメントを検証するオプションを保持します。

詳細を見る

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

CertificateVerifyOptions 型は以下のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | `TextVerifyOptions` の新しいインスタンスをデフォルト値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | 検証対象のサブジェクトを指定して、新しい CertificateVerifyOptions インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | このプロパティは、検証結果に基づいて証明書が期限切れかどうかを示します。 |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | 検証対象の証明書発行者。 |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | 検証に使用されるテキスト一致タイプ。 |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | 検証プロセスは、基本検証ポリシーを使用した X.509 鍵チェーンの検証を提供すべきです。 |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | 検証対象の証明書シリアル番号。 |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | 検証対象の証明書サブジェクト。 |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | 検証対象の証明書サムプリント。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 各ドキュメントページを検証するかどうかを示すフラグ。デフォルトは True です。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 代替署名オプション検証のための追加拡張子。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 有効なプロパティフラグ。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 検証対象のドキュメントページ番号。設定されていない場合、ドキュメントのすべてのページが最初の出現箇所で検証されます（最小値は 1）。（[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) から継承） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 検証対象のページを指定するページオプションです。(継承元: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | ヘッダー/フッターの署名を検証するために使用される文書レイアウト内のシェイプ位置です。(継承元: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### 関連項目
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
