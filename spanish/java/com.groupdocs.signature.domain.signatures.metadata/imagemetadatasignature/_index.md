---
title: "ImageMetadataSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de metadatos de imagen."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Contiene propiedades de firma de metadatos de imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Crea una firma de metadatos de imagen con Id y valor |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getId()](#getId--) | El identificador de la firma de metadatos de imagen. |
|
|  | [setId(int value)](#setId-int-) | El identificador de la firma de metadatos de imagen. |
|
|  | [getSize()](#getSize--) | Valor de solo lectura para obtener el tamaño del valor de Metadata |
|
|  | [setSize(int value)](#setSize-int-) | Valor de solo lectura para obtener el tamaño del valor de Metadata |
|
|  | [getDescription()](#getDescription--) | Valor de solo lectura para obtener la descripción de la firma de metadatos de imagen estándar |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona la instancia de Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Clona la instancia de firma de metadatos de imagen con el valor dado. |
|
|  | [toBoolean()](#toBoolean--) | Convierte a booleano. |
|
|  | [toInteger()](#toInteger--) | Convierte a entero. |
|
|  | [toLong()](#toLong--) | Convierte a long. |
|
|  | [toSingle()](#toSingle--) | Convierte a float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Convierte a float. |
|
|  | [toDouble()](#toDouble--) | Convierte a Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Convierte a Double. |
|
|  | [toDecimal()](#toDecimal--) | Convierte a Decimal. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Convierte a Decimal. |
|
|  | [toDateTime()](#toDateTime--) | Convierte a DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Convierte a DateTime. |
|
|  | [toString()](#toString--) | Convierte a cadena con el método ToString() sobrescrito |
|
|  | [toString(String format)](#toString-java.lang.String-) | Convierte a cadena con formato especificado |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Convierte a cadena con formato especificado |
|
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


Crea una firma de metadatos de imagen con Id y valor


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | id | int | Identificador único del nombre de la firma de Metadatos de Imagen. Consulte las referencias para las especificaciones de etiquetas Exif y los posibles valores de id. |
|
|  | valor | java.lang.Object | Valor de Metadatos |
|

### getId() {#getId--}
```
public final int getId()
```


El identificador de la firma de metadatos de imagen.
Vea la clase [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) que contiene la firma estándar con un valor Id predefinido.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


El identificador de la firma de metadatos de imagen.
Vea la clase [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) que contiene la firma estándar con un valor Id predefinido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Valor de solo lectura para obtener el tamaño del valor de Metadata


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Valor de solo lectura para obtener el tamaño del valor de Metadata


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Valor de solo lectura para obtener la descripción de la firma de metadatos de imagen estándar


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Sobrescribe el método Equals para comparar propiedades de la firma


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | firma | java.lang.Object | Objeto de firma con el que comparar. |
|

**Returns:**
boolean - Devuelve true si el objeto de firma pasado tiene el mismo tipo y todas sus propiedades son iguales a las propiedades de esta instancia.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sobrescribe el método GetHashCode


**Returns:**
int - Código hash de la firma

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona la instancia de Metadata Signature.


**Returns:**
java.lang.Object - Devuelve la instancia clonada de Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clona la instancia de firma de metadatos de imagen con el valor dado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Object | Valor para el nuevo objeto clonado. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Convierte a booleano.


**Returns:**
boolean - Devuelve el valor de la firma de Metadatos como booleano.

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadatos no se pudo convertir.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Convierte a entero.


**Returns:**
int - Devuelve el valor de la Firma de Metadatos como entero.

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadatos no se pudo convertir.

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


Convierte a long.


**Returns:**
long - Devuelve el valor de la firma de metadatos como long.

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadatos no se pudo convertir.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


Convierte a float.


**Returns:**
float - Devuelve el valor de la firma de metadatos de imagen como float.

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadatos no se pudo convertir. Si el valor original es basado en cadena, la información de la propiedad de cultura predeterminada se utilizará de las propiedades de SignatureSettings  SignatureSettings.DefaultCulture

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Convierte a float.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | proveedor | java.util.Locale | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadata no pudo ser convertido

<br />

|

**Returns:**
float - Devuelve el valor de la firma Metadata como float.

### toDouble() {#toDouble--}
```
public double toDouble()
```


Convierte a Double.


**Returns:**
double - Devuelve el valor de la firma de metadatos de imagen como Double.

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadatos no se pudo convertir. Si el valor original es basado en cadena, la información de la propiedad de cultura predeterminada se utilizará de las propiedades de SignatureSettings  SignatureSettings.DefaultCulture

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Convierte a Double.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | proveedor | java.util.Locale | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadata no pudo ser convertido

<br />

|

**Returns:**
double - Devuelve el valor de la Firma de Metadatos como Double.

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Convierte a Decimal.


**Returns:**
java.math.BigDecimal - Devuelve el valor de la firma de metadatos de imagen como Decimal.

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadatos no se pudo convertir. Si el valor original es basado en cadena, la información de la propiedad de cultura predeterminada se utilizará de las propiedades de SignatureSettings  SignatureSettings.DefaultCulture

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Convierte a Decimal.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | proveedor | java.util.Locale | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadata no pudo ser convertido

<br />

|

**Returns:**
java.math.BigDecimal - Devuelve el valor de la firma de metadatos como Decimal.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Convierte a DateTime.


**Returns:**
java.util.Date - Devuelve el valor de la firma Metadata como DateTime.

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadatos no se pudo convertir. Si el valor original es basado en cadena, la información de la propiedad de cultura predeterminada se utilizará de las propiedades de SignatureSettings  SignatureSettings.DefaultCulture

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Convierte a DateTime.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | proveedor | java.util.Locale | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadata no pudo ser convertido

<br />

|

**Returns:**
java.util.Date - Devuelve el valor de la firma Metadata como DateTime.

### toString() {#toString--}
```
public String toString()
```


Convierte a cadena con el método ToString() sobrescrito


**Returns:**
java.lang.String - Devuelve el valor de la firma Metadata como String.

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Convierte a cadena con formato especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | formato | java.lang.String | Cadena de formato de datos. |

<br />

*** ** * ** ***

Convierte una propiedad booleana en "True" o "False". Se utilizará la información de la propiedad de cultura predeterminada de las propiedades de SignatureSettings  SignatureSettings.DefaultCulture

<br />

|

**Returns:**
java.lang.String - Devuelve el valor de la firma Metadata como String.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Convierte a cadena con formato especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | formato | java.lang.String | Cadena de formato de datos. |
|
|  | proveedor | java.util.Locale | Proveedor de formato de datos para usar con operaciones de conversión de datos. |

<br />

*** ** * ** ***

Convierte una propiedad booleana en "True" o "False".

<br />

|

**Returns:**
java.lang.String - Devuelve el valor de la firma Metadata como String.

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

