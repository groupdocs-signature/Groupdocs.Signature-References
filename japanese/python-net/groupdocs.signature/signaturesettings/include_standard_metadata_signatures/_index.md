---
title: "include_standard_metadata_signatures プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "標準ドキュメントメタデータ署名（Author、Owner、作成日、変更日など）がメタデータリストに含まれるかどうかを示すフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

標準ドキュメントメタデータ署名（Author、Owner、作成日、変更日など）がメタデータリストに含まれるかどうかを示すフラグです。

False（デフォルト）に設定すると、GetDocumentInfo はこれらのメタデータ署名を含めません。True に設定すると、ドキュメント情報に標準メタデータ署名が含まれます。

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### 関連項目
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
