---
title: Signature
second_title: GroupDocs.Signature for .NET API リファレンス
description: ドキュメント署名プロセスを制御するメイン クラスを表します
type: docs
weight: 1880
url: /ja/net/groupdocs.signature/signature/
---
## Signature class

ドキュメント署名プロセスを制御するメイン クラスを表します。

```csharp
public class Signature : IDisposable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Signature](signature#constructor)(Stream) | の新しいインスタンスを初期化します[`Signature`](../signature)stream. によって提供されるドキュメントを持つクラス |
| [Signature](signature#constructor_4)(string) | の新しいインスタンスを初期化します[`Signature`](../signature)ファイルパスによって提供されるドキュメントを含むクラスインスタンス. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | の新しいインスタンスを初期化します[`Signature`](../signature)ストリーム オプションとロード オプションによって提供されるドキュメントを含むクラスLoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | の新しいインスタンスを初期化します[`Signature`](../signature)ストリームによって提供されるドキュメントを持つクラス インスタンスと[`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | の新しいインスタンスを初期化します[`Signature`](../signature)ファイルパスによって提供されるドキュメントを持つクラスインスタンスとLoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | の新しいインスタンスを初期化します[`Signature`](../signature)ファイルパスによって提供されるドキュメントを持つクラスインスタンスと[`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | の新しいインスタンスを初期化します[`Signature`](../signature)ストリームによって提供されるドキュメントを含むクラス インスタンス、ロード オプションLoadOptionsと設定[`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | の新しいインスタンスを初期化します[`Signature`](../signature)ファイルパスによって提供されるドキュメントを持つクラスインスタンス、LoadOptionsと[`SignatureSettings`](../signaturesettings). |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | 渡された署名を削除します[`BaseSignature`](../../groupdocs.signature.domain/basesignature)ドキュメントから. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | 渡された署名のリストを削除します[`BaseSignature`](../../groupdocs.signature.domain/basesignature)ドキュメントから. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | 特定のタイプ リストの署名を削除します[`SignatureType`](../../groupdocs.signature.domain/signaturetype)ドキュメントから. Sign メソッドによって追加され、Signatures としてマークされた署名のみ[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) 次の署名タイプがサポートされています: テキスト、画像、デジタル、バーコード、QR コード |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | 渡された署名のリストを削除します[`BaseSignature`](../../groupdocs.signature.domain/basesignature)ドキュメントから. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | 特定のタイプの署名を削除します[`SignatureType`](../../groupdocs.signature.domain/signaturetype)ドキュメントから. Sign メソッドによって追加され、Signatures としてマークされた署名のみ[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) 次の署名タイプがサポートされています: テキスト、画像、デジタル、バーコード、QR コード |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | 特定の署名 ID で署名をドキュメントから削除します。 |
| [Dispose](../../groupdocs.signature/signature/dispose)() | IDisposable インターフェイスを実装して、内部リソースをクリーンアップします |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | ドキュメント ページのプレビューを生成します。 |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | ドキュメント ページに関する情報を取得します: サイズ、 最大ページ高さ、最大高さのページの幅. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | によって文書内の署名を検索します。[`SearchOptions`](../../groupdocs.signature.options/searchoptions) list. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | によってドキュメント内の指定された署名タイプを検索します。[`SignatureType`](../../groupdocs.signature.domain/signaturetype)値. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | によって文書内の署名を検索します。[`SearchOptions`](../../groupdocs.signature.options/searchoptions)options. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | によって文書内の署名の正確なタイプを検索します。[`SignatureType`](../../groupdocs.signature.domain/signaturetype)値. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | のコレクションでドキュメントに署名します[`SignOptions`](../../groupdocs.signature.options/signoptions)結果をストリームに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | でドキュメントに署名します[`SignOptions`](../../groupdocs.signature.options/signoptions)結果をストリームに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | のコレクションでドキュメントに署名します[`SignOptions`](../../groupdocs.signature.options/signoptions)結果を指定したファイル パスに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | でドキュメントに署名します[`SignOptions`](../../groupdocs.signature.options/signoptions)結果を指定したファイル パスに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | のコレクションでドキュメントに署名します[`SignOptions`](../../groupdocs.signature.options/signoptions)定義済みのストリームに結果を保存します[`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | でドキュメントに署名します[`SignOptions`](../../groupdocs.signature.options/signoptions)定義済みのストリームに結果を保存します[`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | のコレクションでドキュメントに署名します[`SignOptions`](../../groupdocs.signature.options/signoptions)事前定義された指定されたファイルパスに結果を保存します[`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | でドキュメントに署名します[`SignOptions`](../../groupdocs.signature.options/signoptions)事前定義された指定されたファイルパスに結果を保存します[`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | 署名が渡された更新[`BaseSignature`](../../groupdocs.signature.domain/basesignature)ドキュメント内. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | 渡された署名を更新します[`BaseSignature`](../../groupdocs.signature.domain/basesignature)ドキュメント内. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | VerifyOptions データのリストを使用してドキュメントの署名を検証します。 |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | 指定された VerifyOptions データを使用してドキュメントの署名を検証します。 |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | 指定された SignOptions に基づいて署名プレビューを生成します。[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | 署名検索プロセスが完了したときに発生します。 |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | 署名検索プロセスの進行状況が変化したときに発生します。 |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | 署名検索プロセスが開始されたときに発生します。 |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | ドキュメントの署名プロセスが完了したときに発生します. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | ドキュメント署名プロセスの進行状況が変更されたときに発生します. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | ドキュメント署名プロセスが開始されたときに発生します。 |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | 署名検証プロセスが完了したときに発生します。 |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | 署名検証プロセスの進行状況が変化したときに発生します. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | 署名検証プロセスが開始されたときに発生します。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Signature 機能の詳細: [GroupDocs.Signature 開発者ガイド](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### 関連項目

* 名前空間 [GroupDocs.Signature](../../groupdocs.signature)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
