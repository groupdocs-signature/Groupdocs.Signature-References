---
title: "SignatureFont クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "SignatureFont クラスはテキスト署名のフォントプロパティを指定します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

SignatureFont クラスはテキスト署名のフォントプロパティを指定します。

SignatureFont 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | SignatureFont をデフォルト値で初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | フォントの太字スタイルです。 |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | フォントのファミリ名です。 |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | フォントの斜体スタイルです。 |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | フォントサイズです。 |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | フォントの取り消し線スタイルです。 |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | フォントの下線スタイルです。 |

### 例

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
`SignatureFont` を使用するタスクガイド:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
