---
title: "Signature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示控制文档签名过程的主类。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

表示控制文档签名过程的主类。

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | 初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用流提供的文档。 |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | 初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用流提供的文档和加载选项 |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | 初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用流提供的文档和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。 |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | 初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用流提供的文档、加载选项 |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 和设置 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | 初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用文件路径提供的文档。 |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | 初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用文件路径提供的文档和 |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | 初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用文件路径提供的文档和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。 |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | 初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用文件路径提供的文档， |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | 使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中。 |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | 使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中，使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)。 |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | 使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中。 |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | 使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中，使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)。 |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | 使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。 |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | 使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径，使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)。 |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | 使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。 |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | 使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径，使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)。 |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | 使用给定的 VerifyOptions 数据验证文档签名。 |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | 使用 VerifyOptions 数据列表验证文档签名。 |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 使用提供的验证选项和过滤器验证文档签名 |
通过指定的谓词筛选成功的结果。
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 使用验证选项列表验证文档签名，并筛选 |
成功的结果通过指定的谓词。
|
|  | [getDocumentInfo()](#getDocumentInfo--) | 获取文档页面的信息：它们的尺寸， |
最大页面高度，以及具有最大高度的页面的宽度。
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | 生成文档页面预览。 |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | 通过 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 列表在文档中搜索签名。 |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | 通过选项列表搜索签名，并使用谓词过滤结果。 |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | 通过 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 选项在文档中搜索签名。 |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | 在文档中搜索指定类型的签名，可选地使用谓词进行过滤。 |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | 通过 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 值在文档中搜索精确类型的签名。 |
|
|  | [search(int[] signatureTypes)](#search-int...-) | 通过 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 值在文档中搜索指定的签名类型。 |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | 在文档中更新传入的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 在文档中更新已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 在文档中更新已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | 在文档中更新已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | 从文档中删除已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 从文档中删除已通过的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | 从文档中删除已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 从文档中删除已通过的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | 从文档中删除特定类型的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。 |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | 从文档中删除特定类型列表的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。 |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | 从文档中删除特定类型的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。 |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | 从文档中删除特定类型列表的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。 |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | 从文档中按特定签名 Id 删除签名。 |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | 从文档中删除已通过的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | 根据给定的 SignOptions 生成签名预览。 |
|
|  | [dispose()](#dispose--) | 实现 IDisposable 接口以清理内部资源 |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用流提供的文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 文档内容流。 |

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


初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用流提供的文档和加载选项
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 文档内容流。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 文档加载选项。 |

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


初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用流提供的文档和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 文档内容流。 |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 签名设置。 |

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


初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用流提供的文档、加载选项
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 和设置 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 文档内容流。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 文档加载选项。 |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 签名设置。 |

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


初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用文件路径提供的文档。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 绝对或相对文件路径。 |

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


初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用文件路径提供的文档和
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 绝对或相对文件路径。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 文档加载选项。 |

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


初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用文件路径提供的文档和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 绝对或相对文件路径。 |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 签名设置。 |

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


初始化一个新的 [Signature](../../com.groupdocs.signature/signature) 类实例，使用文件路径提供的文档，
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 绝对或相对文件路径。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 文档加载选项。 |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 签名设置。 |

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


使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 签名选项。 |

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


使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中，使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 签名选项。 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存选项。 |

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


使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 签名选项列表。 |

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


使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中，使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 签名选项列表。 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存选项。 |

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


使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 签名选项。 |

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


使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径，使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 签名选项。 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存选项。 |

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


使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 签名选项列表。 |

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


使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径，使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 签名选项列表。 |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存选项。 |

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


使用给定的 VerifyOptions 数据验证文档签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | 签名验证选项。 |

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


使用 VerifyOptions 数据列表验证文档签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | 签名验证选项集合。实例为 [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection)。 |

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


使用提供的验证选项和过滤器验证文档签名
通过指定的谓词筛选成功的结果。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | 签名验证选项。 |
|
|  | 谓词 | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 在已验证签名列表上应用的过滤谓词。 |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - 已通过验证并满足谓词的签名列表。

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


使用验证选项列表验证文档签名，并筛选
成功的结果通过指定的谓词。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | 签名验证选项列表。 |
|
|  | 谓词 | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 在已验证签名列表上应用的过滤谓词。 |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - 已通过验证并满足谓词的签名列表。

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


获取文档页面的信息：它们的尺寸，
最大页面高度，以及具有最大高度的页面的宽度。


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


生成文档页面预览。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | 预览选项。 |

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


通过 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 列表在文档中搜索签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | 搜索选项集合。 |

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


通过选项列表搜索签名，并使用谓词过滤结果。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | 搜索选项列表。 |
|
|  | 谓词 | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | 用于过滤结果签名的谓词。 |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


通过 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 选项在文档中搜索签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | 搜索选项。 |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - 返回找到的签名列表。

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


在文档中搜索指定类型的签名，可选地使用谓词进行过滤。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) 的通用类型参数。 |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | 签名搜索选项。 |
|
|  | 谓词 | java.util.function.Predicate<T> | 搜索后应用的可选谓词过滤器。可能为 null。 |
|

**Returns:**
java.util.List<T> - 找到的签名列表，可选地通过谓词过滤。

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


通过 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 值在文档中搜索精确类型的签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | 要搜索的签名类型。 |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - 返回具有精确类型的找到的签名列表。

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


通过 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 值在文档中搜索指定的签名类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureTypes | int[] | 要查找的一个或多个签名类型。 |

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


在文档中更新传入的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 文档中要更新的签名对象。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - 如果操作成功则返回 true。

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


在文档中更新已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | 签名 | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 文档中要更新的签名列表。 |

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


在文档中更新已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | 签名 | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 文档中要更新的签名列表。 |

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


在文档中更新已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 文档中要更新的签名对象。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - 返回 UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) ，其中包含成功更新的签名列表和失败的签名。

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


从文档中删除已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 要从文档中移除的 Signature 对象。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - 如果操作成功则返回 true。

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


从文档中删除已通过的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | 签名 | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 要从文档中移除的签名列表。 |

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


从文档中删除已通过的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 要从文档中移除的 Signature 对象。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - 如果操作成功则返回 true。

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


从文档中删除已通过的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | 签名 | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 要从文档中移除的签名列表。 |

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


从文档中删除特定类型的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。
仅限由 Sign 方法添加并标记为 Signatures 的签名
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) 将被移除。
支持以下签名类型：Text、Image、Digital、Barcode、QR-Code


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | signatureType | int | 要从文档中移除的签名类型。 |

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


