---
title: "WiFi"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示 WiFi 网络连接详细信息。"
type: docs
weight: 20
url: /zh/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

表示 WiFi 网络连接详细信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WiFi()](#WiFi--) | 创建具有默认值的 VCard 实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSSID()](#getSSID--) | 获取或设置 WiFi SSID 名称。 |
| [setSSID(String value)](#setSSID-java.lang.String-) | 获取或设置 WiFi SSID 名称。 |
| [getPassword()](#getPassword--) | 获取或设置 WiFi 密码。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 获取或设置 WiFi 密码。 |
| [getEncryption()](#getEncryption--) | 获取或设置 WiFi 加密 [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)。 |
| [setEncryption(int value)](#setEncryption-int-) | 获取或设置 WiFi 加密 [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)。 |
| [getHidden()](#getHidden--) | 获取或设置 WiFi 是否为隐藏 SSID。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 获取或设置 WiFi 是否为隐藏 SSID。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较 VCard 属性。 |
| [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法。 |
### WiFi() {#WiFi--}
```
public WiFi()
```


创建具有默认值的 VCard 实例。

### getSSID() {#getSSID--}
```
public final String getSSID()
```


获取或设置 WiFi SSID 名称。

**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


获取或设置 WiFi SSID 名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


获取或设置 WiFi 密码。

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


获取或设置 WiFi 密码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


获取或设置 WiFi 加密 [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)。

**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


获取或设置 WiFi 加密 [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


获取或设置 WiFi 是否为隐藏 SSID。

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


获取或设置 WiFi 是否为隐藏 SSID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


覆盖 Equals 方法以比较 VCard 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 VCard 对象。 |

**Returns:**
boolean - 如果传入的 VCard 对象具有相同的类型且其所有属性都等于此实例的属性，则返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法。

**Returns:**
int - VCard 哈希码
