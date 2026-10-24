---
title: "show_properties プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "署名プロパティの表示または非表示を強制するフラグです。true の場合、署名フィールドは事前定義された外観フォーマットを使用します（例: Digitally signed by {PdfDigitalSignature.contactinfo}…）"
type: docs
url: /ja/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/
is_root: false
weight: 2040
---


## show_properties property

署名プロパティの表示または非表示を強制するフラグです。true の場合、署名フィールドは事前定義された外観フォーマット（例: `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`）を使用し、デフォルトは True です。

### Definition:
```python
@property
def show_properties(self):
    ...
@show_properties.setter
def show_properties(self, value):
    ...
```

### 関連項目
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
