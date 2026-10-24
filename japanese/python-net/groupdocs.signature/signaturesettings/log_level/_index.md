---
title: "log_level プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "SignatureSettings.Logger に渡されるメッセージの種類を決定するログレベルフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

どの種類のメッセージが [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) に渡されるかを決定するログレベルフラグです。

この値は組み合わせ可能な `LogLevel` フラグの集合で、例えば `LogLevel.Error | LogLevel.Warning` のように指定できます。`LogLevel.None` は何も記録しません。デフォルトは `LogLevel.All` で、エラー、警告、トレースが記録されます。

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### 関連項目
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
