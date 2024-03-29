---
title: DocumentInfo
second_title: GroupDocs.Signature for .NET API リファレンス
description: ドキュメント記述プロパティを定義します
type: docs
weight: 160
url: /ja/net/groupdocs.signature.domain/documentinfo/
---
## DocumentInfo class

ドキュメント記述プロパティを定義します。

```csharp
public class DocumentInfo : IDocumentInfo
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DocumentInfo](documentinfo)() | の新しいインスタンスを初期化します[`DocumentInfo`](../documentinfo)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BarcodeSignatures](../../groupdocs.signature.domain/documentinfo/barcodesignatures) { get; } | によって追加または更新されたドキュメント バーコード署名のコレクション[`Signature`](../../groupdocs.signature/signature)メソッド. |
| [DigitalSignatures](../../groupdocs.signature.domain/documentinfo/digitalsignatures) { get; } | によって追加または更新されたドキュメントのデジタル署名のコレクション[`Signature`](../../groupdocs.signature/signature)メソッド. |
| [FileType](../../groupdocs.signature.domain/documentinfo/filetype) { get; set; } | ファイル形式の種類. |
| [FormFields](../../groupdocs.signature.domain/documentinfo/formfields) { get; } | ドキュメント内の既存のサポートされているすべてのフォーム フィールドのコレクション。このプロパティは、PDF およびワープロ ドキュメント タイプでのみサポートされます。 |
| [FormFieldSignatures](../../groupdocs.signature.domain/documentinfo/formfieldsignatures) { get; } | によって追加または更新されたドキュメント フォーム フィールド署名のコレクション[`Signature`](../../groupdocs.signature/signature)メソッド. |
| [ImageSignatures](../../groupdocs.signature.domain/documentinfo/imagesignatures) { get; } | によって追加または更新された文書画像署名のコレクション[`Signature`](../../groupdocs.signature/signature)メソッド. |
| [MaxPageHeight](../../groupdocs.signature.domain/documentinfo/maxpageheight) { get; set; } | ページの最大高さを指定します。 |
| [MetadataSignatures](../../groupdocs.signature.domain/documentinfo/metadatasignatures) { get; } | ドキュメント メタデータ署名のコレクション. |
| [PageCount](../../groupdocs.signature.domain/documentinfo/pagecount) { get; set; } | ドキュメントのページ数. |
| [Pages](../../groupdocs.signature.domain/documentinfo/pages) { get; set; } | ドキュメント ページの説明のコレクション。 |
| [ProcessLogs](../../groupdocs.signature.domain/documentinfo/processlogs) { get; } | 署名、更新、削除などのドキュメント履歴プロセスのコレクション。 |
| [QrCodeSignatures](../../groupdocs.signature.domain/documentinfo/qrcodesignatures) { get; } | によって追加または更新されたドキュメント QR コード署名のコレクション[`Signature`](../../groupdocs.signature/signature)メソッド. |
| [Signatures](../../groupdocs.signature.domain/documentinfo/signatures) { get; } | ドキュメントのすべてのタイプの署名のコレクション[`BaseSignature`](../basesignature). |
| [Size](../../groupdocs.signature.domain/documentinfo/size) { get; set; } | 文書サイズ (バイト単位). |
| [TextSignatures](../../groupdocs.signature.domain/documentinfo/textsignatures) { get; } | 文書テキスト署名のコレクション. |
| [WidthForMaxHeight](../../groupdocs.signature.domain/documentinfo/widthformaxheight) { get; set; } | 最大ページ高さの幅を指定します。 |

### 関連項目

* interface [IDocumentInfo](../idocumentinfo)
* 名前空間 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
