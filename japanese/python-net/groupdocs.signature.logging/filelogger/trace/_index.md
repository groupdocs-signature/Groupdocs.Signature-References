---
title: "trace メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "コンソールにトレースメッセージを書き込みます。"
type: docs
url: /ja/python-net/groupdocs.signature.logging/filelogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

コンソールにトレースメッセージを書き込みます。

トレースログメッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。

```python
def trace(self, message):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| message | `str` | トレースメッセージです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `message` が None のときに発生します。 |

### 関連項目
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
