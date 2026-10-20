---
title: "SymmetricEncryption"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Implementa algoritmos simétricos estándar para el cifrado de datos con una única clave y sal de frase de paso."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Implementa algoritmos simétricos estándar para el cifrado de datos con una sola clave y frase de paso (sal).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Crea un algoritmo de cifrado simétrico con parámetros. |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Crea un algoritmo de cifrado simétrico con frase de paso predeterminada |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | Obtiene o establece el tipo de algoritmo simétrico. |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | Obtiene o establece el tipo de algoritmo simétrico. |
|
|  | [getKey()](#getKey--) | Obtiene o establece la clave del algoritmo de cifrado. |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | Obtiene o establece la clave del algoritmo de cifrado. |
|
|  | [getSalt()](#getSalt--) | Obtiene o establece la frase de paso del algoritmo de cifrado. |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | Obtiene o establece la frase de paso del algoritmo de cifrado. |
|
|  | [encode(String source)](#encode-java.lang.String-) | Cifra una cadena según los parámetros de tipo de algoritmo, clave y sal proporcionados |
|
|  | [decode(String source)](#decode-java.lang.String-) | Descifra una cadena según los parámetros de tipo de algoritmo, clave y sal proporcionados |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Crea un algoritmo de cifrado simétrico con parámetros.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | algorithmType | int | Especifique el tipo de algoritmo simétrico |
|
|  | key | java.lang.String | Clave de cifrado |
|
|  | sal | java.lang.String | Frase de paso para el cifrado |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Crea un algoritmo de cifrado simétrico con frase de paso predeterminada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | algorithmType | int | Especifique el tipo de algoritmo simétrico |
|
|  | key | java.lang.String | Clave de cifrado |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Obtiene o establece el tipo de algoritmo simétrico.


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Obtiene o establece el tipo de algoritmo simétrico.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Obtiene o establece la clave del algoritmo de cifrado.


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Obtiene o establece la clave del algoritmo de cifrado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Obtiene o establece la frase de paso del algoritmo de cifrado.


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Obtiene o establece la frase de paso del algoritmo de cifrado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Cifra una cadena según los parámetros de tipo de algoritmo, clave y sal proporcionados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | origen | java.lang.String | Cadena de origen para codificar. |
|

**Returns:**
java.lang.String - Devuelve la cadena cifrada.

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Descifra una cadena según los parámetros de tipo de algoritmo, clave y sal proporcionados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | origen | java.lang.String | Cadena cifrada para descifrar. |
|

**Returns:**
java.lang.String - Devuelve la cadena descifrada.

