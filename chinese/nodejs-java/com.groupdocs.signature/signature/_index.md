---
title: "签名"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示控制文档签名过程的主类。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

表示控制文档签名过程的主类。

--------------------

**Learn more**

 *  More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide][]


[GroupDocs.Signature Developer Guide]: https://docs.groupdocs.com/display/signaturenet/Developer+Guide
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | 使用流提供的文档初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。 |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | 使用流提供的文档和加载选项 LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。 |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | 使用流提供的文档和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。 |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | 使用流提供的文档、加载选项 LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 和设置 [SignatureSettings](../../com.groupdocs.signature/signaturesettings) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。 |
| [Signature(String filePath)](#Signature-java.lang.String-) | 使用文件路径提供的文档初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。 |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | 使用文件路径提供的文档和加载选项 LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。 |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | 使用文件路径提供的文档和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。 |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | 使用文件路径提供的文档、LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | 使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中。 |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | 使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) 将结果保存到流中。 |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | 使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中。 |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | 使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) 将结果保存到流中。 |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | 使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。 |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | 使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) 将结果保存到指定的文件路径。 |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | 使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。 |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | 使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) 将结果保存到指定的文件路径。 |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | 使用给定的 VerifyOptions 数据验证文档签名。 |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | 使用 VerifyOptions 数据列表验证文档签名。 |
| [getDocumentInfo()](#getDocumentInfo--) | 获取文档页面的信息：它们的尺寸、最大页面高度以及具有最大高度的页面的宽度。 |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | 生成文档页面预览。 |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | 通过 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 列表在文档中搜索签名。 |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | 通过 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 选项在文档中搜索签名。 |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | 通过 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 值在文档中搜索确切类型的签名。 |
| [search(int[] signatureTypes)](#search-int...-) | 通过 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 值在文档中搜索指定的签名类型。 |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | 在文档中更新传入的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 在文档中更新传入的签名集合 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 在文档中更新传入的签名集合 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | 在文档中更新传入的签名集合 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | 从文档中删除传入的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 从文档中删除传入的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | 从文档中删除传入的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | 从文档中删除传入的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | 从文档中删除特定类型的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。 |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | 从文档中删除特定类型列表的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。 |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | 从文档中删除特定类型的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。 |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | 从文档中删除特定类型列表的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。 |
| [delete(String signatureId)](#delete-java.lang.String-) | 从文档中通过特定的签名 Id 删除签名。 |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | 从文档中删除传入的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | 根据给定的 SignOptions 生成签名预览。 |
| [dispose()](#dispose--) | 实现 IDisposable 接口以清理内部资源 |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


使用流提供的文档初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 文档内容流。 |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


使用流提供的文档和加载选项 LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.InputStream | 文档内容流。 |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 文档加载选项。 |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


使用流提供的文档和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.InputStream | 文档内容流。 |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 签名设置。 |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


使用流提供的文档、加载选项 LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 和设置 [SignatureSettings](../../com.groupdocs.signature/signaturesettings) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.InputStream | 文档内容流。 |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 文档加载选项。 |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 签名设置。 |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


使用文件路径提供的文档初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 绝对或相对文件路径。 |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


使用文件路径提供的文档和加载选项 LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 绝对或相对文件路径。 |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 文档加载选项。 |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


使用文件路径提供的文档和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 绝对或相对文件路径。 |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 签名设置。 |

--------------------

 **Learn more** 

 *  
 *   |

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


使用文件路径提供的文档、LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) 和 [SignatureSettings](../../com.groupdocs.signature/signaturesettings) 初始化 [Signature](../../com.groupdocs.signature/signature) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 绝对或相对文件路径。 |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | 文档加载选项。 |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | 签名设置。 |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并将结果保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.OutputStream | 输出文档流。 |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 签名选项。 |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) 将结果保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.OutputStream | 输出文档流。 |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 签名选项。 |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存选项。 |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| 文档 | java.io.OutputStream | 输出文档流。 |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 签名选项列表。 |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) 将结果保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.OutputStream | 输出文档流。 |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 签名选项列表。 |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存选项。 |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| filePath | java.lang.String | 输出文件路径。 |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 签名选项。 |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


使用 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) 将结果保存到指定的文件路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 输出文件路径。 |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 签名选项。 |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存选项。 |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| filePath | java.lang.String | 输出文件路径。 |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 签名选项列表。 |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


使用一组 [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) 对文档进行签名，并使用预定义的 [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) 将结果保存到指定的文件路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 输出文件路径。 |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | 签名选项列表。 |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | 保存选项。 |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

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

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


获取文档页面的信息：它们的尺寸、最大页面高度以及具有最大高度的页面的宽度。

**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

--------------------

**Learn more**

 *  Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java][]


