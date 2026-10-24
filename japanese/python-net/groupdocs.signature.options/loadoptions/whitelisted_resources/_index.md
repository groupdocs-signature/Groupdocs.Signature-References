---
title: "whitelisted_resources プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "LoadOptions.SkipExternalResources が true の場合でもロードされる外部リソースのアドレスフラグメントのリスト。"
type: docs
url: /ja/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

[`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) が true の場合でもロードされる外部リソースのアドレスフラグメントのリストです。デフォルト値は空のリストです。

リソースは、その完全なアドレスがフラグメントのいずれかを含む場合にロードされます。比較は大文字小文字を無視し、空のフラグメントは無視されます。`\"https://cdn.example.com/images/\"` のような長いフラグメントを優先してください。短いフラグメントは、それを含む他のアドレスにも一致します。

このプロパティを `None` に設定するとリストがクリアされます。[`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) が false の場合、このリストは効果がありません。なぜならその場合はすべての外部リソースがロードされるからです。

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### 関連項目
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
