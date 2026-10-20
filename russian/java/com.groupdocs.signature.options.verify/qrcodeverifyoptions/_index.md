---
title: "QrCodeVerifyOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Сохраняет параметры для проверки подписи QR-кода документа."
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

Сохраняет параметры для проверки подписи QR-кода документа.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | Создает параметр проверки QRCodeVerifyOptions для подписей QR‑кода. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | Создает параметр проверки QRCodeVerifyOptions для подписей QR‑кода с текстом QR‑кода для проверки. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Создает параметр проверки QRCodeVerifyOptions для подписей QR‑кода с текстом и типом кодирования QR‑кода для проверки. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Получает или задает проверку типа QR‑кода. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Получает или задает проверку типа QR‑кода. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста подписи QR‑кода. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста подписи QR‑кода. |
|
|  | [toString()](#toString--) | Переопределяет преобразование в строку. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


Создает параметр проверки QRCodeVerifyOptions для подписей QR‑кода.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


Создает параметр проверки QRCodeVerifyOptions для подписей QR‑кода с текстом QR‑кода для проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст QR‑кода для проверки |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


Создает параметр проверки QRCodeVerifyOptions для подписей QR‑кода с текстом и типом кодирования QR‑кода для проверки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | Текст для проверки |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Тип кодирования |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Получает или задает проверку типа QR‑кода. Это свойство необязательно.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Получает или задает проверку типа QR‑кода. Это свойство необязательно.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста подписи QR‑кода.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Получает или задает реализацию интерфейса [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) для кодирования и декодирования свойств текста подписи QR‑кода.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


Переопределяет преобразование в строку.


**Returns:**
java.lang.String -
