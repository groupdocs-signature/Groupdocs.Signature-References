---
title: ImageMetadataSignature
second_title: GroupDocs.Signature for .NET API リファレンス
description: 画像メタデータ署名プロパティが含まれています.
type: docs
weight: 570
url: /ja/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

画像メタデータ署名プロパティが含まれています.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | ID と値で画像メタデータ署名を作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 署名の作成日を取得または設定します。 |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | の実装を取得または設定します[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)署名の値のプロパティをエンコードおよびデコードするためのインターフェイス. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | この署名がドキュメントから削除されたかどうかを示すフラグを取得します。 このプロパティは、削除された署名のリストを保持するためにドキュメント履歴ログ レコードにのみ使用されます。 |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | 標準の画像メタデータ署名の説明を取得するための読み取り専用値 |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 署名の高さを指定します。 |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | 画像メタデータ署名の識別子。 参照ImageMetadataSignatures事前定義された Id 値を持つ標準署名を含むクラス. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | このコンポーネントが署名またはドキュメント コンテンツであるかどうかを示すフラグを取得または設定します。 このプロパティは Update メソッドで使用され、要素を署名 (true) またはドキュメント要素 (false) として設定します。 |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 署名の左位置を指定します。 |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 署名の変更日を取得または設定します。 |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | 一意のメタデータ名を指定します。 |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | ページの署名が見つかったことを示します。 |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Update メソッドまたは Delete メソッドでドキュメントの署名を変更するための一意の署名識別子。 このプロパティは、Sign メソッドまたは Search メソッドが呼び出された後に自動的に設定されます。 このプロパティが保存される前に手動で設定して署名を操作することができます。 |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 署名のタイプを指定します。 |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | メタデータのサイズを取得するための読み取り専用値 value |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 折丁の先頭位置を指定します。 |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | メタデータ値のタイプを指定します。 |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | メタデータ オブジェクトを指定します。 |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 署名の幅を指定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | メタデータ署名インスタンスの複製. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | 指定された値でイメージ メタデータ署名インスタンスを複製します。 |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Equals メソッドを上書きして署名プロパティを比較します |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | 逆シリアル化でメタデータ署名値からオブジェクトを取得します。 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | デシリアライゼーションでメタデータ署名テキストからオブジェクトを取得します。 |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | GetHashCode method をオーバーライドします |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | ブール値に変換. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | DateTime に変換します。 |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | DateTime に変換します。 |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | 10 進数に変換します。 |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | 10 進数に変換します。 |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Double に変換します。 |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Double に変換します。 |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | 整数に変換します。 |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | long に変換します。 |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | float に変換します。 |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | float に変換します。 |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | オーバーライド ToString() method で文字列に変換します |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | 指定されたフォーマットの文字列に変換します |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | 指定されたフォーマットの文字列に変換します |

### 関連項目

* class [MetadataSignature](../metadatasignature)
* 名前空間 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
