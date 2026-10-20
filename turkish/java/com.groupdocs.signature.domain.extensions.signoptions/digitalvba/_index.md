---
title: "DigitalVBA"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "E-tablolar VBA projeleri için dijital imzayı temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

E-tablolar VBA projeleri için dijital imzayı temsil eder.
Xlsm veya Xltm gibi belirli Çalışma Sayfaları belge formatlarında VBA projesini imzalama yeteneği sağlar.
DigitalSignOptions.Extensions'a birden fazla DigitalVBA uzantısı eklenirse, yalnızca ilk olan belge imzalama işlemine dahil edilir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | DigitalVBA sınıfının yeni bir örneğini sertifika dosyasıyla başlatır. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | DigitalVBA sınıfının yeni bir örneğini sertifika akışıyla başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getComments()](#getComments--) | İmza yorumlarını alır veya ayarlar. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | İmza yorumlarını alır veya ayarlar. |
|
|  | [getPassword()](#getPassword--) | Dijital sertifikanın şifresini alır veya ayarlar. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Dijital sertifikanın şifresini alır veya ayarlar. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Yalnızca VBA projesi imzalama ayarını alır veya ayarlar. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Yalnızca VBA projesi imzalama ayarını alır veya ayarlar. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Dijital sertifika dosya yolunu alır. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Dijital sertifika akışını alır. |
|
|  | [release()](#release--) | İmzalamadan sonra kaynakları temizlemek için yöntemi geçersiz kılar. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


DigitalVBA sınıfının yeni bir örneğini sertifika dosyasıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Dijital sertifika dosya yolu |
|
|  | parola | java.lang.String | Dijital sertifika parolası |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


DigitalVBA sınıfının yeni bir örneğini sertifika akışıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Dijital Sertifika akışı |
|
|  | parola | java.lang.String | Dijital sertifika parolası |
|

### getComments() {#getComments--}
```
public final String getComments()
```


İmza yorumlarını alır veya ayarlar.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


İmza yorumlarını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Dijital sertifikanın şifresini alır veya ayarlar.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Dijital sertifikanın şifresini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Yalnızca VBA projesi imzalama ayarını alır veya ayarlar.
True olarak ayarlanırsa, SpreadSheet belgesi imzalanmaz, ancak VBA projesi imzalanır.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Yalnızca VBA projesi imzalama ayarını alır veya ayarlar.
True olarak ayarlanırsa, SpreadSheet belgesi imzalanmaz, ancak VBA projesi imzalanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Dijital sertifika dosya yolunu alır.
Bu özellik yalnızca CertificateStream belirtilmemişse kullanılır.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Dijital sertifika akışını alır.
Bu özellik belirtilirse, her zaman CertificateFilePath yerine kullanılır.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


İmzalamadan sonra kaynakları temizlemek için yöntemi geçersiz kılar.


