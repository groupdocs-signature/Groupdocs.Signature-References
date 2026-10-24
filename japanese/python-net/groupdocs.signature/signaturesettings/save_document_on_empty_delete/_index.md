---
title: "save_document_on_empty_delete プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "Delete メソッドで影響を受ける署名が削除されない場合に、ソースドキュメントを再保存するかどうかを決定するフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

Delete メソッドで影響を受ける署名が削除されない場合に、ソースドキュメントを再保存するかどうかを決定するフラグです。

True（デフォルト）の場合、署名が削除されていなくても、ドキュメントは履歴ログ（日時と操作タイプ）と共に保存されます。False の場合、元のドキュメントは変更されません。

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### 関連項目
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
