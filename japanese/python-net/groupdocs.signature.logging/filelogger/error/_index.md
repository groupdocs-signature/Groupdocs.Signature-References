---
title: "error メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "コンソールにエラーメッセージを書き込みます。"
type: docs
url: /ja/python-net/groupdocs.signature.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

コンソールにエラーメッセージを書き込みます。

エラーログメッセージは、アプリケーションフローにおける回復不可能なイベントに関する情報を提供します。

```python
def error(self, message, ex):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| message | `str` | エラーメッセージです。 |
| ex | `Exception` | 例外です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | もし `ex` が None の場合。 |

### 関連項目
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