从文档中删除特定类型列表的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。
仅限由 Sign 方法添加并标记为 Signatures 的签名
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) 将被移除。
支持以下签名类型：Text、Image、Digital、Barcode、QR-Code


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 输出文档流。 |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | 要从文档中移除的签名类型列表。 |

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


从文档中删除特定类型的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。
仅限由 Sign 方法添加并标记为 Signatures 的签名
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) 将被移除。
支持以下签名类型：Text、Image、Digital、Barcode、QR-Code


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | signatureType | int | 要从文档中移除的签名类型。 |

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


从文档中删除特定类型列表的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。
仅限由 Sign 方法添加并标记为 Signatures 的签名
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) 将被移除。
支持以下签名类型：Text、Image、Digital、Barcode、QR-Code


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文件路径 | java.lang.String | 输出文件路径。 |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | 要从文档中移除的签名类型列表。 |

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


从文档中按特定签名 Id 删除签名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureId | java.lang.String | 要从文档中移除的签名 Id。 |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - 如果操作成功则返回 true。

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


从文档中删除已通过的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | 要从文档中移除的签名标识符列表。 |

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


根据给定的 SignOptions 生成 Signature 预览。 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | 使用给定的 SignOptions 的预览签名。 [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


实现 IDisposable 接口以清理内部资源


