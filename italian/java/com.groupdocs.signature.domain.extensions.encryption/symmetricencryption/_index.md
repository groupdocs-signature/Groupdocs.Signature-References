---
title: "SymmetricEncryption"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Implementa algoritmi simmetrici standard per la crittografia dei dati con chiave singola e sale della passphrase."
type: docs
weight: 11
url: /it/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Implementa algoritmi simmetrici standard per la crittografia dei dati con chiave singola e passphrase (sale).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Crea algoritmo di crittografia simmetrica con parametri. |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Crea algoritmo di crittografia simmetrica con passphrase predefinita |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | Ottiene o imposta il tipo di algoritmo simmetrico. |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | Ottiene o imposta il tipo di algoritmo simmetrico. |
|
|  | [getKey()](#getKey--) | Ottiene o imposta la chiave dell'algoritmo di crittografia. |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | Ottiene o imposta la chiave dell'algoritmo di crittografia. |
|
|  | [getSalt()](#getSalt--) | Ottiene o imposta la passphrase dell'algoritmo di crittografia. |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | Ottiene o imposta la passphrase dell'algoritmo di crittografia. |
|
|  | [encode(String source)](#encode-java.lang.String-) | Cifra la stringa basandosi sul tipo di algoritmo fornito, chiave e parametri di sale |
|
|  | [decode(String source)](#decode-java.lang.String-) | Decifra la stringa basandosi sul tipo di algoritmo fornito, chiave e parametri di sale |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Crea algoritmo di crittografia simmetrica con parametri.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | algorithmType | int | Specifica il tipo di algoritmo simmetrico |
|
|  | key | java.lang.String | Chiave di crittografia |
|
|  | sale | java.lang.String | Passphrase per la crittografia |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Crea algoritmo di crittografia simmetrica con passphrase predefinita


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | algorithmType | int | Specifica il tipo di algoritmo simmetrico |
|
|  | key | java.lang.String | Chiave di crittografia |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Ottiene o imposta il tipo di algoritmo simmetrico.


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Ottiene o imposta il tipo di algoritmo simmetrico.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Ottiene o imposta la chiave dell'algoritmo di crittografia.


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Ottiene o imposta la chiave dell'algoritmo di crittografia.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Ottiene o imposta la passphrase dell'algoritmo di crittografia.


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Ottiene o imposta la passphrase dell'algoritmo di crittografia.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Cifra la stringa basandosi sul tipo di algoritmo fornito, chiave e parametri di sale


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | origine | java.lang.String | Stringa di origine da codificare. |
|

**Returns:**
java.lang.String - Restituisce la stringa crittografata.

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Decifra la stringa basandosi sul tipo di algoritmo fornito, chiave e parametri di sale


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | origine | java.lang.String | Stringa crittografata da decodificare. |
|

**Returns:**
java.lang.String - Restituisce la stringa decrittografata.

