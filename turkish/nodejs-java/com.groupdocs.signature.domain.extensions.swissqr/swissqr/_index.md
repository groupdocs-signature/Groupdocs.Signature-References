---
title: "SwissQR"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "SwissQR koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

SwissQR koduna gömülü metni kodlamak ve çözmek için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SwissQR()](#SwissQR--) | SwissQR'nin bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAmount()](#getAmount--) | Ödeme tutarını alır veya ayarlar. |
| [setAmount(double value)](#setAmount-double-) | Ödeme tutarını alır veya ayarlar. |
| [getCurrency()](#getCurrency--) | Ödeme para birimini alır veya ayarlar. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Ödeme para birimini alır veya ayarlar. |
| [getAccount()](#getAccount--) | Alacaklının hesap numarasını alır veya ayarlar. |
| [setAccount(String value)](#setAccount-java.lang.String-) | Alacaklının hesap numarasını alır veya ayarlar. |
| [getCreditor()](#getCreditor--) | Alacaklının adresini alır veya ayarlar. |
| [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Alacaklının adresini alır veya ayarlar. |
| [getReference()](#getReference--) | Alacaklı ödeme referansını alır veya ayarlar. |
| [setReference(String value)](#setReference-java.lang.String-) | Alacaklı ödeme referansını alır veya ayarlar. |
| [getDebtor()](#getDebtor--) | Borçlunun adresini alır veya ayarlar. |
| [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Borçlunun adresini alır veya ayarlar. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Ek yapılandırılmamış mesajı alır veya ayarlar. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Ek yapılandırılmamış mesajı alır veya ayarlar. |
| [getBillInformation()](#getBillInformation--) | Ek yapılandırılmış fatura bilgilerini alır veya ayarlar. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Ek yapılandırılmış fatura bilgilerini alır veya ayarlar. |
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


SwissQR'nin bir örneğini oluşturur.

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Ödeme tutarını alır veya ayarlar. Geçerli değerler 0.01 ile 999,999,999.99 arasındadır.

Değer: Ödeme tutarı.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Ödeme tutarını alır veya ayarlar. Geçerli değerler 0.01 ile 999,999,999.99 arasındadır.

Değer: Ödeme tutarı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Ödeme para birimini alır veya ayarlar. Geçerli değerler "CHF" ve "EUR".

Değer: Ödeme para birimi.

**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Ödeme para birimini alır veya ayarlar. Geçerli değerler "CHF" ve "EUR".

Değer: Ödeme para birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Alacaklının hesap numarasını alır veya ayarlar. Hesap numaraları, İsviçre veya Lihtenştayn bankalarına ait geçerli IBAN olmalıdır. Hesap numarasında boşluklara izin verilir.

Değer: Alacaklı hesap numarası.

**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Alacaklının hesap numarasını alır veya ayarlar. Hesap numaraları, İsviçre veya Lihtenştayn bankalarına ait geçerli IBAN olmalıdır. Hesap numarasında boşluklara izin verilir.

Değer: Alacaklı hesap numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Alacaklının adresini alır veya ayarlar.

Değer: Alacaklı adresi.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Alacaklının adresini alır veya ayarlar.

Değer: Alacaklı adresi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Alacaklı ödeme referansını alır veya ayarlar. Referans, SwissQR IBAN'ları için zorunludur, yani CHxx30000xxxxxx ile CHxx31999xxxxx aralığındaki IBAN'lar. Belirtilirse, referans ya geçerli bir SwissQR referansı (ISR referans formuna karşılık gelen) ya da ISO 11649'e göre geçerli bir alacaklı referansı ("RFxxxx") olmalıdır. Her ikisi de biçimlendirme amacıyla boşluk içerebilir.

Değer: Alacaklı ödeme referansı.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Alacaklı ödeme referansını alır veya ayarlar. Referans, SwissQR IBAN'ları için zorunludur, yani CHxx30000xxxxxx ile CHxx31999xxxxx aralığındaki IBAN'lar. Belirtilirse, referans ya geçerli bir SwissQR referansı (ISR referans formuna karşılık gelen) ya da ISO 11649'e göre geçerli bir alacaklı referansı ("RFxxxx") olmalıdır. Her ikisi de biçimlendirme amacıyla boşluk içerebilir.

Değer: Alacaklı ödeme referansı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Borçlu adresini alır veya ayarlar. Borçlu isteğe bağlıdır. Eğer belirtilmezse, bu alanı null olarak ayarlamak ya da tüm değerleri null veya boş olan bir adres ayarlamak da kabul edilebilir.

Değer: Borçlu adresi.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Borçlu adresini alır veya ayarlar. Borçlu isteğe bağlıdır. Eğer belirtilmezse, bu alanı null olarak ayarlamak ya da tüm değerleri null veya boş olan bir adres ayarlamak da kabul edilebilir.

Değer: Borçlu adresi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Ek yapılandırılmamış mesajı alır veya ayarlar.

Değer: Yapılandırılmamış mesaj.

**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Ek yapılandırılmamış mesajı alır veya ayarlar.

Değer: Yapılandırılmamış mesaj.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Ek yapılandırılmış fatura bilgilerini alır veya ayarlar.

Değer: Yapılandırılmış fatura bilgileri.

**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Ek yapılandırılmış fatura bilgilerini alır veya ayarlar.

Değer: Yapılandırılmış fatura bilgileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

