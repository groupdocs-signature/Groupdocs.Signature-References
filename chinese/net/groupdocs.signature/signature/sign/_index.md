---
title: "Sign"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "使用 SignOptionsgroupdocs.signature.options/signoptions 对文档进行签名并将结果保存到流中。"
type: docs
weight: 160
url: /zh/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

使用 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 对文档进行签名并将结果保存到流中。

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 输出文档流。 |
| signOptions | SignOptions | 签名选项。 |

### 返回值

返回 [`SignResult`](../../../groupdocs.signature.domain/signresult) 的实例，其中包含新创建的签名列表。

### 备注

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 另请参见

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

使用 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 对文档进行签名，并使用预定义的 [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) 将结果保存到流中。

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 输出文档流。 |
| signOptions | SignOptions | 签名选项。 |
| saveOptions | SaveOptions | 保存选项。 |

### 返回值

返回 [`SignResult`](../../../groupdocs.signature.domain/signresult) 的实例，其中包含新创建的签名列表。

### 备注

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 另请参见

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

使用 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 的集合对文档进行签名，并将结果保存到流中。

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 输出文档流。 |
| signOptionsList | List`1 | 签名选项列表。 |

### 返回值

返回 [`SignResult`](../../../groupdocs.signature.domain/signresult) 的实例，其中包含新创建的签名列表。

### 备注

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 另请参见

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

使用 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 的集合对文档进行签名，并使用预定义的 [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) 将结果保存到流中。

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 输出文档流。 |
| signOptionsList | List`1 | 签名选项列表。 |
| saveOptions | SaveOptions | 保存选项。 |

### 返回值

返回 [`SignResult`](../../../groupdocs.signature.domain/signresult) 的实例，其中包含新创建的签名列表。

### 备注

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 另请参见

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

使用 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 输出文件路径。 |
| signOptions | SignOptions | 签名选项。 |

### 返回值

返回 [`SignResult`](../../../groupdocs.signature.domain/signresult) 的实例，其中包含新创建的签名列表。

### 备注

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 另请参见

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

使用 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 对文档进行签名，并使用预定义的 [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) 将结果保存到指定的文件路径。

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 输出文件路径。 |
| signOptions | SignOptions | 签名选项。 |
| saveOptions | SaveOptions | 保存选项。 |

### 返回值

返回 [`SignResult`](../../../groupdocs.signature.domain/signresult) 的实例，其中包含新创建的签名列表。

### 备注

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 另请参见

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

使用 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 的集合对文档进行签名，并将结果保存到指定的文件路径。

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 输出文件路径。 |
| signOptionsList | List`1 | 签名选项列表。 |

### 返回值

返回 [`SignResult`](../../../groupdocs.signature.domain/signresult) 的实例，其中包含新创建的签名列表。

### 备注

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### 另请参见

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

使用 [`SignOptions`](../../../groupdocs.signature.options/signoptions) 的集合对文档进行签名，并使用预定义的 [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) 将结果保存到指定的文件路径。

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 输出文件路径。 |
| signOptionsList | List`1 | 签名选项列表。 |
| saveOptions | SaveOptions | 保存选项。 |

### 返回值

返回 [`SignResult`](../../../groupdocs.signature.domain/signresult) 的实例，其中包含新创建的签名列表。

### 备注

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### 另请参见

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
