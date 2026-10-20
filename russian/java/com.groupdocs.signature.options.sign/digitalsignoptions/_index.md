---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры цифровой подписи."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Представляет параметры цифровой подписи.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | Инициализирует новый экземпляр класса DigitalSignOptions со значениями по умолчанию. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и файлом изображения. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и потоком изображения. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата и файлом изображения. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата и потоком изображения. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getReason()](#getReason--) | Получает или задает причину подписи. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Получает или задает причину подписи. |
|
|  | [getContact()](#getContact--) | Получает или задает контакт подписи. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Получает или задает контакт подписи. |
|
|  | [getLocation()](#getLocation--) | Получает или задает место подписи. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Получает или задает место подписи. |
|
|  | [getPassword()](#getPassword--) | Получает или задает пароль цифрового сертификата. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Получает или задает пароль цифрового сертификата. |
|
|  | [getSignature()](#getSignature--) | Получает или задает свойства цифровой подписи документа. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Получает или задает свойства цифровой подписи документа. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Получает или задает путь к файлу цифрового сертификата. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Получает или задает GUID файла цифрового сертификата. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Получает или задает поток цифрового сертификата. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Получает или задает поток цифрового сертификата. |
|
|  | [getVisible()](#getVisible--) | Получает или задает видимость подписи. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Получает или задает видимость подписи. |
|
|  | [getUseLtv()](#getUseLtv--) | Получает/задает флаг проверки LTV (Long Term Validation). |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | Получает/задает флаг проверки LTV (Long Term Validation). |
|
|  | [getAllowExpired()](#getAllowExpired--) | Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого истек. |
|
|  | [setAllowExpired(boolean value)](#setAllowExpired-boolean-) | Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого истек. |
|
|  | [getAllowNotYetValid()](#getAllowNotYetValid--) | Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого еще не начался. |
|
|  | [setAllowNotYetValid(boolean value)](#setAllowNotYetValid-boolean-) | Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого еще не начался. |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Получает или задает пользовательскую реализацию хеш-подписания, позволяя вызывающим подключать свою собственную |
логику цифровой подписи (HSM, удаленный подписант, программное хранилище ключей и т.д.).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Устанавливает пользовательскую реализацию хеш-подписания, позволяя вызывающим подключать свою собственную |
логику цифровой подписи.
|
|  | [getXAdESType()](#getXAdESType--) | Тип XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | Тип XAdES |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Инициализирует новый экземпляр класса DigitalSignOptions со значениями по умолчанию.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Путь к файлу цифрового сертификата |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Поток цифрового сертификата |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и файлом изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Путь к файлу цифрового сертификата |
|
|  | imageFilePath | java.lang.String | Путь к файлу изображения внешнего вида подписи |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и потоком изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Путь к файлу цифрового сертификата |
|
|  | appearenceImageStream | java.io.InputStream | Поток изображения внешнего вида подписи |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата и файлом изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Поток цифрового сертификата |
|
|  | imageFilePath | java.lang.String | Путь к файлу изображения внешнего вида подписи |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата и потоком изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Поток цифрового сертификата |
|
|  | appearenceImageStream | java.io.InputStream | Поток изображения внешнего вида подписи |
|

### getReason() {#getReason--}
```
public final String getReason()
```


Получает или задает причину подписи.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Получает или задает причину подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Получает или задает контакт подписи.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Получает или задает контакт подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Получает или задает место подписи.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Получает или задает место подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Получает или задает пароль цифрового сертификата.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Получает или задает пароль цифрового сертификата.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Получает или задает свойства цифровой подписи документа.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Получает или задает свойства цифровой подписи документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Получает или задает путь к файлу цифрового сертификата.
Это свойство используется только если CertificateStream не указан.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Получает или задает GUID файла цифрового сертификата.
Это свойство используется только если CertificateStream не указан.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Получает или задает поток цифрового сертификата.
Если это свойство указано, оно всегда используется вместо CertificateGuid.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Получает или задает поток цифрового сертификата.
Если это свойство указано, оно всегда используется вместо CertificateGuid.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Получает или задает видимость подписи.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Получает или задает видимость подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Получает/задает флаг проверки LTV (Long Term Validation).


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Получает/задает флаг проверки LTV (Long Term Validation).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getAllowExpired() {#getAllowExpired--}
```
public final boolean getAllowExpired()
```


Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого истек.
Значение по умолчанию — false: подпись с просроченным сертификатом вызывает
GroupDocsSignatureException
,
и документ не подписывается.


Проверяющие сообщают, что подпись, сделанная с просроченным сертификатом, недействительна. Установите это свойство в true только когда
вам всё равно нужна такая подпись, например для тестирования со старым сертификатом. Документ тогда подписывается, и
предупреждение записывается в журнал, установленный в
SignatureSettings
.


Сертификат сравнивается с текущим временем в UTC, а не с
DigitalSignature.SignTime
. Флаг
применяется к сертификату, указанному
CertificateFilePath
,
CertificateStream
или
Signature
,
и, когда подписывается таблица, к сертификату первого
DigitalVBA
расширения. Digital
подписи изображений не используют сертификат и не проверяются. Сертификат, срок действия которого еще
не начался, контролируется
AllowNotYetValid
.


**Returns:**
boolean
### setAllowExpired(boolean value) {#setAllowExpired-boolean-}
```
public final void setAllowExpired(boolean value)
```


Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого истек.
Значение по умолчанию — false. См. #getAllowExpired().getAllowExpired().


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getAllowNotYetValid() {#getAllowNotYetValid--}
```
public final boolean getAllowNotYetValid()
```


Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого еще не начался.
Значение по умолчанию — false: подпись с таким сертификатом вызывает исключение
GroupDocsSignatureException
,
и документ не подписывается.


Проверяющие сообщают, что подпись, сделанная до того, как сертификат стал действительным, считается недействительной. Такой сертификат был
обычно выдан на более позднюю дату, или часы компьютера неверны. Когда это свойство истинно, документ
подписан, и предупреждение записывается в журнал, установленный в
SignatureSettings
.


Сертификат сравнивается с текущим временем в UTC. Флаг применяется к тем же сертификатам, что и

AllowExpired
, который контролирует сертификаты, срок действия которых истёк.


**Returns:**
boolean
### setAllowNotYetValid(boolean value) {#setAllowNotYetValid-boolean-}
```
public final void setAllowNotYetValid(boolean value)
```


Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого еще не начался.
Значение по умолчанию — false. См. #getAllowNotYetValid().getAllowNotYetValid().


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Получает или задает пользовательскую реализацию хеш-подписания, позволяя вызывающим подключать свою собственную
логику цифровой подписи (HSM, удаленный подписант, программное хранилище ключей и т.д.).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Устанавливает пользовательскую реализацию хеш-подписания, позволяя вызывающим подключать свою собственную
логику цифровой подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


Тип XAdES
XAdESType
. Значение по умолчанию — None (XAdES отключён).
В данный момент тип подписи XAdES поддерживается только для документов Spreadsheet под .NET Framework (не под .NET Standard)


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


Тип XAdES
XAdESType
. Значение по умолчанию — None (XAdES отключён).
В данный момент тип подписи XAdES поддерживается только для документов Spreadsheet под .NET Framework (не под .NET Standard)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
