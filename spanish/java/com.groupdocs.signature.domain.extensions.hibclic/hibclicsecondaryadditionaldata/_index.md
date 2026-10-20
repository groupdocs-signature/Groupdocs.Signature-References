---
title: "HIBCLICSecondaryAdditionalData"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Clase para almacenar los datos secundarios y adicionales del HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Clase para almacenar datos secundarios y adicionales de HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Constructor predeterminado ctor() |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifica el formato de la fecha de vencimiento. |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Identifica el formato de la fecha de vencimiento. |
|
|  | [getExpiryDate()](#getExpiryDate--) | Identifica la fecha de vencimiento. |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Identifica la fecha de vencimiento. |
|
|  | [getLotNumber()](#getLotNumber--) | Identifica el número de lote o partida. |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifica el número de lote o partida. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Identifica el número de serie. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifica el número de serie. |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | Identifica la fecha de fabricación. |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Identifica la fecha de fabricación. |
|
|  | [getQuantity()](#getQuantity--) | Identifica la cantidad, debe ser un valor entero de 0 a 500. |
|
|  | [setQuantity(int value)](#setQuantity-int-) | Identifica la cantidad, debe ser un valor entero de 0 a 500. |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | Identifica el carácter de enlace en la cadena de salida. |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | Identifica el carácter de enlace en la cadena de salida. |
|
|  | [deepClone()](#deepClone--) | Obtiene una copia de este objeto. |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Constructor predeterminado ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Identifica el formato de la fecha de vencimiento.


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Identifica el formato de la fecha de vencimiento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Identifica la fecha de vencimiento. Se usará si ExpiryDateFormat no está configurado a None.


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Identifica la fecha de vencimiento. Se usará si ExpiryDateFormat no está configurado a None.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Identifica el número de lote o partida.
El número de lote/partida debe ser una cadena alfanumérica con una longitud de hasta 18 símbolos.


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Identifica el número de lote o partida.
El número de lote/partida debe ser una cadena alfanumérica con una longitud de hasta 18 símbolos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Identifica el número de serie.
El número de serie debe ser una cadena alfanumérica con una longitud de hasta 18 símbolos.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Identifica el número de serie.
El número de serie debe ser una cadena alfanumérica con una longitud de hasta 18 símbolos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Identifica la fecha de fabricación.
La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo.
Valor predeterminado: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Identifica la fecha de fabricación.
La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo.
Valor predeterminado: DateTime.MinValue


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Identifica la cantidad, debe ser un valor entero de 0 a 500.
La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Identifica la cantidad, debe ser un valor entero de 0 a 500.
La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Identifica el carácter de enlace en la cadena de salida.


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Identifica el carácter de enlace en la cadena de salida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Obtiene una copia de este objeto.


**Returns:**
java.lang.Object
