---
title: "HIBCLICPrimaryData"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Clase para almacenar los datos primarios del HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Clase para almacenar datos primarios HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Constructor predeterminado ctor() |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifica la fecha del código de identificación del etiquetador. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifica la fecha del código de identificación del etiquetador. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifica el número de producto o catálogo. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifica el número de producto o catálogo. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifica el ID de unidad de medida. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifica el ID de unidad de medida. |
|
|  | [deepClone()](#deepClone--) | Obtiene una copia de este objeto. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Constructor predeterminado ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Identifica la fecha del código de identificación del etiquetador. El código de identificación del etiquetador debe
ser una cadena alfanumérica de 4 símbolos, con el primer carácter siempre alfabético.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Identifica la fecha del código de identificación del etiquetador. El código de identificación del etiquetador debe
ser una cadena alfanumérica de 4 símbolos, con el primer carácter siempre alfabético.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Identifica el número de producto o catálogo. El número de producto o catálogo debe ser alfanumérico
cadena de hasta 18 símbolos de longitud.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Identifica el número de producto o catálogo. El número de producto o catálogo debe ser alfanumérico
cadena de hasta 18 símbolos de longitud.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Identifica el ID de unidad de medida. El ID de unidad de medida debe ser un valor entero de 0 a 9.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Identifica el ID de unidad de medida. El ID de unidad de medida debe ser un valor entero de 0 a 9.


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
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
