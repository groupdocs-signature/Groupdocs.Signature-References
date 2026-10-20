---
title: "MetadataSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de metadatos."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Contiene propiedades de firma de metadatos.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Especifica un nombre de metadato único. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Especifica un nombre de metadato único. |
|
|  | [getValue()](#getValue--) | Especifica el objeto de metadatos. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Especifica el objeto de metadatos. |
|
|  | [getType()](#getType--) | Especifica el tipo de valor de metadatos. |
|
|  | [setType(int value)](#setType-int-) | Especifica el tipo de valor de metadatos. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar las propiedades Value de la firma. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar las propiedades Value de la firma. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Obtenga el objeto del Valor de la Firma de Metadatos durante la deserialización. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtenga el objeto del Texto de la Firma de Metadatos durante la deserialización. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [toBoolean()](#toBoolean--) | Convierte a booleano. |
|
|  | [toInteger()](#toInteger--) | Convierte a entero. |
|
|  | [toDouble()](#toDouble--) | Convierte a Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Convierte a Double. |
|
|  | [toSingle()](#toSingle--) | Convierte a float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Convierte a float. |
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
|  | [deepClone()](#deepClone--) | Clona la instancia de Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Clona la instancia de Metadata Signature con el valor dado. |
|
### getName() {#getName--}
```
public final String getName()
```


Especifica un nombre de metadato único.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Especifica un nombre de metadato único.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Especifica el objeto de metadatos.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Especifica el objeto de metadatos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Especifica el tipo de valor de metadatos.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Especifica el tipo de valor de metadatos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar las propiedades Value de la firma.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar las propiedades Value de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Obtenga el objeto del Valor de la Firma de Metadatos durante la deserialización.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Instancia del objeto T


T
: Tipo de objeto para deserializar del valor de Metadatos

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Obtenga el objeto del Texto de la Firma de Metadatos durante la deserialización.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Establecer implementación personalizada de cifrado de datos |


T
: Tipo de objeto para deserializar del valor de Metadatos
|

**Returns:**
T -
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


### toDouble() {#toDouble--}
```
public double toDouble()
```


Convierte a Double.


**Returns:**
double - Devuelve el valor de la Firma de Metadatos como Double.

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

### toSingle() {#toSingle--}
```
public float toSingle()
```


Convierte a float.


**Returns:**
float - Devuelve el valor de la firma Metadata como float.

<br />

*** ** * ** ***

Lanza una excepción si el valor de Metadata no pudo ser convertido. Si el valor original es una cadena, se utilizará la información de la propiedad de cultura predeterminada de las propiedades de SignatureSettings  SignatureSettings.DefaultCulture ()

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

<br />

*** ** * ** ***

Convierte una propiedad booleana en "True" o "False". Para otro tipo de datos se utilizará el proveedor de formato de datos predeterminado.

<br />


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


Clona la instancia de Metadata Signature con el valor dado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Object | Valor para el nuevo objeto clonado. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

