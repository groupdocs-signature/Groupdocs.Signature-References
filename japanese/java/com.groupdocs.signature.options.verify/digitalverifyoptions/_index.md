---
title: "DigitalVerifyOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントのデジタル署名を検証するオプションを保持します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object、 [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

ドキュメントのデジタル署名を検証するオプションを保持します。

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | デフォルト値で Digital Verification Option を作成します。 |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | 指定されたデジタル証明書 GUID で Digital Verification Option を作成します。 |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | 指定された証明書ストリームで Digital Verification Option を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Certificate Guid または Stream から X509Certificate2 証明書を取得します。 |
|
|  | [getPassword()](#getPassword--) | 必要な場合のデジタル証明書のパスワード。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 必要な場合のデジタル証明書のパスワード。 |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | デジタル証明書のファイル GUID。 |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | デジタル証明書のファイル GUID。 |
|
|  | [getCertificateStream()](#getCertificateStream--) | デジタル証明書のストリーム。 |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | デジタル証明書のストリーム。 |
|
|  | [getComments()](#getComments--) | 検証するデジタル署名のコメント。 |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 検証するデジタル署名のコメント。 |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | 検証するデジタル署名の日付と時刻の範囲。 |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | 検証するデジタル署名の日付と時刻の範囲。 |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | 検証するデジタル署名の日付と時刻の範囲。 |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | 検証するデジタル署名の日付と時刻の範囲。 |
|
|  | [getReason()](#getReason--) | 検証するデジタル署名の理由。 |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | 検証するデジタル署名の理由。 |
|
|  | [getContact()](#getContact--) | 検証する署名の連絡先。 |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | 検証する署名の連絡先。 |
|
|  | [getLocation()](#getLocation--) | 検証する署名の場所。 |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 検証する署名の場所。 |
|
|  | [getSubjectName()](#getSubjectName--) | 検証する証明書のサブジェクト識別名。 |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | 検証する証明書のサブジェクト識別名。 |
|
|  | [getIssuerName()](#getIssuerName--) | 検証する証明書の発行者名。 |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | 検証する証明書の発行者名。 |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


デフォルト値で Digital Verification Option を作成します。


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


指定されたデジタル証明書 GUID で Digital Verification Option を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | デジタル証明書へのファイルパス。 |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


指定された証明書ストリームで Digital Verification Option を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 証明書のストリーム。 |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Certificate Guid または Stream から X509Certificate2 証明書を取得します。


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


必要な場合のデジタル証明書のパスワード。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


必要な場合のデジタル証明書のパスワード。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


デジタル証明書のファイル GUID。


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


デジタル証明書のファイル GUID。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


デジタル証明書のストリーム。


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


デジタル証明書のストリーム。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


検証するデジタル署名のコメント。


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


検証するデジタル署名のコメント。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


検証するデジタル署名の日付と時刻の範囲。null 許容値は無視されます。


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


検証するデジタル署名の日付と時刻の範囲。null 許容値は無視されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


検証するデジタル署名の日付と時刻の範囲。null 許容値は無視されます。


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


検証するデジタル署名の日付と時刻の範囲。null 許容値は無視されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


検証するデジタル署名の理由。


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


検証するデジタル署名の理由。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


検証する署名の連絡先。


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


検証する署名の連絡先。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


検証する署名の場所。


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


検証する署名の場所。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


検証する証明書のサブジェクト識別名。値は大文字小文字を区別します。
このプロパティが設定されている場合、検証は署名のサブジェクト名が渡された値を含むか等しいかをチェックします


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


検証する証明書のサブジェクト識別名。値は大文字小文字を区別します。
このプロパティが設定されている場合、検証は署名のサブジェクト名が渡された値を含むか等しいかをチェックします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


検証する証明書の発行者名。値は大文字小文字を区別します。
このプロパティが設定されている場合、検証は署名の発行者名が渡された値を含むか等しいかをチェックします


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


検証する証明書の発行者名。値は大文字小文字を区別します。
このプロパティが設定されている場合、検証は署名の発行者名が渡された値を含むか等しいかをチェックします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

