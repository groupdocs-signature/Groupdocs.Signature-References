---
title: "署名"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "ドキュメント署名プロセスを制御するメインクラスを表します。"
type: docs
weight: 2170
url: /ja/net/groupdocs.signature/signature/
---
## Signature class

ドキュメント署名プロセスを制御するメインクラスを表します。

```csharp
public class Signature : IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Signature](signature#constructor)(Stream) | `[`Signature`](../signature)` クラスの新しいインスタンスを、ストリームで提供されたドキュメントで初期化します。 |
| [Signature](signature#constructor_4)(string) | `[`Signature`](../signature)` クラスの新しいインスタンスを、ファイル パスで提供されたドキュメントで初期化します。 |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | `[`Signature`](../signature)` クラスの新しいインスタンスを、ストリームで提供されたドキュメントとロード オプション LoadOptions で初期化します。 |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | `[`Signature`](../signature)` クラスの新しいインスタンスを、ストリームで提供されたドキュメントと [`SignatureSettings`](../signaturesettings) で初期化します。 |
| [Signature](signature#constructor_5)(string, LoadOptions) | `[`Signature`](../signature)` クラスの新しいインスタンスを、ファイル パスで提供されたドキュメントと LoadOptions で初期化します。 |
| [Signature](signature#constructor_7)(string, SignatureSettings) | `[`Signature`](../signature)` クラスの新しいインスタンスを、ファイル パスで提供されたドキュメントと [`SignatureSettings`](../signaturesettings) で初期化します。 |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | `[`Signature`](../signature)` クラスの新しいインスタンスを、ストリームで提供されたドキュメント、ロード オプション LoadOptions、そして設定 [`SignatureSettings`](../signaturesettings) で初期化します。 |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | `[`Signature`](../signature)` クラスの新しいインスタンスを、ファイル パスで提供されたドキュメント、LoadOptions、そして [`SignatureSettings`](../signaturesettings) で初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | 渡された署名 [`BaseSignature`](../../groupdocs.signature.domain/basesignature) をドキュメントから削除します。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | 渡された署名リスト [`BaseSignature`](../../groupdocs.signature.domain/basesignature) をドキュメントから削除します。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | ドキュメントから特定のタイプリスト [`SignatureType`](../../groupdocs.signature.domain/signaturetype) の署名を削除します。Sign メソッドで追加され、署名としてマークされた [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) のみが削除対象となります。サポートされている署名タイプは次のとおりです：Text、Image、Digital、Barcode、QR-Code。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | 渡された署名リスト [`BaseSignature`](../../groupdocs.signature.domain/basesignature) をドキュメントから削除します。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | ドキュメントから特定のタイプ [`SignatureType`](../../groupdocs.signature.domain/signaturetype) の署名を削除します。Sign メソッドで追加され、署名としてマークされた [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) のみが削除対象となります。サポートされている署名タイプは次のとおりです：Text、Image、Digital、Barcode、QR-Code。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | ドキュメントから特定の署名 Id による署名を削除します。 |
| [Dispose](../../groupdocs.signature/signature/dispose)() | 内部リソースをクリーンアップするために IDisposable インターフェイスを実装します。 |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | ドキュメントページのプレビューを生成します。 |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | ドキュメントページに関する情報を取得します：各ページのサイズ、最大ページ高さ、最大高さのページの幅。 |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | 利用可能なすべての検索オプションを使用してドキュメント内の署名を検索し、指定された述語に基づいて結果をフィルタリングします。 |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | ドキュメント内の署名を[`SearchOptions`](../../groupdocs.signature.options/searchoptions)リストで検索します。 |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | ドキュメント内の指定された署名タイプを[`SignatureType`](../../groupdocs.signature.domain/signaturetype)値で検索します。 |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | 提供された検索オプションを使用してドキュメント内の署名を検索し、指定された述語に基づいて結果をフィルタリングします。 |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | ドキュメント内の署名を[`SearchOptions`](../../groupdocs.signature.options/searchoptions)オプションで検索します。 |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | ドキュメント内の署名の正確なタイプを[`SignatureType`](../../groupdocs.signature.domain/signaturetype)値で検索します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | `[`SignOptions`](../../groupdocs.signature.options/signoptions)`のコレクションでドキュメントに署名し、結果をストリームに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | `[`SignOptions`](../../groupdocs.signature.options/signoptions)`でドキュメントに署名し、結果をストリームに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | `[`SignOptions`](../../groupdocs.signature.options/signoptions)`のコレクションでドキュメントに署名し、結果を指定されたファイルパスに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | `[`SignOptions`](../../groupdocs.signature.options/signoptions)`でドキュメントに署名し、結果を指定されたファイルパスに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | `[`SignOptions`](../../groupdocs.signature.options/signoptions)`のコレクションでドキュメントに署名し、事前定義された[`SaveOptions`](../../groupdocs.signature.options/saveoptions)を使用して結果をストリームに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | `[`SignOptions`](../../groupdocs.signature.options/signoptions)`でドキュメントに署名し、事前定義された[`SaveOptions`](../../groupdocs.signature.options/saveoptions)を使用して結果をストリームに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | `[`SignOptions`](../../groupdocs.signature.options/signoptions)`のコレクションでドキュメントに署名し、事前定義された[`SaveOptions`](../../groupdocs.signature.options/saveoptions)を使用して結果を指定されたファイルパスに保存します。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | `[`SignOptions`](../../groupdocs.signature.options/signoptions)`でドキュメントに署名し、事前定義された[`SaveOptions`](../../groupdocs.signature.options/saveoptions)を使用して結果を指定されたファイルパスに保存します。 |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | ドキュメント内の渡された署名[`BaseSignature`](../../groupdocs.signature.domain/basesignature)を更新します。 |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | ドキュメント内の渡された署名群[`BaseSignature`](../../groupdocs.signature.domain/basesignature)を更新します。 |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | VerifyOptionsデータのリストでドキュメントの署名を検証します。 |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | 指定されたVerifyOptionsデータでドキュメントの署名を検証します。 |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | 利用可能なすべての検証オプションを使用してドキュメントの署名を検証し、指定された述語に基づいて結果をフィルタリングします。このメソッドはまず検証オプションに一致する署名を検索し、述語でフィルタリングした後、フィルタされた署名のみを検証します。 |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | 提供された検証オプションを使用してドキュメントの署名を検証し、指定された述語に基づいて結果をフィルタリングします。このメソッドはまず検証オプションに一致する署名を検索し、述語でフィルタリングした後、フィルタされた署名のみを検証します。 |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | 指定されたSignOptionsに基づいて署名プレビューを生成します。[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | 署名検索プロセスが完了したときに発生します。 |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | 署名検索プロセスの進行状況が変化したときに発生します。 |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | 署名検索プロセスが開始されたときに発生します。 |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | ドキュメント署名プロセスが完了したときに発生します。 |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | 文書署名プロセスの進行状況が変更されたときに発生します。 |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | 文書署名プロセスが開始されたときに発生します。 |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | 署名検証プロセスが完了したときに発生します。 |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | 署名検証プロセスの進行状況が変更されたときに発生します。 |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | 署名検証プロセスが開始されたときに発生します。 |

### 備考

**Learn more**

GroupDocs.Signature の機能の詳細: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### 関連項目

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
