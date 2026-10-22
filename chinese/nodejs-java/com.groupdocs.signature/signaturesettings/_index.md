---
title: "SignatureSettings"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "定义用于自定义行为的设置。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

定义用于自定义 [Signature](../../com.groupdocs.signature/signature) 行为的设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SignatureSettings()](#SignatureSettings--) | 创建具有默认值的默认 SignatureSettings 实例。 |
| [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | 创建使用 Logger 实现的默认 SignatureSettings 实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDefaultCulture()](#getDefaultCulture--) | 获取或设置文档处理期间使用的默认区域性。 |
| [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | 获取或设置文档处理期间使用的默认区域性。 |
| [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | 获取或设置将已删除签名包含在文档信息结果中的标志。 |
| [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | 获取或设置将已删除签名包含在文档信息结果中的标志。 |
| [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | 获取或设置当 Update 方法没有签名可更新时重新保存源文档的标志。 |
| [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | 获取或设置当 Update 方法没有签名可更新时重新保存源文档的标志。 |
| [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | 获取或设置当 Delete 方法没有受影响的签名可删除时重新保存源文档的标志。 |
| [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | 获取或设置当 Delete 方法没有受影响的签名可删除时重新保存源文档的标志。 |
| [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | 获取或设置将嵌入的标准文档元数据签名（如作者、所有者、文档创建日期、修改日期等）包含到元数据列表中的标志。 |
| [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | 获取或设置将嵌入的标准文档元数据签名（如作者、所有者、文档创建日期、修改日期等）包含到元数据列表中的标志。 |
| [getLogger()](#getLogger--) | 用于日志记录（错误、警告、跟踪）的日志实现。 |
| [getLogLevel()](#getLogLevel--) | 用于限制消息的日志级别（全部、跟踪、警告、错误）。 |
| [setLogLevel(int value)](#setLogLevel-int-) | 用于限制消息的日志级别（全部、跟踪、警告、错误）。 |
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


创建具有默认值的默认 SignatureSettings 实例。

### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


创建使用 Logger 实现的默认 SignatureSettings 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


获取或设置文档处理期间使用的默认区域性。默认值为 "en-US"。

**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


获取或设置文档处理期间使用的默认区域性。默认值为 "en-US"。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


获取或设置将已删除签名包含在文档信息结果中的标志。每个 Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) 都有 Deleted 标志 BaseSignature.Deleted（[BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)），用于检测其是否已被删除。

**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


获取或设置将已删除签名包含在文档信息结果中的标志。每个 Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) 都有 Deleted 标志 BaseSignature.Deleted（[BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)），用于检测其是否已被删除。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


获取或设置当 Update 方法没有签名可更新时重新保存源文档的标志。如果此标志设置为 true（默认），即使 Update 方法没有签名可更新，文档也会保存并记录相应的历史处理日志（日期和操作类型）。当此标志设置为 false 时，源文档将完全不被修改。

**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


获取或设置当 Update 方法没有签名可更新时重新保存源文档的标志。如果此标志设置为 true（默认），即使 Update 方法没有签名可更新，文档也会保存并记录相应的历史处理日志（日期和操作类型）。当此标志设置为 false 时，源文档将完全不被修改。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


获取或设置当 Delete 方法没有受影响的签名可删除时重新保存源文档的标志。如果此标志设置为 true（默认），即使 Delete 方法没有签名可删除，文档也会保存并记录相应的历史处理日志（日期和操作类型）。当此标志设置为 false 时，源文档将完全不被修改。

**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


获取或设置当 Delete 方法没有受影响的签名可删除时重新保存源文档的标志。如果此标志设置为 true（默认），即使 Delete 方法没有签名可删除，文档也会保存并记录相应的历史处理日志（日期和操作类型）。当此标志设置为 false 时，源文档将完全不被修改。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


获取或设置将嵌入的标准文档元数据签名（如作者、所有者、文档创建日期、修改日期等）包含到元数据列表中的标志。如果此标志设置为 false（默认），GetDocumentInfo 将不包括这些元数据签名。当此标志设置为 true 时，文档信息将包含这些标准元数据签名。

**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


获取或设置将嵌入的标准文档元数据签名（如作者、所有者、文档创建日期、修改日期等）包含到元数据列表中的标志。如果此标志设置为 false（默认），GetDocumentInfo 将不包括这些元数据签名。当此标志设置为 true 时，文档信息将包含这些标准元数据签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


用于日志记录（错误、警告、跟踪）的日志实现。[ILogger](../../com.groupdocs.signature.logging/ilogger)。

**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


用于限制消息的日志级别（全部、跟踪、警告、错误）。LogLevel。默认情况下设置为 All 级别。

**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


用于限制消息的日志级别（全部、跟踪、警告、错误）。LogLevel。默认情况下设置为 All 级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

