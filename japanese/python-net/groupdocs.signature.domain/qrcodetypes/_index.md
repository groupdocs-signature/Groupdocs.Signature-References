---
title: "QrCodeTypes クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "QR コードタイプのコンテナです。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/qrcodetypes/
is_root: false
weight: 570
---


## QrCodeTypes class

QR コードタイプのコンテナです。

QrCodeTypes 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/parse/#parsing_type) | QR コードのタイプ名を解析し、対応する QRCodeType インスタンスを返します。 |
| [try_parse](/signature/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/#parsing_type) | 指定された解析タイプ名に一致する QRCode タイプを返します。名前が不明な場合は None を返します。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [ALL_TYPES](/signature/python-net/groupdocs.signature.domain/qrcodetypes/all_types/) | すべての QRCode タイプ。 |
| [AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/aztec/) | Aztec QR-Code タイプ オブジェクト。 |
| [DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/data_matrix/) | DataMatrix QR-Code タイプ オブジェクト。 |
| [QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/qr/) | QR QR-Code タイプ オブジェクト。 |
| [GS1_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_data_matrix/) | GS1 DataMatrix QR-Code タイプ オブジェクト。 |
| [GS1QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1qr/) | GS1 QR-Code タイプ オブジェクト。 |
| [HIBCLICQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclicqr/) | HIBC LIC QRコード タイプ オブジェクト。 |
| [HIBCLIC_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_data_matrix/) | HIBC LIC データマトリックス QRコード タイプ オブジェクト。 |
| [HIBCLIC_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibclic_aztec/) | HIBC LIC アズテック QRコード タイプ オブジェクト。 |
| [HIBCPASQR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpasqr/) | HIBC PAS QRコード タイプ オブジェクト。 |
| [HIBCPAS_DATA_MATRIX](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_data_matrix/) | HIBC PAS データマトリックス QRコード タイプ オブジェクト。 |
| [HIBCPAS_AZTEC](/signature/python-net/groupdocs.signature.domain/qrcodetypes/hibcpas_aztec/) | HIBC PAS アズテック QRコード タイプ オブジェクト。 |
| [HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/han_xin/) | Han Xin QRコード タイプ オブジェクト。 |
| [GS1_HAN_XIN](/signature/python-net/groupdocs.signature.domain/qrcodetypes/gs1_han_xin/) | GS1 Han Xin QRコード タイプ オブジェクト。 |
| [RECT_MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/rect_micro_qr/) | RectMicroQR タイプ オブジェクト。 |
| [MICRO_QR](/signature/python-net/groupdocs.signature.domain/qrcodetypes/micro_qr/) | MicroQR タイプ オブジェクト。 |

### 例

```python
from groupdocs.signature.domain import QrCodeTypes

# 署名オプションを作成する際は QRコード タイプ 列挙体 を使用してください
print(QrCodeTypes.QR)
```

### Guides
`QrCodeTypes` を使用するタスク ガイド:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
