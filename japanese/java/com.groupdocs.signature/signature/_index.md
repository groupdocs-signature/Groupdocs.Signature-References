---
title: "署名"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメント署名プロセスを制御するメインクラスを表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

ドキュメント署名プロセスを制御するメインクラスを表します。

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | ストリームで提供されたドキュメントを使用して、[Signature](../../com.groupdocs.signature/signature) クラスの新しいインスタンスを初期化します。 |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | ストリームで提供されたドキュメントとロード オプションを使用して、[Signature](../../com.groupdocs.signature/signature) クラスの新しいインスタンスを初期化します |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | ストリームで提供されたドキュメントと [SignatureSettings](../../com.groupdocs.signature/signaturesettings) を使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します。 |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | ストリームで提供されたドキュメント、ロード オプションを使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) と設定 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | ファイル パスで提供されたドキュメントを使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します。 |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | ファイル パスで提供されたドキュメントと [Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | ファイル パスで提供されたドキュメントと [SignatureSettings](../../com.groupdocs.signature/signaturesettings) を使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します。 |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | ファイル パスで提供されたドキュメントを使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します、 |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) と [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) でドキュメントに署名し、結果をストリームに保存します。 |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) でドキュメントに署名し、事前定義された [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) を使用して結果をストリームに保存します。 |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) のコレクションでドキュメントに署名し、結果をストリームに保存します。 |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | コレクションの [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、事前定義された [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) を使用して結果をストリームに保存します。 |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。 |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、事前定義された [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) を使用して結果を指定されたファイルパスに保存します。 |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | コレクションの [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。 |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | コレクションの [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、事前定義された [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) を使用して結果を指定されたファイルパスに保存します。 |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | 指定された VerifyOptions データでドキュメントの署名を検証します。 |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | VerifyOptions データのリストでドキュメントの署名を検証します。 |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 提供された検証オプションとフィルターを使用してドキュメントの署名を検証します |
指定された述語によって成功した結果を取得します。
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 検証オプションのリストを使用してドキュメントの署名を検証し、フィルターを適用します |
指定された述語で成功した結果を取得します。
|
|  | [getDocumentInfo()](#getDocumentInfo--) | ドキュメントページの情報を取得します：サイズ、 |
最大ページ高さ、最大高さのページの幅。
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | ドキュメントページのプレビューを生成します。 |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) のリストでドキュメント内の署名を検索します。 |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | オプションのリストで署名を検索し、結果を述語でフィルタリングします。 |
|
|  | [search(Predicate<BaseSignature> predicate)](#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | ドキュメント内のすべてのタイプ（テキスト、画像、デジタル、バーコード、QRコード、メタデータ）の署名を検索します |
そしてそれらを述語でフィルタリングします。
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) オプションでドキュメント内の署名を検索します。 |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | ドキュメント内で指定されたタイプの署名を検索し、必要に応じて述語でフィルタリングします。 |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) の値でドキュメント内の正確なタイプの署名を検索します。 |
|
|  | [search(int[] signatureTypes)](#search-int...-) | [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) の値でドキュメント内の指定された署名タイプを検索します。 |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | ドキュメント内の渡された署名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を更新します。 |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | ドキュメント内の渡された署名群 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を更新します。 |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | ドキュメント内の渡された署名群 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を更新します。 |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | ドキュメント内の渡された署名群 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を更新します。 |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | ドキュメントから渡された署名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。 |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | ドキュメントから渡された署名リスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。 |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | ドキュメントから渡された署名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。 |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | ドキュメントから渡された署名リスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。 |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | ドキュメントから特定のタイプの署名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) を削除します。 |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | ドキュメントから特定のタイプリストに含まれる署名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) を削除します。 |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | ドキュメントから特定のタイプの署名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) を削除します。 |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | ドキュメントから特定のタイプリストに含まれる署名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) を削除します。 |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | ドキュメントから特定の署名IDによる署名を削除します。 |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | ドキュメントから渡された署名リスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。 |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | 指定された SignOptions に基づいて署名プレビューを生成します。 |
|
|  | [dispose()](#dispose--) | 内部リソースをクリーンアップするために IDisposable インターフェイスを実装します。 |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


ストリームで提供されたドキュメントを使用して、[Signature](../../com.groupdocs.signature/signature) クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | ドキュメントのコンテンツストリームです。 |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


ストリームで提供されたドキュメントとロード オプションを使用して、[Signature](../../com.groupdocs.signature/signature) クラスの新しいインスタンスを初期化します
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | ドキュメントのコンテンツストリームです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | ドキュメントのロードオプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


ストリームで提供されたドキュメントと [SignatureSettings](../../com.groupdocs.signature/signaturesettings) を使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | ドキュメントのコンテンツストリームです。 |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 署名設定です。 |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


ストリームで提供されたドキュメント、ロード オプションを使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) と設定 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.InputStream | ドキュメントのコンテンツストリームです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | ドキュメントのロードオプションです。 |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 署名設定です。 |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


ファイル パスで提供されたドキュメントを使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 絶対パスまたは相対パスのファイルパスです。 |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


ファイル パスで提供されたドキュメントと [Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 絶対パスまたは相対パスのファイルパスです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | ドキュメントのロードオプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


ファイル パスで提供されたドキュメントと [SignatureSettings](../../com.groupdocs.signature/signaturesettings) を使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 絶対パスまたは相対パスのファイルパスです。 |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 署名設定です。 |

<br />

*** ** * ** ***

 **Learn more** 

* 
* 

<br />

|

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


ファイル パスで提供されたドキュメントを使用して、[Signature](../../com.groupdocs.signature/signature) クラスのインスタンスを初期化します、
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) と [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 絶対パスまたは相対パスのファイルパスです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | ドキュメントのロードオプションです。 |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 署名設定です。 |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) でドキュメントに署名し、結果をストリームに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 署名オプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) でドキュメントに署名し、事前定義された [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) を使用して結果をストリームに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 署名オプションです。 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存オプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) のコレクションでドキュメントに署名し、結果をストリームに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 署名オプションのリストです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


コレクションの [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、事前定義された [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) を使用して結果をストリームに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 署名オプションのリストです。 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存オプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 署名オプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、事前定義された [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) を使用して結果を指定されたファイルパスに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 署名オプションです。 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存オプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


コレクションの [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 署名オプションのリストです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


コレクションの [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) を使用してドキュメントに署名し、事前定義された [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) を使用して結果を指定されたファイルパスに保存します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 署名オプションのリストです。 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存オプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


指定された VerifyOptions データでドキュメントの署名を検証します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | 署名検証オプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


VerifyOptions データのリストでドキュメントの署名を検証します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | 署名検証オプションコレクションです。 [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection) のインスタンスです。 |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)
```


提供された検証オプションとフィルターを使用してドキュメントの署名を検証します
指定された述語によって成功した結果を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | 署名検証オプションです。 |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 検証済み署名のリストに適用されるフィルタ述語です。 |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - 検証に成功し、述語を満たした署名のリスト。

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


検証オプションのリストを使用してドキュメントの署名を検証し、フィルターを適用します
指定された述語で成功した結果を取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | 署名検証オプションのリストです。 |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 検証済み署名のリストに適用されるフィルタ述語です。 |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - 検証に成功し、述語を満たした署名のリスト。

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


ドキュメントページの情報を取得します：サイズ、
最大ページ高さ、最大高さのページの幅。


**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

<br />

*** ** * ** ***

**Learn more**

* Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java](../https://docs.groupdocs.com/signature/java/get-document-information/)

<br />


### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


ドキュメントページのプレビューを生成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | プレビューオプションです。 |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/generate-document-pages-preview/)

<br />

|

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


[SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) のリストでドキュメント内の署名を検索します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | 検索オプションのコレクションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.

### search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)
```


オプションのリストで署名を検索し、結果を述語でフィルタリングします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | 検索オプションのリストです。 |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 結果の署名をフィルタリングするために使用される述語。 |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### search(Predicate<BaseSignature> predicate) {#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> search(Predicate<BaseSignature> predicate)
```


ドキュメント内のすべてのタイプ（テキスト、画像、デジタル、バーコード、QRコード、メタデータ）の署名を検索します
そしてそれらを述語でフィルタリングします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 見つかった署名のリストに適用するフィルタ述語です。 |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - 提供された述語を満たす [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) インスタンスのリストを返します。

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


[SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) オプションでドキュメント内の署名を検索します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | 検索オプションです。 |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - 見つかった署名のリストを返します。

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


ドキュメント内で指定されたタイプの署名を検索し、必要に応じて述語でフィルタリングします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) のジェネリック型パラメータです。 |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | 署名検索のオプションです。 |
|
|  | predicate | java.util.function.Predicate<T> | 検索後に適用されるオプションの述語フィルタです。null の可能性があります。 |
|

**Returns:**
java.util.List<T> - 見つかった署名のリストで、オプションで述語によりフィルタリングされます。

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


[SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) の値でドキュメント内の正確なタイプの署名を検索します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | 検索する署名のタイプです。 |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - 正確なタイプの見つかった署名のリストを返します。

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


[SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) の値でドキュメント内の指定された署名タイプを検索します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatureTypes | int[] | 検索する署名の1つまたは複数のタイプです。 |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.

### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


ドキュメント内の渡された署名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を更新します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | ドキュメント内で更新される署名オブジェクトです。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - 操作が成功した場合に true を返します。

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


ドキュメント内の渡された署名群 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を更新します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | 署名 | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | ドキュメント内で更新する署名の一覧。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


ドキュメント内の渡された署名群 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を更新します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | 署名 | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | ドキュメント内で更新する署名の一覧。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


ドキュメント内の渡された署名群 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を更新します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | ドキュメント内で更新される署名オブジェクトです。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - 成功裏に更新された署名と失敗した署名の一覧を含む UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) を返します。

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


ドキュメントから渡された署名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | ドキュメントから削除される署名オブジェクト。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - 操作が成功した場合に true を返します。

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


ドキュメントから渡された署名リスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | 署名 | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | ドキュメントから削除する署名の一覧。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


ドキュメントから渡された署名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | ドキュメントから削除される署名オブジェクト。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - 操作が成功した場合に true を返します。

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


ドキュメントから渡された署名リスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | 署名 | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | ドキュメントから削除する署名の一覧。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


ドキュメントから特定のタイプの署名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) を削除します。
Sign メソッドで追加され、Signatures としてマークされた署名のみ
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) は削除されます。
次の署名タイプがサポートされています: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | signatureType | int | ドキュメントから削除される署名のタイプ。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


ドキュメントから特定のタイプリストに含まれる署名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) を削除します。
Sign メソッドで追加され、Signatures としてマークされた署名のみ
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) は削除されます。
次の署名タイプがサポートされています: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ドキュメント | java.io.OutputStream | 出力ドキュメントストリームです。 |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | ドキュメントから削除される署名タイプの一覧。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


ドキュメントから特定のタイプの署名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) を削除します。
Sign メソッドで追加され、Signatures としてマークされた署名のみ
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) は削除されます。
次の署名タイプがサポートされています: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | signatureType | int | ドキュメントから削除される署名のタイプ。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


ドキュメントから特定のタイプリストに含まれる署名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) を削除します。
Sign メソッドで追加され、Signatures としてマークされた署名のみ
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) は削除されます。
次の署名タイプがサポートされています: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | 出力ファイルパスです。 |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | ドキュメントから削除される署名タイプの一覧。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


ドキュメントから特定の署名IDによる署名を削除します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatureId | java.lang.String | ドキュメントから削除される署名の Id。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - 操作が成功した場合に true を返します。

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


ドキュメントから渡された署名リスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) を削除します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | ドキュメントから削除される署名の識別子の一覧。 |

<br />

*** ** * ** ***

**Learn more** /// /// /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents) /// /// /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting) /// /// ///
|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


指定された SignOptions に基づいて署名プレビューを生成します。 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | 指定された SignOptions を使用したプレビュ署名。 [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


内部リソースをクリーンアップするために IDisposable インターフェイスを実装します。


