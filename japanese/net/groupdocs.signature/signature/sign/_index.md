---
title: "Sign"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "SignOptionsgroupdocs.signature.options/signoptions を使用してドキュメントに署名し、結果をストリームに保存します。"
type: docs
weight: 160
url: /ja/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) を使用してドキュメントに署名し、結果をストリームに保存します。

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 出力ドキュメントストリーム。 |
| signOptions | SignOptions | 署名オプション。 |

### 戻り値

[`SignResult`](../../../groupdocs.signature.domain/signresult) のインスタンスを返します。新しく作成された署名のリストが含まれます。

### 備考

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) を使用してドキュメントに署名し、事前定義された [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) で結果をストリームに保存します。

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 出力ドキュメントストリーム。 |
| signOptions | SignOptions | 署名オプション。 |
| saveOptions | SaveOptions | 保存オプション。 |

### 戻り値

[`SignResult`](../../../groupdocs.signature.domain/signresult) のインスタンスを返します。新しく作成された署名のリストが含まれます。

### 備考

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) のコレクションを使用してドキュメントに署名し、結果をストリームに保存します。

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 出力ドキュメントストリーム。 |
| signOptionsList | List`1 | 署名オプションの一覧です。 |

### 戻り値

[`SignResult`](../../../groupdocs.signature.domain/signresult) のインスタンスを返します。新しく作成された署名のリストが含まれます。

### 備考

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

ドキュメントに [`SignOptions`](../../../groupdocs.signature.options/signoptions) のコレクションで署名し、事前定義された [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) を使用して結果をストリームに保存します。

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 出力ドキュメントストリーム。 |
| signOptionsList | List`1 | 署名オプションの一覧です。 |
| saveOptions | SaveOptions | 保存オプション。 |

### 戻り値

[`SignResult`](../../../groupdocs.signature.domain/signresult) のインスタンスを返します。新しく作成された署名のリストが含まれます。

### 備考

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) を使用してドキュメントに署名し、結果を指定されたファイルパスに保存します。

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 出力ファイルパスです。 |
| signOptions | SignOptions | 署名オプション。 |

### 戻り値

[`SignResult`](../../../groupdocs.signature.domain/signresult) のインスタンスを返します。新しく作成された署名のリストが含まれます。

### 備考

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) を使用してドキュメントに署名し、事前定義された [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) とともに結果を指定されたファイルパスに保存します。

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 出力ファイルパスです。 |
| signOptions | SignOptions | 署名オプション。 |
| saveOptions | SaveOptions | 保存オプション。 |

### 戻り値

[`SignResult`](../../../groupdocs.signature.domain/signresult) のインスタンスを返します。新しく作成された署名のリストが含まれます。

### 備考

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) のコレクションでドキュメントに署名し、結果を指定されたファイルパスに保存します。

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 出力ファイルパスです。 |
| signOptionsList | List`1 | 署名オプションの一覧です。 |

### 戻り値

[`SignResult`](../../../groupdocs.signature.domain/signresult) のインスタンスを返します。新しく作成された署名のリストが含まれます。

### 備考

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

[`SignOptions`](../../../groupdocs.signature.options/signoptions) のコレクションでドキュメントに署名し、事前定義された [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) とともに結果を指定されたファイルパスに保存します。

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 出力ファイルパスです。 |
| signOptionsList | List`1 | 署名オプションの一覧です。 |
| saveOptions | SaveOptions | 保存オプション。 |

### 戻り値

[`SignResult`](../../../groupdocs.signature.domain/signresult) のインスタンスを返します。新しく作成された署名のリストが含まれます。

### 備考

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 関連項目

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
