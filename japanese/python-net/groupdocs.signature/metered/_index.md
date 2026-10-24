---
title: "Metered クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "従量課金（使用量に応じた）ライセンスを管理します。"
type: docs
url: /ja/python-net/groupdocs.signature/metered/
is_root: false
weight: 40
---


## Metered class

従量課金（使用量に応じた）ライセンスを管理します。

Metered ライセンスは実際の使用量に基づいて請求されます（通常はページまたは
処理されたドキュメント）。public/private キーペアは一度だけ設定します
アプリケーションの起動時に設定します；ラッパーは使用状況を GroupDocs にバックグラウンドで報告します
バックグラウンドでライセンスサーバーへ

Metered 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get_consumption_credit](/signature/python-net/groupdocs.signature/metered/get_consumption_credit/) | これまでに消費されたクレジット数を返します。 |
| [get_consumption_quantity](/signature/python-net/groupdocs.signature/metered/get_consumption_quantity/) | これまでに処理されたデータ量を返します。 |
| [set_metered_key](/signature/python-net/groupdocs.signature/metered/set_metered_key/#public_key-private_key) | 指定された public/private キーペアで従量課金を有効にします。 |

### 関連項目
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
