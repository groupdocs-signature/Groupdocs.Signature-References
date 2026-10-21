---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "画像メタデータ署名プロパティを含みます。"
type: docs
weight: 740
url: /ja/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

画像メタデータ署名プロパティを含みます。

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Id と値で Image Metadata Signature を作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 署名の作成日を取得または設定します。 |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | 署名の Value プロパティをエンコードおよびデコードするための [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) インターフェイスの実装を取得または設定します。 |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | この署名が文書から削除されたかどうかを示すフラグを取得します。このプロパティは、削除された署名のリストを保持するための文書履歴ログレコードでのみ使用されます。 |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | 標準 Image Metadata 署名の説明を取得するための読み取り専用値 |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 署名の高さを指定します。 |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Image Metadata 署名の識別子です。標準の Signature を事前定義された Id 値で含む ImageMetadataSignatures クラスをご参照ください。 |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | このコンポーネントが署名か文書コンテンツかを示すフラグを取得または設定します。このプロパティは Update メソッドと共に使用され、要素を署名 (true) または文書要素 (false) として設定します。 |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 署名の左位置を指定します。 |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 署名の変更日を取得または設定します。 |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | 一意のメタデータ名を指定します。 |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | 署名が見つかったページを指定します。 |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | 文書内の署名を Update または Delete メソッドで変更するための一意の署名識別子です。このプロパティは Sign または Search メソッドが呼び出された後に自動的に設定されます。以前に保存されていた場合は、署名を操作するために手動で設定することができます。 |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 署名のタイプを指定します。 |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Metadata 値のサイズを取得するための読み取り専用値 |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 署名の上位置を指定します。 |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | メタデータの値タイプを指定します。 |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | メタデータオブジェクトを指定します。 |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 署名の幅を指定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Metadata Signature インスタンスをクローンします。 |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | 指定された値で Image Metadata Signature インスタンスをクローンします。 |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | 署名プロパティを比較するために Equals メソッドを上書きします |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | デシリアライズ時に Metadata Signature Value からオブジェクトを取得します。 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | デシリアライズ時に Metadata Signature Text からオブジェクトを取得します。 |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | GetHashCode メソッドをオーバーライドします |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | ブール値に変換します。 |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | DateTime に変換します。 |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | DateTime に変換します。 |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Decimal に変換します。 |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Decimal に変換します。 |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Double に変換します。 |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Double に変換します。 |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | 整数に変換します。 |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | long に変換します。 |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | float に変換します。 |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | float に変換します。 |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | String に変換します（ToString() メソッドをオーバーライド）。 |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | 指定されたフォーマットで String に変換します。 |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | 指定されたフォーマットで String に変換します。 |

### 関連項目

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
