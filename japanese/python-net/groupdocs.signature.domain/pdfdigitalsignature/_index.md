---
title: "PdfDigitalSignature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "PDF デジタル署名プロパティを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

PDF デジタル署名プロパティを表します。

PdfDigitalSignature 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | 証明書なしで PDF デジタル署名を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | 指定された X509 ストアを使用して PDF デジタル署名を初期化します。ストアから最初の証明書が使用されます。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | 指定された X509 ストアと証明書インデックスを使用して PDF デジタル署名を初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | 指定された X509 証明書で PDF デジタル署名を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | PDF デジタル署名インスタンスをクローンします。 |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | 署名プロパティを比較して等価性を判断します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | GetHashCode メソッドをオーバーライドします。 |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | すべてのシステム X509 証明書ストアからデジタル署名をロードします。(inherited from [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (継承元: [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (継承元: [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (継承元: [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | 署名者が提供する連絡先情報で、受取人が署名を検証できるようにします。例: 電話番号。 |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | 署名の CPU ホスト名または物理的な場所です。 |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | 署名の理由、例: (I agreeРІР‚В¦)。 |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | 署名プロパティの表示または非表示を強制するフラグです。true の場合、署名フィールドは事前定義された外観フォーマット（例: `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`）を使用し、デフォルトは True です。 |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | PDF デジタル署名のタイムスタンプです。デフォルト値は None です。 |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | PDF デジタル署名のタイプです。 |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | デジタル署名に関連付けられた X509 証明書です。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | 証明書のカスタムストア名です。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | 証明書のストア場所です。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | 証明書のストア名です。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | 署名目的のコメントです。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 署名の作成日です。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | この署名がドキュメントから削除されたかどうかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 署名の高さです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | このコンポーネントが署名 (`True`) かドキュメントコンテンツ (`False`) のどちらを表すかを示すフラグです。 ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) から継承) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | デジタル署名は有効で、文書は改ざんされていません。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 署名の左側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 署名の変更日です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 署名が見つかったページ番号です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | 文書が署名された時間です。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 署名の一意の識別子です。更新または削除操作でドキュメント内の署名を変更するために使用されます。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 署名のタイプです。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | 証明書のサムプリントです。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 署名の上側位置です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 署名の幅です。 (継承元: [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | XAdES タイプ（[`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)）。( [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/) から継承) |

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
