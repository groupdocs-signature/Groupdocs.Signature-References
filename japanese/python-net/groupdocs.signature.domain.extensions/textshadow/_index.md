---
title: "TextShadow クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "テキスト署名のテキストシャドウ プロパティを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/textshadow/
is_root: false
weight: 380
---


## TextShadow class

テキスト署名のテキストシャドウ プロパティを表します。

結果は署名タイプやドキュメント形式に応じて変わる場合があります。

TextShadow は、すべてのサポート対象ドキュメントタイプで `TextAsImage` 署名と併用することが推奨されます。また、シンプルな [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) と [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) をスプレッドシート（`.xslx`）やプレゼンテーション（`.pptx`）の透かしとして使用することもできます。

Word 文書（`.docx`）向けのシンプルな[`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/)も推奨されますが、機能は限定的です。

TextShadow 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/__init__/) | デフォルトオプションで TextShadow を初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | このオブジェクトのコピーを取得します。（[`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/) から継承） |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [angle](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/angle/) | テキストに対する影の配置角度です。デフォルト値は 0 です。 |
| [blur](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/blur/) | 影のぼかしです。デフォルト値は 4 です。 |
| [color](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/color/) | 影の色です。デフォルト値は Black です。 |
| [distance](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/distance/) | テキストから影までの距離です。 |
| [transparency](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/transparency/) | 影の透明度です。 |

### 関連項目
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
