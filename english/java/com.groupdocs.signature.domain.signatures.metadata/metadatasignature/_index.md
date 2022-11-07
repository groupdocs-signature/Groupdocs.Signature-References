---
title: MetadataSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains Metadata signature properties.
type: docs
weight: 11
url: /java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Contains Metadata signature properties.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Specifies unique metadata name. |
| [setName(String value)](#setName-java.lang.String-) | Specifies unique metadata name. |
| [getValue()](#getValue--) | Specifies metadata object. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Specifies metadata object. |
| [getDataEncryption()](#getDataEncryption--) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode signature Value properties. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode signature Value properties. |
| [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Obtain object from Metadata Signature Value over deserialization. |
| [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtain object from Metadata Signature Text over deserialization. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [toBoolean()](#toBoolean--) | Converts to boolean. |
| [toInteger()](#toInteger--) | Converts to integer. |
| [toDouble()](#toDouble--) | Converts to Double. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Converts to Double. |
| [toSingle()](#toSingle--) | Converts to float. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Converts to float. |
| [toDateTime()](#toDateTime--) | Converts to DateTime. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Converts to DateTime. |
| [toString()](#toString--) | Converts to String with override ToString() method |
| [toString(String format)](#toString-java.lang.String-) | Converts to String with specified format |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Converts to String with specified format |
| [getType()](#getType--) | Specifies metadata value type. |
| [setType(int value)](#setType-int-) | Specifies metadata value type. |
| [deepClone()](#deepClone--) | Clone Metadata Signature instance. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clone Metadata Signature instance with given value. |
### getName() {#getName--}
```
public final String getName()
```


Specifies unique metadata name.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specifies unique metadata name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Specifies metadata object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Specifies metadata object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode signature Value properties.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode signature Value properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Obtain object from Metadata Signature Value over deserialization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Instance of T object

 T : Type of object to deserialize from Metadata value
### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Obtain object from Metadata Signature Text over deserialization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Set custom data encryption implementation

 T : Type of object to deserialize from Metadata Value |

**Returns:**
T - 
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overwrites Equals method to compare signature properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Signature object to compare with. |

**Returns:**
boolean - Returns true if passed signature object has same type and all its properties are equal to this instance properties.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Overrides GetHashCode method

**Returns:**
int - Signature hash code
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Converts to boolean.

**Returns:**
boolean - Returns the Metadata signature value as boolean.

--------------------

Throws an exception if the Metadata value could not be converted.
### toInteger() {#toInteger--}
```
public int toInteger()
```


Converts to integer.

**Returns:**
int - Returns the Metadata Signature value as integer.

--------------------

Throws an exception if the Metadata value could not be converted.
### toDouble() {#toDouble--}
```
public double toDouble()
```


Converts to Double.

**Returns:**
double - Returns the Metadata Signature value as Double.

--------------------

Throws an exception if the Metadata value could not be converted. If original value is string based the default culture property info will be used from SignatureSettings properties  SignatureSettings.DefaultCulture 
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Converts to Double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| provider | java.util.Locale | Format data provider to use with data conversion operations.

--------------------

Throws an exception if the Metadata value could not be converted |

**Returns:**
double - Returns the Metadata Signature value as Double.
### toSingle() {#toSingle--}
```
public float toSingle()
```


Converts to float.

**Returns:**
float - Returns the Metadata Signature value as float.

--------------------

Throws an exception if the Metadata value could not be converted. If original value is string based the default culture property info will be used from SignatureSettings properties  SignatureSettings.DefaultCulture ()
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


Converts to float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| provider | java.util.Locale | Format data provider to use with data conversion operations.

--------------------

Throws an exception if the Metadata value could not be converted |

**Returns:**
float - Returns the Metadata Signature value as float.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Converts to DateTime.

**Returns:**
java.util.Date - Returns the Metadata Signature value as DateTime.

--------------------

Throws an exception if the Metadata value could not be converted. If original value is string based the default culture property info will be used from SignatureSettings properties  SignatureSettings.DefaultCulture 
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Converts to DateTime.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| provider | java.util.Locale | Format data provider to use with data conversion operations.

--------------------

Throws an exception if the Metadata value could not be converted |

**Returns:**
java.util.Date - Returns the Metadata Signature value as DateTime.
### toString() {#toString--}
```
public String toString()
```


Converts to String with override ToString() method

**Returns:**
java.lang.String - Returns the Metadata Signature value as String.

--------------------

Converts a boolean property into "True" or "False". For another data type the default data format provider will be used.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Converts to String with specified format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Data format string.

--------------------

Converts a boolean property into "True" or "False". Default culture property info will be used from SignatureSettings properties  SignatureSettings.DefaultCulture  |

**Returns:**
java.lang.String - Returns the Metadata Signature value as String.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Converts to String with specified format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Data format string. |
| provider | java.util.Locale | Format data provider to use with data conversion operations.

--------------------

Converts a boolean property into "True" or "False". |

**Returns:**
java.lang.String - Returns the Metadata Signature value as String.
### getType() {#getType--}
```
public final int getType()
```


Specifies metadata value type.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Specifies metadata value type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone Metadata Signature instance.

**Returns:**
java.lang.Object - Returns cloned Metadata Signature instance
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clone Metadata Signature instance with given value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Value for new cloned object. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.
