---
title: "SymmetricEncryption"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Implementeert standaard symmetrische algoritmen voor gegevensversleuteling met een enkele sleutel en wachtwoordzout."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Implementeert standaard symmetrische algoritmen voor gegevensencryptie met een enkele sleutel en wachtwoordzin (zout).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Maakt een symmetrisch versleutelingsalgoritme met parameters. |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Maakt een symmetrisch versleutelingsalgoritme met standaardwachtwoord |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | Haalt op of stelt het type van het symmetrische algoritme in. |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | Haalt op of stelt het type van het symmetrische algoritme in. |
|
|  | [getKey()](#getKey--) | Haalt op of stelt de sleutel van het versleutelingsalgoritme in. |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | Haalt op of stelt de sleutel van het versleutelingsalgoritme in. |
|
|  | [getSalt()](#getSalt--) | Haalt op of stelt het wachtwoord van het versleutelingsalgoritme in. |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | Haalt op of stelt het wachtwoord van het versleutelingsalgoritme in. |
|
|  | [encode(String source)](#encode-java.lang.String-) | Versleutelt een tekenreeks op basis van het opgegeven algoritmetype, de sleutel en de zoutparameters |
|
|  | [decode(String source)](#decode-java.lang.String-) | Ontsleutelt een tekenreeks op basis van het opgegeven algoritmetype, de sleutel en de zoutparameters |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Maakt een symmetrisch versleutelingsalgoritme met parameters.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | algorithmType | int | Specificeer het type symmetrisch algoritme |
|
|  | key | java.lang.String | Versleutelingssleutel |
|
|  | zout | java.lang.String | Wachtwoord voor versleuteling |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Maakt een symmetrisch versleutelingsalgoritme met standaardwachtwoord


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | algorithmType | int | Specificeer het type symmetrisch algoritme |
|
|  | key | java.lang.String | Versleutelingssleutel |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Haalt op of stelt het type van het symmetrische algoritme in.


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Haalt op of stelt het type van het symmetrische algoritme in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Haalt op of stelt de sleutel van het versleutelingsalgoritme in.


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Haalt op of stelt de sleutel van het versleutelingsalgoritme in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Haalt op of stelt het wachtwoord van het versleutelingsalgoritme in.


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Haalt op of stelt het wachtwoord van het versleutelingsalgoritme in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Versleutelt een tekenreeks op basis van het opgegeven algoritmetype, de sleutel en de zoutparameters


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bron | java.lang.String | Brontekenreeks om te coderen. |
|

**Returns:**
java.lang.String - Retourneert versleutelde tekenreeks.

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Ontsleutelt een tekenreeks op basis van het opgegeven algoritmetype, de sleutel en de zoutparameters


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bron | java.lang.String | Versleutelde tekenreeks om te decoderen. |
|

**Returns:**
java.lang.String - Retourneert ontsleutelde tekenreeks.

