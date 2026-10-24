---
title: "set_license メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "現在のプロセスにライセンスを適用します。"
type: docs
url: /ja/python-net/groupdocs.signature/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

現在のプロセスにライセンスを適用します。

```python
def set_license(self, license_source):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| license_source |  | 文字列パスで示す ``.lic`` ファイル、またはライセンスバイトを生成する読み取り可能なファイルライクオブジェクトのいずれかです。ファイルライク入力は、一時ファイルに書き込まれ、ブリッジに渡されます。 |

| 例外 | 説明 |
| :- | :- |
| `TypeError` | ``license_source`` が文字列パスでも読み取り可能なファイルライクオブジェクトでもない場合。 |

### 関連項目
* class [`License`](/signature/python-net/groupdocs.signature/license/)
