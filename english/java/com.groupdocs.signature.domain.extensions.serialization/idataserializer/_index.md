---
title: IDataSerializer
second_title: GroupDocs.Signature for Java API Reference
description: Serialization interface to provide object serialization and deserialization methods.
type: docs
weight: 22
url: /java/com.groupdocs.signature.domain.extensions.serialization/idataserializer/
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
