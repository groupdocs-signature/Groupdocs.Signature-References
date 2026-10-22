---
title: "IDataEncryption"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Interfaccia Encryption per fornire metodi di codifica e decodifica degli oggetti."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.signature.domain.extensions.encryption/idataencryption/
---```
public interface IDataEncryption
```

Encryption interface to provide object encoding and decoding methods.
## Methods

| Method | Description |
| --- | --- |
| [encode(String source)](#encode-java.lang.String-) | Encode method to encrypt string. |
| [decode(String source)](#decode-java.lang.String-) | Decode method to obtain decrypted string. |
### encode(String source) {#encode-java.lang.String-}
```
public abstract String encode(String source)
```


Encode method to encrypt string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Source string to encode. |

**Returns:**
java.lang.String - Returns encrypted string
### decode(String source) {#decode-java.lang.String-}
```
public abstract String decode(String source)
```


Decode method to obtain decrypted string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Encrypted string to decode. |

**Returns:**
java.lang.String - Returns decrypted string
