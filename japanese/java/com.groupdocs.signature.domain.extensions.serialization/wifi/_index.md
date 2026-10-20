---
title: "WiFi"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "WiFi ネットワーク接続の詳細を表します。"
type: docs
weight: 20
url: /ja/java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

WiFi ネットワーク接続の詳細を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WiFi()](#WiFi--) | デフォルト値で VCard インスタンスを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSSID()](#getSSID--) | WiFi SSID 名を取得または設定します。 |
|
|  | [setSSID(String value)](#setSSID-java.lang.String-) | WiFi SSID 名を取得または設定します。 |
|
|  | [getPassword()](#getPassword--) | WiFi パスワードを取得または設定します。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | WiFi パスワードを取得または設定します。 |
|
|  | [getEncryption()](#getEncryption--) | WiFi 暗号化を取得または設定します [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)。 |
|
|  | [setEncryption(int value)](#setEncryption-int-) | WiFi 暗号化を取得または設定します [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)。 |
|
|  | [getHidden()](#getHidden--) | WiFi が隠し SSID かどうかを取得または設定します。 |
|
|  | [setHidden(boolean value)](#setHidden-boolean-) | WiFi が隠し SSID かどうかを取得または設定します。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | VCardプロパティを比較するためにEqualsメソッドを上書きします。 |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
### WiFi() {#WiFi--}
```
public WiFi()
```


デフォルト値で VCard インスタンスを作成します。


### getSSID() {#getSSID--}
```
public final String getSSID()
```


WiFi SSID 名を取得または設定します。


**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


WiFi SSID 名を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


WiFi パスワードを取得または設定します。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


WiFi パスワードを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


WiFi 暗号化を取得または設定します [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)。


**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


WiFi 暗号化を取得または設定します [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


WiFi が隠し SSID かどうかを取得または設定します。


**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


WiFi が隠し SSID かどうかを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


VCardプロパティを比較するためにEqualsメソッドを上書きします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | 比較対象となる VCard オブジェクト。 |
|

**Returns:**
boolean - 渡された VCard オブジェクトが同じ型で、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int - VCard のハッシュコード

