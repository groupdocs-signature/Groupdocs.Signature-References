---
title: "SwissAddress クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "債権者または債務者の住所を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

債権者または債務者の住所を表します。

ストリート、番地、郵便番号、町（構造化住所タイプ）を設定するか、住所行1と2（結合住所要素タイプ）を設定することができます。

SwissAddress 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | 住所行1（通り名、番地、または私書箱を含む）は任意で、結合要素住所でのみ使用されます。 |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | 住所の第2行（郵便番号と町が含まれます）は、結合要素の住所では必須です。 |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | 2文字のISO国コードです。住所全体がnullまたは空の値を含む場合を除き、国コードは必須です。 |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | 番地です。このフィールドは構造化住所でのみ使用され、任意です。 |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | 名前です。自然人の姓と名、または法人の会社名のいずれかです。 |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | 郵便番号です。このフィールドは構造化住所でのみ使用されます。このタイプでは必須です。 |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | 住所の通り名（番地なし）です。任意で、構造化住所でのみ使用されます。 |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | 町または市です。構造化住所でのみ使用され、このタイプでは必須です。 |

### 関連項目
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
