---
title: "Padding クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "要素に関連付けられたパディングまたはマージン情報を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

要素に関連付けられたパディングまたはマージン情報を表します。

Padding 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Padding クラスの新しいインスタンスをゼロ値で初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Padding クラスの新しいインスタンスを、すべての辺に対して指定されたパディングサイズを使用して初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Padding クラスの新しいインスタンスを、指定されたパディングサイズを使用して初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | このオブジェクトのコピーを取得します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | すべての辺のパディング値。 |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | 下辺のパディング値。 |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | 右辺と左辺の合計パディング。 |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | 左辺のパディング値。 |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | 右辺のパディング値。 |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | 上辺のパディング値。 |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | 上辺と下辺の合計パディング。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | パディングなしの Padding オブジェクトを提供します。 |

### 例

```python
from groupdocs.signature.domain import Padding

# すべての側面で 5 ユニットの均一なパディング
uniform = Padding(5)

# 右側と下側の特定のパディング
custom = Padding(right=40, bottom=60)
```

### Guides
`Padding` を使用するタスク ガイド:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
