---
title: Sign
second_title: GroupDocs.Signature for .NET API 参考
description: 用SignOptionsgroupdocs.signature.options/signoptions并将结果保存到流中
type: docs
weight: 160
url: /zh/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

用[`SignOptions`](../../../groupdocs.signature.options/signoptions)并将结果保存到流中。

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 输出文档流。 |
| signOptions | SignOptions | 签名选项。 |

### 返回值

返回实例[`SignResult`](../../../groupdocs.signature.domain/signresult)带有新创建的签名列表。

### 评论

**学到更多**

* 有关 GroupDocs.Signature 支持的电子签名类型的更多信息： [GroupDocs.Signature 支持的电子签名类型](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* 更多关于 C# 中的电子签名文档： [如何使用 GroupDocs.Signature 对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/Signing)

### 也可以看看

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

用[`SignOptions`](../../../groupdocs.signature.options/signoptions)并将结果保存到预定义的流中[`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 输出文档流。 |
| signOptions | SignOptions | 签名选项。 |
| saveOptions | SaveOptions | 保存选项。 |

### 返回值

返回实例[`SignResult`](../../../groupdocs.signature.domain/signresult)带有新创建的签名列表。

### 评论

**学到更多**

* 有关 GroupDocs.Signature 支持的电子签名类型的更多信息： [GroupDocs.Signature 支持的电子签名类型](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* 更多关于 C# 中的电子签名文档： [如何使用 GroupDocs.Signature 对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/Signing)
* 更多关于如何保存电子签名文件和自定义保存过程： [如何使用 GroupDocs.Signature 在保存时自定义电子签名文档](https://docs.groupdocs.com/display/signaturenet/Saving)

### 也可以看看

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

用集合标志文档[`SignOptions`](../../../groupdocs.signature.options/signoptions)并将结果保存到流中。

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 输出文档流。 |
| signOptionsList | List`1 | 签名选项列表。 |

### 返回值

返回实例[`SignResult`](../../../groupdocs.signature.domain/signresult)带有新创建的签名列表。

### 评论

**学到更多**

* 有关 GroupDocs.Signature 支持的电子签名类型的更多信息： [GroupDocs.Signature 支持的电子签名类型](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* 更多关于 C# 中的电子签名文档： [如何使用 GroupDocs.Signature 对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/Signing)

### 也可以看看

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

用集合标志文档[`SignOptions`](../../../groupdocs.signature.options/signoptions)并将结果保存到预定义的流中[`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 输出文档流。 |
| signOptionsList | List`1 | 签名选项列表。 |
| saveOptions | SaveOptions | 保存选项。 |

### 返回值

返回实例[`SignResult`](../../../groupdocs.signature.domain/signresult)带有新创建的签名列表。

### 评论

**学到更多**

* 有关 GroupDocs.Signature 支持的电子签名类型的更多信息： [GroupDocs.Signature 支持的电子签名类型](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* 更多关于 C# 中的电子签名文档： [如何使用 GroupDocs.Signature 对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/Signing)
* 更多关于如何保存电子签名文件和自定义保存过程： [如何使用 GroupDocs.Signature 在保存时自定义电子签名文档](https://docs.groupdocs.com/display/signaturenet/Saving)

### 也可以看看

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

用[`SignOptions`](../../../groupdocs.signature.options/signoptions)并将结果保存到指定的文件路径。

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 输出文件路径。 |
| signOptions | SignOptions | 签名选项。 |

### 返回值

返回实例[`SignResult`](../../../groupdocs.signature.domain/signresult)带有新创建的签名列表。

### 评论

**学到更多**

* 有关 GroupDocs.Signature 支持的电子签名类型的更多信息： [GroupDocs.Signature 支持的电子签名类型](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* 更多关于 C# 中的电子签名文档： [如何使用 GroupDocs.Signature 对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/Signing)

### 也可以看看

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

用[`SignOptions`](../../../groupdocs.signature.options/signoptions)并将结果保存到具有预定义的指定文件路径[`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 输出文件路径。 |
| signOptions | SignOptions | 签名选项。 |
| saveOptions | SaveOptions | 保存选项。 |

### 返回值

返回实例[`SignResult`](../../../groupdocs.signature.domain/signresult)带有新创建的签名列表。

### 评论

**学到更多**

* 有关 GroupDocs.Signature 支持的电子签名类型的更多信息： [GroupDocs.Signature 支持的电子签名类型](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* 更多关于 C# 中的电子签名文档： [如何使用 GroupDocs.Signature 对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/Signing)
* 更多关于如何保存电子签名文件和自定义保存过程： [如何使用 GroupDocs.Signature 在保存时自定义电子签名文档](https://docs.groupdocs.com/display/signaturenet/Saving)

### 也可以看看

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

用集合标志文档[`SignOptions`](../../../groupdocs.signature.options/signoptions)并将结果保存到指定的文件路径。

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 输出文件路径。 |
| signOptionsList | List`1 | 签名选项列表。 |

### 返回值

返回实例[`SignResult`](../../../groupdocs.signature.domain/signresult)带有新创建的签名列表。

### 评论

**学到更多**

* 有关 GroupDocs.Signature 支持的电子签名类型的更多信息： [GroupDocs.Signature 支持的电子签名类型](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* 更多关于 C# 中的电子签名文档： [如何使用 GroupDocs.Signature 对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/Signing)

### 也可以看看

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

用集合标志文档[`SignOptions`](../../../groupdocs.signature.options/signoptions)并将结果保存到具有预定义的指定文件路径[`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 输出文件路径。 |
| signOptionsList | List`1 | 签名选项列表。 |
| saveOptions | SaveOptions | 保存选项。 |

### 返回值

返回实例[`SignResult`](../../../groupdocs.signature.domain/signresult)带有新创建的签名列表。

### 评论

**学到更多**

* 有关 GroupDocs.Signature 支持的电子签名类型的更多信息： [GroupDocs.Signature 支持的电子签名类型](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* 更多关于 C# 中的电子签名文档： [如何使用 GroupDocs.Signature 对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/Signing)
* 更多关于如何保存电子签名文件和自定义保存过程： [如何使用 GroupDocs.Signature 在保存时自定义电子签名文档](https://docs.groupdocs.com/display/signaturenet/Saving)

### 也可以看看

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* 命名空间 [GroupDocs.Signature](../../signature)
* 部件 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
