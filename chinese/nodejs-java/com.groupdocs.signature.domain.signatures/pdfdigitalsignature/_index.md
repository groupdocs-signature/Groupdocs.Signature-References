---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "包含 Pdf Digital signature 属性。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

包含 Pdf Digital signature 属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfDigitalSignature()](#PdfDigitalSignature--) | 使用无证书初始化 Pdf Digital Signature。 |
| [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | 使用指定证书创建 Pdf 数字签名。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getContactInfo()](#getContactInfo--) | 签署者提供的信息，以便接收者联系签署者验证签名，例如。 |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | 签署者提供的信息，以便接收者联系签署者验证签名，例如。 |
| [getLocation()](#getLocation--) | 签署时的 CPU 主机名或物理位置。 |
| [setLocation(String value)](#setLocation-java.lang.String-) | 签署时的 CPU 主机名或物理位置。 |
| [getReason()](#getReason--) | 签署原因，例如 (I agree\u0420\u0406\u0420\u201a\u0412¦)。 |
| [setReason(String value)](#setReason-java.lang.String-) | 签署原因，例如 (I agree\u0420\u0406\u0420\u201a\u0412¦)。 |
| [getType()](#getType--) | Pdf 数字签名的类型。 |
| [setType(int value)](#setType-int-) | Pdf 数字签名的类型。 |
| [getTimeStamp()](#getTimeStamp--) | Pdf 数字签名的时间戳。 |
| [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Pdf 数字签名的时间戳。 |
| [getShowProperties()](#getShowProperties--) | 强制显示/隐藏签名属性。 |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | 强制显示/隐藏签名属性。 |
| [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
| [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法。 |
| [deepClone()](#deepClone--) | 克隆 Barcode Signature 实例。 |
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


使用无证书初始化 Pdf Digital Signature。

### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


使用指定证书创建 Pdf 数字签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 证书 | java.security.KeyStore | X509 证书。 |

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


签署者提供的信息，以便接收者联系签署者验证签名，例如电话号码。

**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


签署者提供的信息，以便接收者联系签署者验证签名，例如电话号码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


签署时的 CPU 主机名或物理位置。

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


签署时的 CPU 主机名或物理位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


签署原因，例如 (I agree\u0420\u0406\u0420\u201a\u0412¦)。

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


签署原因，例如 (I agree\u0420\u0406\u0420\u201a\u0412¦)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Pdf 数字签名的类型。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Pdf 数字签名的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Pdf 数字签名的时间戳。默认值为 null。

**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Pdf 数字签名的时间戳。默认值为 null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段将具有预定义的外观格式：Digitally signed by \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} 日期: \{Date\} 原因: \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} 位置: \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} 默认情况下 ShowProperties 为 true。

**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段将具有预定义的外观格式：Digitally signed by \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} 日期: \{Date\} 原因: \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} 位置: \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} 默认情况下 ShowProperties 为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


覆盖 Equals 方法以比较签名属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 签名 | java.lang.Object | 用于比较的 Signature 对象。 |

**Returns:**
boolean - 如果传入的签名对象具有相同类型且所有属性都等于此实例的属性，则返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法。

**Returns:**
int - 签名哈希码
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆 Barcode Signature 实例。

**Returns:**
java.lang.Object - 返回克隆的 Barcode Signature 实例。
