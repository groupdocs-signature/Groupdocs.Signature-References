---
title: MetadataSignatureCollection
second_title: GroupDocs.Signature for .NET API リファレンス
description: メタデータ署名オブジェクトのコレクション.
type: docs
weight: 620
url: /ja/net/groupdocs.signature.domain/metadatasignaturecollection/
---
## MetadataSignatureCollection class

メタデータ署名オブジェクトのコレクション.

```csharp
public class MetadataSignatureCollection : ICloneable, IEnumerable<MetadataSignature>
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MetadataSignatureCollection](metadatasignaturecollection)() | メタデータ署名のコレクションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../groupdocs.signature.domain/metadatasignaturecollection/count) { get; } | コレクション内のアイテム数を取得します。 |
| [Item](../../groupdocs.signature.domain/metadatasignaturecollection/item) { get; } | プロパティの名前で MetadataSignature オブジェクトを返します. (2 indexers) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../groupdocs.signature.domain/metadatasignaturecollection/add)(MetadataSignature) | メタデータ署名オブジェクトをコレクションに追加します。 |
| [AddRange](../../groupdocs.signature.domain/metadatasignaturecollection/addrange)(IEnumerable&lt;MetadataSignature&gt;) | メタデータ署名コレクションを追加します。 |
| [Clear](../../groupdocs.signature.domain/metadatasignaturecollection/clear)() | コレクションからすべての項目を削除します。 |
| [Clone](../../groupdocs.signature.domain/metadatasignaturecollection/clone)() | メタデータ シグネチャ アイテムを含むメタデータ シグネチャ コレクション クラスのクローンを作成します。 |
| [Contains](../../groupdocs.signature.domain/metadatasignaturecollection/contains)(string) | 指定された名前のメタデータがコレクションに存在する場合、true を返します。 |
| [GetEnumerator](../../groupdocs.signature.domain/metadatasignaturecollection/getenumerator)() | 列挙子を返します。 |
| [IndexOf](../../groupdocs.signature.domain/metadatasignaturecollection/indexof)(string) | 名前でプロパティのインデックスを取得します。 |
| [Remove](../../groupdocs.signature.domain/metadatasignaturecollection/remove)(string) | 指定された名前のメタデータ署名をコレクションから削除します。 |
| [RemoveAt](../../groupdocs.signature.domain/metadatasignaturecollection/removeat)(int) | 指定されたインデックスでメタデータ署名を削除します。 |

### 関連項目

* class [MetadataSignature](../metadatasignature)
* 名前空間 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