[How to get document properties in Java]: https://docs.groupdocs.com/signature/java/get-document-information/
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


生成文档页面预览。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | 预览选项。 |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature][]


[How to generate document pages preview using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/generate-document-pages-preview/ |

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


通过 [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) 列表在文档中搜索签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | 搜索选项集合。 |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.
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

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - 返回找到的签名列表。
### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


通过 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 值在文档中搜索确切类型的签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | 要搜索的签名类型。 |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - 返回具有精确类型的已找到签名列表。
### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


通过 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) 值在文档中搜索指定的签名类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureTypes | int[] | 要查找的一种或多种签名类型。 |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

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
| 文档 | java.io.OutputStream | 输出文档流。 |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 文档中要更新的签名对象。 |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - 如果操作成功则返回 true。
### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


在文档中更新传入的签名集合 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.OutputStream | 输出文档流。 |
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 文档中要更新的签名列表。 |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


在文档中更新传入的签名集合 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 输出文件路径。 |
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 文档中要更新的签名列表。 |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


在文档中更新传入的签名集合 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 输出文件路径。 |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 文档中要更新的签名对象。 |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - 返回 UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult)，其中包含成功更新的签名列表和失败的签名。
### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


从文档中删除传入的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.OutputStream | 输出文档流。 |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 文档中要删除的签名对象。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - 如果操作成功则返回 true。
### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


从文档中删除传入的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.OutputStream | 输出文档流。 |
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 文档中要删除的签名列表。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


从文档中删除传入的签名 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 输出文件路径。 |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | 文档中要删除的签名对象。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - 如果操作成功则返回 true。
### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


从文档中删除传入的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 输出文件路径。 |
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | 文档中要删除的签名列表。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


从文档中删除特定类型的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。仅删除由 Sign 方法添加并标记为签名的 BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-))。支持以下签名类型：Text、Image、Digital、Barcode、QR-Code。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.OutputStream | 输出文档流。 |
|  | signatureType | int | 要从文档中删除的签名类型。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


从文档中删除特定类型列表的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。仅删除由 Sign 方法添加并标记为签名的 BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-))。支持以下签名类型：Text、Image、Digital、Barcode、QR-Code。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | java.io.OutputStream | 输出文档流。 |
|  | signatureTypes | java.util.List<java.lang.Integer> | 要从文档中删除的签名类型列表。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


从文档中删除特定类型的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。仅删除由 Sign 方法添加并标记为签名的 BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-))。支持以下签名类型：Text、Image、Digital、Barcode、QR-Code。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 输出文件路径。 |
|  | signatureType | int | 要从文档中删除的签名类型。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


从文档中删除特定类型列表的签名 [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)。仅删除由 Sign 方法添加并标记为签名的 BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-))。支持以下签名类型：Text、Image、Digital、Barcode、QR-Code。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 输出文件路径。 |
|  | signatureTypes | java.util.List<java.lang.Integer> | 要从文档中删除的签名类型列表。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


从文档中通过特定的签名 Id 删除签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureId | java.lang.String | 要从文档中删除的签名 Id。 |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
boolean - 如果操作成功则返回 true。
### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


从文档中删除传入的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | 文档中要删除的签名标识符列表。 |

--------------------

**Learn more** ///  ///  /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature][] ///  ///  /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C] ///  ///  ///


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


根据给定的 SignOptions 生成签名预览。[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | 使用给定的 SignOptions 的预览签名。[PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

--------------------

**Learn more**

 *  Learn more about how to generate previews of the signatures: |

### dispose() {#dispose--}
```
public final void dispose()
```


实现 IDisposable 接口以清理内部资源

