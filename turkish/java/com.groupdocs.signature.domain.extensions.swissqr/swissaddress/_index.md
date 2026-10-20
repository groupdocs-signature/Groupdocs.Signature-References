---
title: "SwissAddress"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Alacaklı veya borçlunun adresini temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Alacaklı veya borçlunun adresini temsil eder.
Ya sokak, ev numarası, posta kodu ve kasaba (yapılandırılmış adres türü) ayarlayabilirsiniz
ya da adres satırı 1 ve 2 (birleştirilmiş adres öğeleri türü).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | İsmi alır veya ayarlar, doğal bir kişinin ad ve soyadı ya da |
yasal bir kişinin şirket adı.
|
|  | [setName(String value)](#setName-java.lang.String-) | İsmi alır veya ayarlar, doğal bir kişinin ad ve soyadı ya da |
yasal bir kişinin şirket adı.
|
|  | [getAddressLine1()](#getAddressLine1--) | Adres satırı 1'i alır veya ayarlar. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Adres satırı 1'i alır veya ayarlar. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Adres satırı 2'yi alır veya ayarlar. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Adres satırı 2'yi alır veya ayarlar. |
|
|  | [getStreet()](#getStreet--) | Sokak bilgisini alır veya ayarlar. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Sokak bilgisini alır veya ayarlar. |
|
|  | [getHouseNo()](#getHouseNo--) | Ev numarasını alır veya ayarlar. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Ev numarasını alır veya ayarlar. |
|
|  | [getPostalCode()](#getPostalCode--) | Posta kodunu alır veya ayarlar. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Posta kodunu alır veya ayarlar. |
|
|  | [getTown()](#getTown--) | Kasaba veya şehri alır veya ayarlar. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Kasaba veya şehri alır veya ayarlar. |
|
|  | [getCountryCode()](#getCountryCode--) | İki harfli ISO ülke kodunu alır veya ayarlar. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | İki harfli ISO ülke kodunu alır veya ayarlar. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


İsmi alır veya ayarlar, doğal bir kişinin ad ve soyadı ya da
yasal bir kişinin şirket adı.
Değer: İsim.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


İsmi alır veya ayarlar, doğal bir kişinin ad ve soyadı ya da
yasal bir kişinin şirket adı.
Değer: İsim.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Adres satırı 1'i alır veya ayarlar.
Adres satırı 1, sokak adı, ev numarası veya posta kutusunu içerir.
Bu alan yalnızca birleştirilmiş öğe adresleri için kullanılır ve isteğe bağlıdır.
Değer: Adres satırı 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Adres satırı 1'i alır veya ayarlar.
Adres satırı 1, sokak adı, ev numarası veya posta kutusunu içerir.
Bu alan yalnızca birleştirilmiş öğe adresleri için kullanılır ve isteğe bağlıdır.
Değer: Adres satırı 1.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Adres satırı 2'yi alır veya ayarlar.
Adres satırı 2, posta kodu ve kasabayı içerir.
Bu alan yalnızca birleştirilmiş öğe adresleri için kullanılır. Bu tip için zorunludur.
Değer: Adres satırı 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Adres satırı 2'yi alır veya ayarlar.
Adres satırı 2, posta kodu ve kasabayı içerir.
Bu alan yalnızca birleştirilmiş öğe adresleri için kullanılır. Bu tip için zorunludur.
Değer: Adres satırı 2.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Sokak bilgisini alır veya ayarlar.
Sokak, ev numarası olmadan belirtilmelidir.
Bu alan yalnızca yapılandırılmış adresler için kullanılır ve isteğe bağlıdır.
Değer: Sokak.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Sokak bilgisini alır veya ayarlar.
Sokak, ev numarası olmadan belirtilmelidir.
Bu alan yalnızca yapılandırılmış adresler için kullanılır ve isteğe bağlıdır.
Değer: Sokak.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Ev numarasını alır veya ayarlar.
Bu alan yalnızca yapılandırılmış adresler için kullanılır ve isteğe bağlıdır.
Değer: Ev numarası.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Ev numarasını alır veya ayarlar.
Bu alan yalnızca yapılandırılmış adresler için kullanılır ve isteğe bağlıdır.
Değer: Ev numarası.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Posta kodunu alır veya ayarlar.
Bu alan yalnızca yapılandırılmış adresler için kullanılır. Bu tip için zorunludur.
Değer: Posta kodu.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Posta kodunu alır veya ayarlar.
Bu alan yalnızca yapılandırılmış adresler için kullanılır. Bu tip için zorunludur.
Değer: Posta kodu.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Kasaba veya şehri alır veya ayarlar.
Bu alan yalnızca yapılandırılmış adresler için kullanılır. Bu tip için zorunludur.
Değer: Kasaba veya şehir.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Kasaba veya şehri alır veya ayarlar.
Bu alan yalnızca yapılandırılmış adresler için kullanılır. Bu tip için zorunludur.
Değer: Kasaba veya şehir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


İki harfli ISO ülke kodunu alır veya ayarlar.
Ülke kodu, tüm adres null veya boş değerler içermediği sürece zorunludur.
Değer: ISO ülke kodu.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


İki harfli ISO ülke kodunu alır veya ayarlar.
Ülke kodu, tüm adres null veya boş değerler içermediği sürece zorunludur.
Değer: ISO ülke kodu.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

