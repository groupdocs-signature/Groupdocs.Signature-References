---
title: "StampLine クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "スタンプのラインプロパティを指定します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

スタンプのラインプロパティを指定します。

StampLine 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | デフォルト値で StampLine を初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | 署名の背景色。 |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | スタンプラインテキストのフォント。 |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | スタンプ上の行の高さ。 |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | スタンプラインの内部枠線。 |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | スタンプ行の外側の境界。 |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | スタンプ行のテキスト。 |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | テキストの下部の意図。 |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | 署名のテキスト色。 |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | テキストの繰り返し種別。 |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | スタンプ行の可視性。 |

### 例

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# スタンプ行を作成する
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
