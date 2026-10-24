---
title: "load_external_resources プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントが外部リソースをロードするかどうかを決定するフラグ。"
type: docs
url: /ja/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

ドキュメントが外部リソースをロードするかどうかを決定するフラグです。このプロパティは廃止予定です。代わりに逆の意味を持つ [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) を使用してください。

LoadExternalResources = True は `SkipExternalResources` = False と同等で、LoadExternalResources = False は `SkipExternalResources` = True と同等です。デフォルト値は False で、明示的に許可しない限り外部リソースはロードされません。

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### 関連項目
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
