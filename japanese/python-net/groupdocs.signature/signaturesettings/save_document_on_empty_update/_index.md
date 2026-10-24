---
title: "save_document_on_empty_update プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "Update メソッドで更新する署名がない場合に、元のドキュメントを再保存するかどうかを決定するフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

`Update` メソッドで更新する署名がない場合に、ソースドキュメントを再保存するかどうかを決定するフラグです。

`True`（デフォルト）に設定すると、署名が更新されていなくても、ドキュメントは対応する履歴プロセスログ（日時と操作タイプ）と共に保存されます。`False` に設定すると、元のドキュメントはまったく変更されません。

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### 関連項目
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
