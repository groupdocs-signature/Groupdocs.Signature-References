---
title: "IDataEncryption"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "ऑब्जेक्ट एन्कोडिंग और डिकोडिंग मेथड्स प्रदान करने के लिए एन्क्रिप्शन इंटरफ़ेस।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.signature.domain.extensions.encryption/idataencryption/
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
