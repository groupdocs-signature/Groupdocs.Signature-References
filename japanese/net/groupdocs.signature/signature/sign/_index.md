---
title: Sign
second_title: GroupDocs.Signature for .NET API リファレンス
description: でドキュメントに署名しますSignOptionsgroupdocs.signature.options/signoptions結果をストリームに保存します
type: docs
weight: 160
url: /ja/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

でドキュメントに署名します[`SignOptions`](../../../groupdocs.signature.options/signoptions)結果をストリームに保存します。

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 出力ドキュメント ストリーム。 |
| signOptions | SignOptions | 署名オプション。 |

### 戻り値

のインスタンスを返します[`SignResult`](../../../groupdocs.signature.domain/signresult)新しく作成された署名のリスト付き。

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされている電子署名の種類の詳細: [GroupDocs.Signature でサポートされている電子署名の種類](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C# でドキュメントに電子署名する方法の詳細: [GroupDocs.Signature を使用してドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/Signing)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

でドキュメントに署名します[`SignOptions`](../../../groupdocs.signature.options/signoptions)定義済みのストリームに結果を保存します[`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 出力ドキュメント ストリーム。 |
| signOptions | SignOptions | 署名オプション。 |
| saveOptions | SaveOptions | 保存オプション。 |

### 戻り値

のインスタンスを返します[`SignResult`](../../../groupdocs.signature.domain/signresult)新しく作成された署名のリスト付き。

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされている電子署名の種類の詳細: [GroupDocs.Signature でサポートされている電子署名の種類](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C# でドキュメントに電子署名する方法の詳細: [GroupDocs.Signature を使用してドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/Signing)
* 電子的に署名されたドキュメントを保存し、保存プロセスをカスタマイズする方法の詳細: [GroupDocs.Signature を使用して保存時に電子署名されたドキュメントをカスタマイズする方法](https://docs.groupdocs.com/display/signaturenet/Saving)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

のコレクションでドキュメントに署名します[`SignOptions`](../../../groupdocs.signature.options/signoptions)結果をストリームに保存します。

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 出力ドキュメント ストリーム。 |
| signOptionsList | List`1 | 署名オプションのリスト。 |

### 戻り値

のインスタンスを返します[`SignResult`](../../../groupdocs.signature.domain/signresult)新しく作成された署名のリスト付き。

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされている電子署名の種類の詳細: [GroupDocs.Signature でサポートされている電子署名の種類](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C# でドキュメントに電子署名する方法の詳細: [GroupDocs.Signature を使用してドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/Signing)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

のコレクションでドキュメントに署名します[`SignOptions`](../../../groupdocs.signature.options/signoptions)定義済みのストリームに結果を保存します[`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 出力ドキュメント ストリーム。 |
| signOptionsList | List`1 | 署名オプションのリスト。 |
| saveOptions | SaveOptions | 保存オプション。 |

### 戻り値

のインスタンスを返します[`SignResult`](../../../groupdocs.signature.domain/signresult)新しく作成された署名のリスト付き。

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされている電子署名の種類の詳細: [GroupDocs.Signature でサポートされている電子署名の種類](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C# でドキュメントに電子署名する方法の詳細: [GroupDocs.Signature を使用してドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/Signing)
* 電子的に署名されたドキュメントを保存し、保存プロセスをカスタマイズする方法の詳細: [GroupDocs.Signature を使用して保存時に電子署名されたドキュメントをカスタマイズする方法](https://docs.groupdocs.com/display/signaturenet/Saving)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

でドキュメントに署名します[`SignOptions`](../../../groupdocs.signature.options/signoptions)結果を指定したファイル パスに保存します。

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 出力ファイルのパス。 |
| signOptions | SignOptions | 署名オプション。 |

### 戻り値

のインスタンスを返します[`SignResult`](../../../groupdocs.signature.domain/signresult)新しく作成された署名のリスト付き。

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされている電子署名の種類の詳細: [GroupDocs.Signature でサポートされている電子署名の種類](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C# でドキュメントに電子署名する方法の詳細: [GroupDocs.Signature を使用してドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/Signing)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

でドキュメントに署名します[`SignOptions`](../../../groupdocs.signature.options/signoptions)事前定義された指定されたファイルパスに結果を保存します[`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 出力ファイルのパス。 |
| signOptions | SignOptions | 署名オプション。 |
| saveOptions | SaveOptions | 保存オプション。 |

### 戻り値

のインスタンスを返します[`SignResult`](../../../groupdocs.signature.domain/signresult)新しく作成された署名のリスト付き。

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされている電子署名の種類の詳細: [GroupDocs.Signature でサポートされている電子署名の種類](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C# でドキュメントに電子署名する方法の詳細: [GroupDocs.Signature を使用してドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/Signing)
* 電子的に署名されたドキュメントを保存し、保存プロセスをカスタマイズする方法の詳細: [GroupDocs.Signature を使用して保存時に電子署名されたドキュメントをカスタマイズする方法](https://docs.groupdocs.com/display/signaturenet/Saving)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

のコレクションでドキュメントに署名します[`SignOptions`](../../../groupdocs.signature.options/signoptions)結果を指定したファイル パスに保存します。

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 出力ファイルのパス。 |
| signOptionsList | List`1 | 署名オプションのリスト。 |

### 戻り値

のインスタンスを返します[`SignResult`](../../../groupdocs.signature.domain/signresult)新しく作成された署名のリスト付き。

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされている電子署名の種類の詳細: [GroupDocs.Signature でサポートされている電子署名の種類](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C# でドキュメントに電子署名する方法の詳細: [GroupDocs.Signature を使用してドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/Signing)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

のコレクションでドキュメントに署名します[`SignOptions`](../../../groupdocs.signature.options/signoptions)事前定義された指定されたファイルパスに結果を保存します[`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 出力ファイルのパス。 |
| signOptionsList | List`1 | 署名オプションのリスト。 |
| saveOptions | SaveOptions | 保存オプション。 |

### 戻り値

のインスタンスを返します[`SignResult`](../../../groupdocs.signature.domain/signresult)新しく作成された署名のリスト付き。

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされている電子署名の種類の詳細: [GroupDocs.Signature でサポートされている電子署名の種類](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C# でドキュメントに電子署名する方法の詳細: [GroupDocs.Signature を使用してドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/Signing)
* 電子的に署名されたドキュメントを保存し、保存プロセスをカスタマイズする方法の詳細: [GroupDocs.Signature を使用して保存時に電子署名されたドキュメントをカスタマイズする方法](https://docs.groupdocs.com/display/signaturenet/Saving)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 名前空間 [GroupDocs.Signature](../../signature)
* 組み立て [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
