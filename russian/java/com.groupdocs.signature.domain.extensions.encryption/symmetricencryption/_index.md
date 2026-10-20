---
title: "SymmetricEncryption"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Реализует стандартные симметричные алгоритмы шифрования данных с использованием одного ключа и соли парольной фразы."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Реализует стандартные симметричные алгоритмы для шифрования данных с использованием одного ключа и пароля (соль).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Создаёт симметричный алгоритм шифрования с параметрами. |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Создаёт симметричный алгоритм шифрования с паролем по умолчанию |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | Получает или задаёт тип симметричного алгоритма. |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | Получает или задаёт тип симметричного алгоритма. |
|
|  | [getKey()](#getKey--) | Получает или задаёт ключ алгоритма шифрования. |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | Получает или задаёт ключ алгоритма шифрования. |
|
|  | [getSalt()](#getSalt--) | Получает или задаёт парольную фразу алгоритма шифрования. |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | Получает или задаёт парольную фразу алгоритма шифрования. |
|
|  | [encode(String source)](#encode-java.lang.String-) | Шифрует строку на основе предоставленного типа алгоритма, ключа и параметров соли |
|
|  | [decode(String source)](#decode-java.lang.String-) | Расшифровывает строку на основе предоставленного типа алгоритма, ключа и параметров соли |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Создаёт симметричный алгоритм шифрования с параметрами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | algorithmType | int | Укажите тип симметричного алгоритма |
|
|  | key | java.lang.String | Ключ шифрования |
|
|  | соль | java.lang.String | Парольная фраза для шифрования |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Создаёт симметричный алгоритм шифрования с паролем по умолчанию


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | algorithmType | int | Укажите тип симметричного алгоритма |
|
|  | key | java.lang.String | Ключ шифрования |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Получает или задаёт тип симметричного алгоритма.


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Получает или задаёт тип симметричного алгоритма.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Получает или задаёт ключ алгоритма шифрования.


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Получает или задаёт ключ алгоритма шифрования.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Получает или задаёт парольную фразу алгоритма шифрования.


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Получает или задаёт парольную фразу алгоритма шифрования.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Шифрует строку на основе предоставленного типа алгоритма, ключа и параметров соли


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | источник | java.lang.String | Исходная строка для кодирования. |
|

**Returns:**
java.lang.String — возвращает зашифрованную строку.

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Расшифровывает строку на основе предоставленного типа алгоритма, ключа и параметров соли


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | источник | java.lang.String | Зашифрованная строка для декодирования. |
|

**Returns:**
java.lang.String — возвращает расшифрованную строку.

