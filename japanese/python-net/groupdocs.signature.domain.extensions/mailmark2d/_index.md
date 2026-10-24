---
title: "Mailmark2D クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "Royal Mail 2D Mailmarkに埋め込まれたテキストをエンコードおよびデコードします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Royal Mail 2D Mailmarkに埋め込まれたテキストをエンコードおよびデコードします。

Mailmark2D 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Royal Mail Mailmark の結合データを、デフォルトの一次データと二次データの値で初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | このオブジェクトのコピーを返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | 項目のクラスです。 |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | 顧客が使用できるオプションのスペースです。 |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | DataMatrix バーコードのエンコードモードです。デフォルト値: `DataMatrixEncodeMode.c40`。 |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | このプロパティは DPS を含む配達先住所の郵便番号を保持します。内陸の住所の場合、エリア（1‑2 文字）、地区（1‑2 文字）、セクター（1 文字）、ユニット（2 文字）、および DPS（2 文字）で構成され、正しい PAF® 形式に従う必要があり、最大長は 9 文字です。 |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | 各製品タイプの Royal Mail Mailmark バーコードペイロードの識別子です。 |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | Supply Chain ID 内の一意のアイテム識別子で、少なくとも 90 日間（最大値: 99999999）の一意の識別のためにすべての Mailmark バーコードに必要です。 |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | DPS なしの Return to Sender 郵便番号です。 |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | 要求されている Return to Sender サービスのレベルを示すフラグです。最大長は 1 です。 |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | メール送信に関与する顧客の一意のグループです。 |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | UPU 国 ID（最大長: 4 文字）です。 |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | 各 Information Type ID に関連するバーコードバージョン識別子です。 |

### 関連項目
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
