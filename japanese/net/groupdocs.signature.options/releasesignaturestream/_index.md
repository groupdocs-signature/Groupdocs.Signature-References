---
title: ReleaseSignatureStream
second_title: GroupDocs.Signature for .NET API リファレンス
description: 出力署名プレビュー ストリームを解放するメソッドを定義するデリゲート
type: docs
weight: 1660
url: /ja/net/groupdocs.signature.options/releasesignaturestream/
---
## ReleaseSignatureStream delegate

出力署名プレビュー ストリームを解放するメソッドを定義するデリゲート。

```csharp
public delegate void ReleaseSignatureStream(PreviewSignatureOptions previewOptions, 
    Stream signatureStream);
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| previewOptions | PreviewSignatureOptions | プレビューされた署名のオプション。 |
| signatureStream | Stream | リリースする署名画像ストリーム。 |

### 関連項目

* class [PreviewSignatureOptions](../previewsignatureoptions)
* 名前空間 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->