---
title: "EPC"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa el Código de Respuesta Rápida del European Payments Council."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Representa el Código de Respuesta Rápida del European Payments Council.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EPC()](#EPC--) | Instancia un nuevo objeto EPC. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Obtiene o establece el Nombre del Beneficiario. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el Nombre del Beneficiario. |
|
|  | [getBIC()](#getBIC--) | Obtiene o establece el BIC del Beneficiario con una longitud máxima de 11 caracteres. |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | Obtiene o establece el BIC del Beneficiario con una longitud máxima de 11 caracteres. |
|
|  | [getIBAN()](#getIBAN--) | Obtiene o establece la Cuenta del Beneficiario (IBAN). |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | Obtiene o establece la Cuenta del Beneficiario (IBAN). |
|
|  | [getAmount()](#getAmount--) | Obtiene o establece la cantidad. |
|
|  | [setAmount(double value)](#setAmount-double-) | Obtiene o establece la cantidad. |
|
|  | [getCode()](#getCode--) | Obtiene o establece el Código de Negocio con hasta 4 caracteres. |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | Obtiene o establece el Código de Negocio con hasta 4 caracteres. |
|
|  | [getReference()](#getReference--) | Obtiene o establece la Referencia de Pago (máximo 35 caracteres). |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Obtiene o establece la Referencia de Pago (máximo 35 caracteres). |
|
|  | [getRemittance()](#getRemittance--) | Obtiene o establece la Información de Remesa (máximo 140 caracteres). |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | Obtiene o establece la Información de Remesa (máximo 140 caracteres). |
|
|  | [getInformation()](#getInformation--) | Obtiene o establece la información de sugerencia. |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | Obtiene o establece la información de sugerencia. |
|
|  | [getVersion()](#getVersion--) | Implementación de la versión EPC / SEPA QR-Code. |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | Implementación de la versión EPC / SEPA QR-Code. |
|
|  | [getCharset()](#getCharset--) | Implementación del conjunto de caracteres EPC / SEPA QR-Code. |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | Implementación del conjunto de caracteres EPC / SEPA QR-Code. |
|
|  | [getIdentification()](#getIdentification--) | Identificación EPC / SEPA QR-Code. |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | Identificación EPC / SEPA QR-Code. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar las propiedades EPC |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
### EPC() {#EPC--}
```
public EPC()
```


Instancia un nuevo objeto EPC.


### getName() {#getName--}
```
public final String getName()
```


Obtiene o establece el Nombre del Beneficiario. La longitud máxima es de 70 caracteres.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtiene o establece el Nombre del Beneficiario. La longitud máxima es de 70 caracteres.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Obtiene o establece el BIC del Beneficiario con una longitud máxima de 11 caracteres.


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Obtiene o establece el BIC del Beneficiario con una longitud máxima de 11 caracteres.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Obtiene o establece la Cuenta del Beneficiario (IBAN). El IBAN consta de hasta 34 caracteres alfanuméricos.


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Obtiene o establece la Cuenta del Beneficiario (IBAN). El IBAN consta de hasta 34 caracteres alfanuméricos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Obtiene o establece la cantidad.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Obtiene o establece la cantidad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Obtiene o establece el Código de Negocio con hasta 4 caracteres.


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Obtiene o establece el Código de Negocio con hasta 4 caracteres.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Obtiene o establece la Referencia de Pago (máximo 35 caracteres). Este campo y el campo Información de Remesa son mutuamente excluyentes.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Obtiene o establece la Referencia de Pago (máximo 35 caracteres). Este campo y el campo Información de Remesa son mutuamente excluyentes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Obtiene o establece la Información de Remesa (máximo 140 caracteres). Este campo y el campo Referencia de Pago son mutuamente excluyentes.


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Obtiene o establece la Información de Remesa (máximo 140 caracteres). Este campo y el campo Referencia de Pago son mutuamente excluyentes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Obtiene o establece la información de pista. Máximo 70 caracteres.


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Obtiene o establece la información de pista. Máximo 70 caracteres.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Implementación de la versión EPC / SEPA QR-Code. Por defecto, este valor se establece en 002.


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Implementación de la versión EPC / SEPA QR-Code. Por defecto, este valor se establece en 002.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


Implementación del conjunto de caracteres EPC / SEPA QR-Code. Por defecto, este valor se establece en 1


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


Implementación del conjunto de caracteres EPC / SEPA QR-Code. Por defecto, este valor se establece en 1


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


Identificación EPC / SEPA QR-Code. Por defecto, este valor se establece en SCT


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


Identificación EPC / SEPA QR-Code. Por defecto, este valor se establece en SCT


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Sobrescribe el método Equals para comparar las propiedades EPC


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | origen | java.lang.Object | Objeto EPC con el que comparar. |
|

**Returns:**
boolean - Devuelve true si el objeto de dirección pasado tiene el mismo tipo y todas sus propiedades son iguales a las propiedades de esta instancia.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sobrescribe el método GetHashCode


**Returns:**
int - Código hash del correo electrónico

