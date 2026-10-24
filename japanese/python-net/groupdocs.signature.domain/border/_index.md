---
title: "Border クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ボーダーの外観を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

ボーダーの外観を表します。

Border 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | IClonable インターフェイスを実装します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | 署名のボーダー色。 |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | 署名のボーダースタイル。 |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | 署名のボーダー透明度は 0.0（不透明）から 1.0（透明）までの範囲で、デフォルトは 0（不透明）です。 |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | ボーダーの可視性。 |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | 署名ボーダーの太さ。 |

### 例

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
`Border` を使用するタスクガイド：

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
