---
title: ImageMetadataSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains Image Metadata signature properties.
type: docs
weight: 10
url: /java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Contains Image Metadata signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Creates Image Metadata Signature with Id and value |
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | The identifier of Image Metadata signature. |
| [setId(int value)](#setId-int-) | The identifier of Image Metadata signature. |
| [getSize()](#getSize--) | Read-only value to get size of Metadata value |
| [setSize(int value)](#setSize-int-) | Read-only value to get size of Metadata value |
| [getDescription()](#getDescription--) | Read-only value to get description for standard Image Metadata signature |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone Metadata Signature instance. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clone Image Metadata Signature instance with given value. |
| [toBoolean()](#toBoolean--) | Converts to boolean. |
| [toInteger()](#toInteger--) | Converts to integer. |
| [toLong()](#toLong--) | Converts to long. |
| [toSingle()](#toSingle--) | Converts to float. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Converts to float. |
| [toDouble()](#toDouble--) | Converts to Double. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Converts to Double. |
| [toDecimal()](#toDecimal--) | Converts to Decimal. |
| [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Converts to Decimal. |
| [toDateTime()](#toDateTime--) | Converts to DateTime. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Converts to DateTime. |
| [toString()](#toString--) | Converts to String with override ToString() method |
| [toString(String format)](#toString-java.lang.String-) | Converts to String with specified format |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Converts to String with specified format |
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Creates Image Metadata Signature with Id and value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Unique identifier Image Metadata Signature name. See references for Exif tags specifications for possible id values |
| value | java.lang.Object | Metadata value |

### getId() {#getId--}
```
public final int getId()
```


The identifier of Image Metadata signature. See [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) class that contains standard Signature with predefined Id value.

**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


The identifier of Image Metadata signature. See [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) class that contains standard Signature with predefined Id value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Read-only value to get size of Metadata value

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Read-only value to get size of Metadata value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Read-only value to get description for standard Image Metadata signature

**Returns:**
java.lang.String
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


Clone Image Metadata Signature instance with given value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Value for new cloned object. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
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
### toLong() {#toLong--}
```
public final long toLong()
```


Converts to long.

**Returns:**
long - Returns the Metadata Signature value as long.

--------------------

Throws an exception if the Metadata value could not be converted.
### toSingle() {#toSingle--}
```
public final float toSingle()
```


Converts to float.

**Returns:**
float - Returns the Image Metadata Signature value as float.

--------------------

Throws an exception if the Metadata value could not be converted. If original value is string based the default culture property info will be used from SignatureSettings properties  SignatureSettings.DefaultCulture 
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
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
### toDouble() {#toDouble--}
```
public double toDouble()
```


Converts to Double.

**Returns:**
double - Returns the Image Metadata Signature value as Double.

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
### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Converts to Decimal.

**Returns:**
java.math.BigDecimal - Returns the Image Metadata Signature value as Decimal.

--------------------

Throws an exception if the Metadata value could not be converted. If original value is string based the default culture property info will be used from SignatureSettings properties  SignatureSettings.DefaultCulture 
### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Converts to Decimal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| provider | java.util.Locale | Format data provider to use with data conversion operations.

--------------------

Throws an exception if the Metadata value could not be converted |

**Returns:**
java.math.BigDecimal - Returns the Metadata Signature value as Decimal.
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
### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

