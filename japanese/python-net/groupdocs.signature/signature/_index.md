---
title: "Signature クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメント署名プロセスを制御するメインクラスを表します。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

ドキュメント署名プロセスを制御するメインクラスを表します。

GroupDocs.Signature の機能の詳細はこちら：
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Signature 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | ストリームとして提供されたドキュメントで新しい Signature インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | ドキュメントストリームとロードオプションで新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | ストリームで提供されたドキュメントとオプションの [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) で新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | ドキュメントストリーム、ロードオプション、署名設定を使用して新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | ファイルパスで提供されたドキュメントで新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | ファイルパスで提供されたドキュメントとロードオプションで新しい Signature インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | ファイルパスで提供されたドキュメントとオプションの [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) で新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。 |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | ファイルパスで提供されたドキュメント、ロードオプション、署名設定を使用して新しい [`Signature`](/signature/python-net/groupdocs.signature/signature/) インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | 指定された [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) をドキュメントから削除します。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | 提供された署名リストをドキュメントから削除します。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | 指定されたタイプの署名をドキュメントから削除します。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | 指定された `SignatureType` リストの署名をドキュメントから削除します。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | 特定の署名 Id によって署名をドキュメントから削除します。 |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | 指定された署名をドキュメントから削除します。 |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | 署名オブジェクトが使用する内部リソースをクリーンアップします。 |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | ドキュメントページのプレビューを生成します。 |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | 指定された SignOptions に基づいて署名プレビューを生成します。 |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | ドキュメントページに関する情報を取得します：サイズ、最大ページ高さ、最大高さのページの幅。 |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | リストの [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) を使用してドキュメント内の署名を検索します。 |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | 提供された検索オプションを使用してドキュメント内の署名を検索し、指定された述語に基づいて結果をフィルタリングします。 |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | `SignatureType` の値でドキュメント内の指定された署名タイプを検索します。 |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | 利用可能なすべての検索オプションを使用してドキュメント内の署名を検索し、指定された述語に基づいて結果をフィルタリングします。 |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) を使用してドキュメントに署名し、結果をストリームに保存します。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) を使用してドキュメントに署名し、事前定義された [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) を使用して結果をストリームに保存します。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) のコレクションを使用してドキュメントに署名し、結果をストリームに保存します。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) のコレクションを使用してドキュメントに署名し、事前定義された [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) を使用して結果をストリームに保存します。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | SignOptions を使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) を使用してドキュメントに署名し、事前定義された [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) を使用して結果を指定されたファイルパスに保存します。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) のコレクションを使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。 |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) のコレクションを使用してドキュメントに署名し、事前定義された [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) を使用して結果を指定されたファイルパスに保存します。 |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | 渡された署名 BaseSignature をドキュメント内で更新します。 |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | 渡された署名 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) をドキュメント内で更新します。 |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | 指定された VerifyOptions データでドキュメントの署名を検証します。 |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | 提供された検証オプションを使用してドキュメントの署名を検証し、指定された述語に基づいて結果をフィルタリングします。 |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | VerifyOptions データのリストでドキュメントの署名を検証します。 |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | 提供された検証オプションを使用して文書の署名を検証し、指定された述語で結果をフィルタリングします。 |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
`Signature` を使用するタスクガイド：

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### 関連項目
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
