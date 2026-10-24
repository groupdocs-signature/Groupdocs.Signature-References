---
title: "DocumentResultSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "新規作成された署名を含むドキュメントのアーカイブ署名プロセスの処理結果を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/documentresultsignature/
is_root: false
weight: 170
---


## DocumentResultSignature class

新規作成された署名を含むドキュメントのアーカイブ署名プロセスの処理結果を表します。

詳細を見る

- More about signing documents withing archives using GroupDocs.Signature: https://docs.groupdocs.com/signature/net/signing-archive-documents/

DocumentResultSignature 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/basesignature/clone/) | 署名インスタンスをクローンします。 ( [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承 ) |
| [equals](/signature/python-net/groupdocs.signature.domain/basesignature/equals/) | 指定された署名オブジェクトをこのインスタンスと等価かどうか比較します。 ( [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承 ) |
| [equals_object](/signature/python-net/groupdocs.signature.domain/basesignature/equals_object/) | ( [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承 ) |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/basesignature/get_hash_code/) | GetHashCode のオーバーライド実装を提供します。 ( [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承 ) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/documentresultsignature/destin_document_size/) | 宛先ドキュメントのサイズ。 |
| [error_message](/signature/python-net/groupdocs.signature.domain/documentresultsignature/error_message/) | ドキュメントの処理中にエラーが発生した際のエラーメッセージです。 |
| [failed](/signature/python-net/groupdocs.signature.domain/documentresultsignature/failed/) | プロセス中に失敗した署名のリスト [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。 |
| [file_name](/signature/python-net/groupdocs.signature.domain/documentresultsignature/file_name/) | ドキュメントのファイル名です。 |
| [processing_time](/signature/python-net/groupdocs.signature.domain/documentresultsignature/processing_time/) | プロセスの実行時間（ミリ秒）。 |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/documentresultsignature/source_document_size/) | ソースドキュメントのサイズ。 |
| [succeeded](/signature/python-net/groupdocs.signature.domain/documentresultsignature/succeeded/) | 正常に処理された署名の一覧 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。 |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/documentresultsignature/total_signatures/) | 処理された署名の総数。 |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 署名の作成日です。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | この署名がドキュメントから削除されたかどうかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 署名の高さです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | このコンポーネントが署名 (`True`) かドキュメントコンテンツ (`False`) のどちらを表すかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 署名の左側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 署名の変更日です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 署名が見つかったページ番号です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 署名の一意の識別子です。更新または削除操作でドキュメント内の署名を変更するために使用されます。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 署名のタイプです。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 署名の上側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 署名の幅です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
