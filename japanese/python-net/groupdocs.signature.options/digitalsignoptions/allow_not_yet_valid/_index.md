---
title: "allow_not_yet_valid プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "有効期間がまだ開始されていない証明書での署名を許可するフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

有効期間がまだ開始されていない証明書で署名できるフラグです。デフォルト値は False です。そのような証明書で署名しようとすると `GroupDocsSignatureException` がスローされ、ドキュメントは署名されません。

バリデータは、証明書が有効になる前に作成された署名を無効として報告します。そのような証明書は通常、後日の発行であるか、コンピュータの時計が誤っている場合です。このフラグが True のとき、ドキュメントは署名され、[`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) に設定されたロガーに警告が書き込まれます。

証明書は UTC の現在時刻と比較されます。このフラグは、有効期間が終了した証明書を制御する [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) と同じ証明書に適用されます。

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### 関連項目
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
