---
title: AddImageSignature
second_title: GroupDocs.Signature for .NET API リファレンス
description: 渡された引数で新しい ImageMetadataSignature を作成しコレクションに追加します
type: docs
weight: 50
url: /ja/net/groupdocs.signature.options/metadatasignoptions/addimagesignature/
---
## MetadataSignOptions.AddImageSignature method

渡された引数で新しい ImageMetadataSignature を作成し、コレクションに追加します。

```csharp
public ImageMetadataSignature AddImageSignature(ushort id, object value)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| id | UInt16 | 一意の識別子 イメージ メタデータ シグネチャ名。可能な id 値については、Exif タグ仕様のリファレンスを参照してください |
| value | Object | メタデータ値 |

### 戻り値

MetadataSignatures コレクションに追加された、新しく作成された署名

### 関連項目

* class [ImageMetadataSignature](../../../groupdocs.signature.domain/imagemetadatasignature)
* class [MetadataSignOptions](../../metadatasignoptions)
* 名前空間 [GroupDocs.Signature.Options](../../metadatasignoptions)
* 組み立て [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
