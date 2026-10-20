---
title: "Mailmark2D"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Clase para codificar y decodificar el texto incrustado en el Royal Mail 2D Mailmark."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Clase para codificar y decodificar el texto incrustado en el Royal Mail 2D Mailmark.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | Crea datos combinados de Royal Mail Mailmark con valores predeterminados de datos primarios y secundarios. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. |
|
|  | [getVersionID()](#getVersionID--) | Identifica la versión del código de barras según corresponda a cada ID de tipo de información. |
|
|  | [getClass_()](#getClass---) | Identifica la clase del artículo. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | Identifica la clase del artículo. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | Identifica el grupo único de clientes involucrados en el envío. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifica el grupo único de clientes involucrados en el envío. |
|
|  | [getItemID()](#getItemID--) | Identifica el artículo único dentro del ID de la cadena de suministro. |
|
|  | [setItemID(int value)](#setItemID-int-) | Identifica el artículo único dentro del ID de la cadena de suministro. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contiene el código postal de la dirección de entrega con DPS |
Si es interior, el código postal/DP contiene el siguiente número de caracteres.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contiene el código postal de la dirección de entrega con DPS |
Si es interior, el código postal/DP contiene el siguiente número de caracteres.
|
|  | [getRTSFlag()](#getRTSFlag--) | Indicador que muestra qué nivel de servicio de Devolución al Remitente se está solicitando. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Indicador que muestra qué nivel de servicio de Devolución al Remitente se está solicitando. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contiene el código postal de Devolución al Remitente pero sin DPS. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contiene el código postal de Devolución al Remitente pero sin DPS. |
|
|  | [getCustomerContent()](#getCustomerContent--) | Espacio opcional para uso del cliente. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Espacio opcional para uso del cliente. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Modo de codificación del código de barras DataMatrix. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Modo de codificación del código de barras DataMatrix. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | El tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | El tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
|
|  | [deepClone()](#deepClone--) | Obtiene una copia de este objeto. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Crea datos combinados de Royal Mail Mailmark con valores predeterminados de datos primarios y secundarios.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Identifica el ID de país UPU. Longitud máxima: 4 caracteres.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Identifica el ID de país UPU. Longitud máxima: 4 caracteres.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto.

<br />

*** ** * ** ***

Valores válidos: "0" - Doméstico clasificado y no clasificado "A" - Envío en línea "B" - Franqueo "C" - Consolidación

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto.

<br />

*** ** * ** ***

Valores válidos: "0" - Doméstico clasificado y no clasificado "A" - Envío en línea "B" - Franqueo "C" - Consolidación

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Identifica la versión del código de barras según corresponda a cada ID de tipo de información.

<br />

*** ** * ** ***

Valores válidos: "1" - actualmente usado solo este valor (predeterminado) "0" y "2" a "9" y "A" a "Z" reservados para posible uso futuro.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Identifica la clase del artículo.

<br />

*** ** * ** ***

Valores válidos: "1" - 1C (Minorista) "2" - 2C (Minorista) "3" - Economía (Minorista) "5" - Diferido (Minorista) "8" - Premium (Acceso a red) "9" - Estándar (Acceso a red)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Identifica la clase del artículo.

<br />

*** ** * ** ***

Valores válidos: "1" - 1C (Minorista) "2" - 2C (Minorista) "3" - Economía (Minorista) "5" - Diferido (Minorista) "8" - Premium (Acceso a red) "9" - Estándar (Acceso a red)

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Identifica el grupo único de clientes involucrados en el envío.
Valor máximo: 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Identifica el grupo único de clientes involucrados en el envío.
Valor máximo: 9999999.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Identifica el artículo único dentro del ID de la cadena de suministro.
Se requiere que cada código de barras Mailmark lleve un ID para que pueda ser identificado de forma única durante al menos 90 días.
Valor máximo: 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Identifica el artículo único dentro del ID de la cadena de suministro.
Se requiere que cada código de barras Mailmark lleve un ID para que pueda ser identificado de forma única durante al menos 90 días.
Valor máximo: 99999999.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Contiene el código postal de la dirección de entrega con DPS
Si es interior, el código postal/DP contiene el siguiente número de caracteres.
Área (1 o 2 caracteres)
Distrito(1 o 2 caracteres)
Sector(1 carácter)
Unidad(2 caracteres)
DPS (2 caracteres).
El código postal y DPS deben cumplir con un formato PAF® válido. La longitud máxima es 9.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Contiene el código postal de la dirección de entrega con DPS
Si es interior, el código postal/DP contiene el siguiente número de caracteres.
Área (1 o 2 caracteres)
Distrito(1 o 2 caracteres)
Sector(1 carácter)
Unidad(2 caracteres)
DPS (2 caracteres).
El código postal y DPS deben cumplir con un formato PAF® válido. La longitud máxima es 9.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Indicador que muestra qué nivel del servicio Devolver al Remitente se está solicitando. La longitud máxima es 1.


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Indicador que muestra qué nivel del servicio Devolver al Remitente se está solicitando. La longitud máxima es 1.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Contiene el código postal de Devolución al Remitente pero sin DPS.
El PC(sin DPS) debe cumplir con un formato PAF®.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Contiene el código postal de Devolución al Remitente pero sin DPS.
El PC(sin DPS) debe cumplir con un formato PAF®.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Espacio opcional para uso del cliente.

<br />

*** ** * ** ***

Longitud máxima por Tipo [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Tipo 7: 6 caracteres Tipo 9: 45 caracteres Tipo 29: 25 caracteres

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Espacio opcional para uso del cliente.

<br />

*** ** * ** ***

Longitud máxima por Tipo [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Tipo 7: 6 caracteres Tipo 9: 45 caracteres Tipo 29: 25 caracteres

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Modo de codificación del código de barras DataMatrix. Valor predeterminado: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Modo de codificación del código de barras DataMatrix. Valor predeterminado: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


El tipo 2D Mailmark define el tamaño del código de barras Data Matrix.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


El tipo 2D Mailmark define el tamaño del código de barras Data Matrix.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Obtiene una copia de este objeto.


**Returns:**
java.lang.Object
