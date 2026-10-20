---
title: "SymmetricEncryption"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Implementerar standardalgoritmer för symmetrisk kryptering av data med en enda nyckel och lösenfras‑salt."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Implementerar standardalgoritmer för symmetrisk kryptering av data med en enda nyckel och lösenfras (salt).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Skapar symmetrisk krypteringsalgoritm med parametrar. |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Skapar symmetrisk krypteringsalgoritm med standardlösenfras |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | Hämtar eller anger typ av symmetrisk algoritm. |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | Hämtar eller anger typ av symmetrisk algoritm. |
|
|  | [getKey()](#getKey--) | Hämtar eller anger nyckel för krypteringsalgoritm. |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | Hämtar eller anger nyckel för krypteringsalgoritm. |
|
|  | [getSalt()](#getSalt--) | Hämtar eller anger lösenfras för krypteringsalgoritm. |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | Hämtar eller anger lösenfras för krypteringsalgoritm. |
|
|  | [encode(String source)](#encode-java.lang.String-) | Krypterar sträng baserat på angiven algoritmtyp, nyckel och saltparametrar |
|
|  | [decode(String source)](#decode-java.lang.String-) | Dekrypterar sträng baserat på angiven algoritmtyp, nyckel och saltparametrar |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Skapar symmetrisk krypteringsalgoritm med parametrar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | algorithmType | int | Ange symmetrisk algoritmtyp |
|
|  | nyckel | java.lang.String | Krypteringsnyckel |
|
|  | salt | java.lang.String | Lösenfras för kryptering |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Skapar symmetrisk krypteringsalgoritm med standardlösenfras


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | algorithmType | int | Ange symmetrisk algoritmtyp |
|
|  | nyckel | java.lang.String | Krypteringsnyckel |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Hämtar eller anger typ av symmetrisk algoritm.


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Hämtar eller anger typ av symmetrisk algoritm.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Hämtar eller anger nyckel för krypteringsalgoritm.


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Hämtar eller anger nyckel för krypteringsalgoritm.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Hämtar eller anger lösenfras för krypteringsalgoritm.


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Hämtar eller anger lösenfras för krypteringsalgoritm.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Krypterar sträng baserat på angiven algoritmtyp, nyckel och saltparametrar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | källa | java.lang.String | Källsträng att koda. |
|

**Returns:**
java.lang.String - Returnerar krypterad sträng.

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Dekrypterar sträng baserat på angiven algoritmtyp, nyckel och saltparametrar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | källa | java.lang.String | Krypterad sträng att avkoda. |
|

**Returns:**
java.lang.String - Returnerar dekrypterad sträng.

