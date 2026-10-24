---
title: "allow_expired プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "有効期限が切れた証明書での署名を許可するフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

有効期限が切れた証明書で署名できるフラグです。デフォルト値は False です。期限切れの証明書で署名しようとすると `GroupDocsSignatureException` がスローされ、ドキュメントは署名されません。

バリデータは、有効期限が切れた証明書で作成された署名を無効として報告します。このプロパティは、どうしてもそのような署名が必要な場合、たとえば古い証明書でテストする場合にのみ True に設定してください。ドキュメントは署名され、[`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) で設定されたロガーに警告が書き込まれます。

証明書は UTC の現在時刻と比較され、[`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) とは比較されません。このフラグは、[`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/)、[`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) または [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/) で指定された証明書に適用され、スプレッドシートが署名される場合は、最初の [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) 拡張機能の証明書にも適用されます。画像のデジタル署名は証明書を使用せず、チェックも行われません。まだ有効期間が開始されていない証明書は、[`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) によって制御されます。

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### 関連項目
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
