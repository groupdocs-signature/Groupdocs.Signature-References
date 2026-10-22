---
title: "SymmetricEncryption"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Implémente les algorithmes symétriques standard pour le chiffrement des données avec une clé unique et un sel de phrase secrète."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Implémente des algorithmes symétriques standard pour le chiffrement des données avec une clé unique et une phrase secrète (sel).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Crée un algorithme de chiffrement symétrique avec des paramètres. |
| [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Crée un algorithme de chiffrement symétrique avec la phrase secrète par défaut |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAlgorithmType()](#getAlgorithmType--) | Obtient ou définit le type d'algorithme symétrique. |
| [setAlgorithmType(int value)](#setAlgorithmType-int-) | Obtient ou définit le type d'algorithme symétrique. |
| [getKey()](#getKey--) | Obtient ou définit la clé de l'algorithme de chiffrement. |
| [setKey(String value)](#setKey-java.lang.String-) | Obtient ou définit la clé de l'algorithme de chiffrement. |
| [getSalt()](#getSalt--) | Obtient ou définit la phrase secrète de l'algorithme de chiffrement. |
| [setSalt(String value)](#setSalt-java.lang.String-) | Obtient ou définit la phrase secrète de l'algorithme de chiffrement. |
| [encode(String source)](#encode-java.lang.String-) | Chiffre la chaîne en fonction du type d'algorithme fourni, de la clé et des paramètres de sel |
| [decode(String source)](#decode-java.lang.String-) | Déchiffre la chaîne en fonction du type d'algorithme fourni, de la clé et des paramètres de sel |
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Crée un algorithme de chiffrement symétrique avec des paramètres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| algorithmType | int | Spécifiez le type d'algorithme symétrique |
| clé | java.lang.String | Clé de chiffrement |
| sel | java.lang.String | Phrase secrète pour le chiffrement |

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Crée un algorithme de chiffrement symétrique avec la phrase secrète par défaut

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| algorithmType | int | Spécifiez le type d'algorithme symétrique |
| clé | java.lang.String | Clé de chiffrement |

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Obtient ou définit le type d'algorithme symétrique.

**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Obtient ou définit le type d'algorithme symétrique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Obtient ou définit la clé de l'algorithme de chiffrement.

**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Obtient ou définit la clé de l'algorithme de chiffrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Obtient ou définit la phrase secrète de l'algorithme de chiffrement.

**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Obtient ou définit la phrase secrète de l'algorithme de chiffrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Chiffre la chaîne en fonction du type d'algorithme fourni, de la clé et des paramètres de sel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Chaîne source à encoder. |

**Returns:**
java.lang.String - Retourne la chaîne chiffrée.
### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Déchiffre la chaîne en fonction du type d'algorithme fourni, de la clé et des paramètres de sel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Chaîne chiffrée à décoder. |

**Returns:**
java.lang.String - Retourne la chaîne déchiffrée.
