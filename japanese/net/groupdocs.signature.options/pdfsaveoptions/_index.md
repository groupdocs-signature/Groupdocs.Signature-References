---
title: PdfSaveOptions
second_title: GroupDocs.Signature for .NET API リファレンス
description: PDF ドキュメントのオプションを保存します
type: docs
weight: 1510
url: /ja/net/groupdocs.signature.options/pdfsaveoptions/
---
## PdfSaveOptions class

PDF ドキュメントのオプションを保存します。

```csharp
public class PdfSaveOptions : SaveOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions#constructor)() | PdfSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [PdfSaveOptions](pdfsaveoptions#constructor_1)(bool) | 上書きフラグを使用して PdfSaveOptions クラスの新しいインスタンスを初期化します。 |
| [PdfSaveOptions](pdfsaveoptions#constructor_2)(PdfSaveFileFormat) | 指定された出力ファイル形式で PdfSaveOptions クラスの新しいインスタンスを初期化します。 |
| [PdfSaveOptions](pdfsaveoptions#constructor_3)(PdfSaveFileFormat, bool) | 指定した出力ファイル形式と上書きフラグを使用して、PdfSaveOptions クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | 出力ファイル path に拡張子がない場合に自動的に拡張子を追加するフラグを取得または設定します。デフォルト値は false です。 |
| [FileFormat](../../groupdocs.signature.options/pdfsaveoptions/fileformat) { get; set; } | 署名済みドキュメントのファイル形式を取得または設定します。 |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | 既存のファイルを新しい出力ファイルで上書きするかどうかを取得または設定します。 それ以外の場合、新しいファイルはサフィックスとして数字で作成されます. デフォルトでは、この値は true に設定されており、ファイルが上書きされることを意味します. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | 署名されたドキュメントをパスワードで保護して保存するためのパスワードを取得または設定します。 このプロパティは、画像ドキュメントではサポートされていません。 |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | LoadOptions からのパスワードを使用して、署名済みドキュメントを保護されたものとして保存するかどうかを取得または設定します。 デフォルト値は true です。 このプロパティは、画像ドキュメントではサポートされていません。 |

### 関連項目

* class [SaveOptions](../saveoptions)
* 名前空間 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
