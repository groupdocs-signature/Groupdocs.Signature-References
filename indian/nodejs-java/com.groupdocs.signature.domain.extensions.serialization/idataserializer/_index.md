---
title: "IDataSerializer"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "ऑब्जेक्ट सीरियलाइज़ेशन और डीसिरियलाइज़ेशन विधियों को प्रदान करने के लिए सीरियलाइज़ेशन इंटरफ़ेस।"
type: docs
weight: 22
url: /hi/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/idataserializer/
---```
public interface IDataSerializer
```

Serialization interface to provide object serialization and deserialization methods.
## Methods

| Method | Description |
| --- | --- |
| [serialize(Object data)](#serialize-java.lang.Object-) | Serialize method to format object to string representing. |
| [<T>deserialize(String source, Class<T> type)](#-T-deserialize-java.lang.String-java.lang.Class-T--) | Deserialize method to obtain required object from string. |
### serialize(Object data) {#serialize-java.lang.Object-}
```
public abstract String serialize(Object data)
```


Serialize method to format object to string representing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | java.lang.Object | Source object to serialize |

**Returns:**
java.lang.String - 
### <T>deserialize(String source, Class<T> type) {#-T-deserialize-java.lang.String-java.lang.Class-T--}
```
public abstract T <T>deserialize(String source, Class<T> type)
```


Deserialize method to obtain required object from string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Source serialized string that contains object

 T : Type of return object |
| type | java.lang.Class<T> |  |

**Returns:**
T - 
