---
title: SymmetricEncryption
second_title: GroupDocs.Editor for Java API Reference
description: Implements standard symmetric algorithms for data encryption with single key and passphrase salt.
type: docs
weight: 11
url: /java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Implements standard symmetric algorithms for data encryption with single key and passphrase (salt).
## Constructors

| Constructor | Description |
| --- | --- |
| [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Creates symmetric encryption algorithm with parameters. |
| [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Creates symmetric encryption algorithm with default passphrase |
## Methods

| Method | Description |
| --- | --- |
| [getAlgorithmType()](#getAlgorithmType--) | Gets or sets type of symmetric algorithm. |
| [setAlgorithmType(int value)](#setAlgorithmType-int-) | Gets or sets type of symmetric algorithm. |
| [getKey()](#getKey--) | Gets or sets key of encryption algorithm. |
| [setKey(String value)](#setKey-java.lang.String-) | Gets or sets key of encryption algorithm. |
| [getSalt()](#getSalt--) | Gets or sets passphrase of encryption algorithm. |
| [setSalt(String value)](#setSalt-java.lang.String-) | Gets or sets passphrase of encryption algorithm. |
| [encode(String source)](#encode-java.lang.String-) | Encrypts string based on provided algorithm type, key and salt parameters |
| [decode(String source)](#decode-java.lang.String-) | Decrypts string based on provided algorithm type, key and salt parameters |
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Creates symmetric encryption algorithm with parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| algorithmType | int | Specify symmetric algorithm type |
| key | java.lang.String | Encryption key |
| salt | java.lang.String | Passphrase for encryption |

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Creates symmetric encryption algorithm with default passphrase

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| algorithmType | int | Specify symmetric algorithm type |
| key | java.lang.String | Encryption key |

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Gets or sets type of symmetric algorithm.

**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Gets or sets type of symmetric algorithm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Gets or sets key of encryption algorithm.

**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Gets or sets key of encryption algorithm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Gets or sets passphrase of encryption algorithm.

**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Gets or sets passphrase of encryption algorithm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Encrypts string based on provided algorithm type, key and salt parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Source string to encode. |

**Returns:**
java.lang.String - Returns encrypted string.
### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Decrypts string based on provided algorithm type, key and salt parameters

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Encrypted string to decode. |

**Returns:**
java.lang.String - Returns decrypted string.
