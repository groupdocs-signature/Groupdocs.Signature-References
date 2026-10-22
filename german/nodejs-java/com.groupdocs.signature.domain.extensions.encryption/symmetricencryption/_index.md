---
title: "SymmetricEncryption"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Implementiert standardmäßige symmetrische Algorithmen zur Datenverschlüsselung mit einem einzelnen Schlüssel und Passphrase‑Salz."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Implementiert standardmäßige symmetrische Algorithmen für die Datenverschlüsselung mit einem einzelnen Schlüssel und einer Passphrase (Salt).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Erstellt einen symmetrischen Verschlüsselungsalgorithmus mit Parametern. |
| [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Erstellt einen symmetrischen Verschlüsselungsalgorithmus mit Standard‑Passphrase |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAlgorithmType()](#getAlgorithmType--) | Liest oder setzt den Typ des symmetrischen Algorithmus. |
| [setAlgorithmType(int value)](#setAlgorithmType-int-) | Liest oder setzt den Typ des symmetrischen Algorithmus. |
| [getKey()](#getKey--) | Liest oder setzt den Schlüssel des Verschlüsselungsalgorithmus. |
| [setKey(String value)](#setKey-java.lang.String-) | Liest oder setzt den Schlüssel des Verschlüsselungsalgorithmus. |
| [getSalt()](#getSalt--) | Liest oder setzt die Passphrase des Verschlüsselungsalgorithmus. |
| [setSalt(String value)](#setSalt-java.lang.String-) | Liest oder setzt die Passphrase des Verschlüsselungsalgorithmus. |
| [encode(String source)](#encode-java.lang.String-) | Verschlüsselt einen String basierend auf dem angegebenen Algorithmustyp, Schlüssel und Salz‑Parametern |
| [decode(String source)](#decode-java.lang.String-) | Entschlüsselt einen String basierend auf dem angegebenen Algorithmustyp, Schlüssel und Salz‑Parametern |
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Erstellt einen symmetrischen Verschlüsselungsalgorithmus mit Parametern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Algorithmustyp | int | Geben Sie den Typ des symmetrischen Algorithmus an |
| Schlüssel | java.lang.String | Verschlüsselungsschlüssel |
| Salz | java.lang.String | Passphrase für die Verschlüsselung |

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Erstellt einen symmetrischen Verschlüsselungsalgorithmus mit Standard‑Passphrase

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Algorithmustyp | int | Geben Sie den Typ des symmetrischen Algorithmus an |
| Schlüssel | java.lang.String | Verschlüsselungsschlüssel |

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Liest oder setzt den Typ des symmetrischen Algorithmus.

**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Liest oder setzt den Typ des symmetrischen Algorithmus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Liest oder setzt den Schlüssel des Verschlüsselungsalgorithmus.

**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Liest oder setzt den Schlüssel des Verschlüsselungsalgorithmus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Liest oder setzt die Passphrase des Verschlüsselungsalgorithmus.

**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Liest oder setzt die Passphrase des Verschlüsselungsalgorithmus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Verschlüsselt einen String basierend auf dem angegebenen Algorithmustyp, Schlüssel und Salz‑Parametern

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Quelle | java.lang.String | Quell-String zum Kodieren. |

**Returns:**
java.lang.String – Gibt den verschlüsselten String zurück.
### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Entschlüsselt einen String basierend auf dem angegebenen Algorithmustyp, Schlüssel und Salz‑Parametern

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Quelle | java.lang.String | Verschlüsselter String zum Dekodieren. |

**Returns:**
java.lang.String – Gibt den entschlüsselten String zurück.
