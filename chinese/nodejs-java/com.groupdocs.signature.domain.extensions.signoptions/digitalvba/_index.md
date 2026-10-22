---
title: "DigitalVBA"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示用于电子表格 VBA 项目的数字签名。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

表示用于电子表格 VBA 项目的数字签名。它提供在特定的电子表格文档格式（如 Xlsm 或 Xltm）中对 VBA 项目进行签名的能力。如果向 DigitalSignOptions.Extensions 添加了多个 DigitalVBA 扩展，仅第一个会参与文档签名。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | 使用证书文件初始化 DigitalVBA 类的新实例。 |
| [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | 使用证书流初始化 DigitalVBA 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getComments()](#getComments--) | 获取或设置签名注释。 |
| [setComments(String value)](#setComments-java.lang.String-) | 获取或设置签名注释。 |
| [getPassword()](#getPassword--) | 获取或设置数字证书的密码。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 获取或设置数字证书的密码。 |
| [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | 获取或设置仅对 VBA 项目签名的设置。 |
| [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | 获取或设置仅对 VBA 项目签名的设置。 |
| [getCertificateFilePath()](#getCertificateFilePath--) | 获取数字证书文件路径。 |
| [getCertificateStream()](#getCertificateStream--) | 获取数字证书流。 |
| [release()](#release--) | 覆盖方法以在签名后清理资源。 |
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


使用证书文件初始化 DigitalVBA 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificateFilePath | java.lang.String | 数字证书文件路径 |
| 密码 | java.lang.String | 数字证书密码 |

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


使用证书流初始化 DigitalVBA 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificateStream | java.io.InputStream | 数字证书流 |
| 密码 | java.lang.String | 数字证书密码 |

### getComments() {#getComments--}
```
public final String getComments()
```


获取或设置签名注释。

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


获取或设置签名注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取或设置数字证书的密码。

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


获取或设置数字证书的密码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


获取或设置仅对 VBA 项目签名的设置。如果设置为 true，则不会签署 SpreadSheet 文档，但会签署 VBA 项目。

**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


获取或设置仅对 VBA 项目签名的设置。如果设置为 true，则不会签署 SpreadSheet 文档，但会签署 VBA 项目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


获取数字证书文件路径。如果未指定 CertificateStream，则仅使用此属性。

**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


获取数字证书流。如果指定了此属性，则始终使用它而不是 CertificateFilePath。

**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


覆盖方法以在签名后清理资源。

