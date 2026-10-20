---
title: "SwissAddress"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa la dirección del acreedor o deudor."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Representa la dirección del acreedor o deudor.
Puede establecer la calle, el número de casa, el código postal y la ciudad (tipo de dirección estructurada)
o la línea de dirección 1 y 2 (tipo de elementos de dirección combinados).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Obtiene o establece el nombre, ya sea el nombre y apellido de una persona física o |
el nombre de la empresa de una persona jurídica.
|
|  | [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre, ya sea el nombre y apellido de una persona física o |
el nombre de la empresa de una persona jurídica.
|
|  | [getAddressLine1()](#getAddressLine1--) | Obtiene o establece la línea de dirección 1. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Obtiene o establece la línea de dirección 1. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Obtiene o establece la línea de dirección 2. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Obtiene o establece la línea de dirección 2. |
|
|  | [getStreet()](#getStreet--) | Obtiene o establece la calle. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Obtiene o establece la calle. |
|
|  | [getHouseNo()](#getHouseNo--) | Obtiene o establece el número de casa. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Obtiene o establece el número de casa. |
|
|  | [getPostalCode()](#getPostalCode--) | Obtiene o establece el código postal. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Obtiene o establece el código postal. |
|
|  | [getTown()](#getTown--) | Obtiene o establece la localidad o la ciudad. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Obtiene o establece la localidad o la ciudad. |
|
|  | [getCountryCode()](#getCountryCode--) | Obtiene o establece el código de país ISO de dos letras. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Obtiene o establece el código de país ISO de dos letras. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Obtiene o establece el nombre, ya sea el nombre y apellido de una persona física o
el nombre de la empresa de una persona jurídica.
Valor: El nombre.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtiene o establece el nombre, ya sea el nombre y apellido de una persona física o
el nombre de la empresa de una persona jurídica.
Valor: El nombre.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Obtiene o establece la línea de dirección 1.
La línea de dirección 1 contiene el nombre de la calle, el número de casa o P.O. box.
Este campo solo se usa para direcciones de elementos combinados y es opcional.
Valor: La línea de dirección 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Obtiene o establece la línea de dirección 1.
La línea de dirección 1 contiene el nombre de la calle, el número de casa o P.O. box.
Este campo solo se usa para direcciones de elementos combinados y es opcional.
Valor: La línea de dirección 1.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Obtiene o establece la línea de dirección 2.
La línea de dirección 2 contiene el código postal y la localidad.
Este campo solo se usa para direcciones de elementos combinados. Para este tipo, es obligatorio.
Valor: La línea de dirección 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Obtiene o establece la línea de dirección 2.
La línea de dirección 2 contiene el código postal y la localidad.
Este campo solo se usa para direcciones de elementos combinados. Para este tipo, es obligatorio.
Valor: La línea de dirección 2.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Obtiene o establece la calle.
La calle debe especificarse sin número de casa.
Este campo solo se usa para direcciones estructuradas y es opcional.
Valor: La calle.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Obtiene o establece la calle.
La calle debe especificarse sin número de casa.
Este campo solo se usa para direcciones estructuradas y es opcional.
Valor: La calle.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Obtiene o establece el número de casa.
Este campo solo se usa para direcciones estructuradas y es opcional.
Valor: El número de casa.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Obtiene o establece el número de casa.
Este campo solo se usa para direcciones estructuradas y es opcional.
Valor: El número de casa.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Obtiene o establece el código postal.
Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.
Valor: El código postal.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Obtiene o establece el código postal.
Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.
Valor: El código postal.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Obtiene o establece la localidad o la ciudad.
Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.
Valor: La localidad o la ciudad.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Obtiene o establece la localidad o la ciudad.
Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio.
Valor: La localidad o la ciudad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Obtiene o establece el código de país ISO de dos letras.
El código de país es obligatorio a menos que toda la dirección contenga valores nulos o vacíos.
Valor: El código de país ISO.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Obtiene o establece el código de país ISO de dos letras.
El código de país es obligatorio a menos que toda la dirección contenga valores nulos o vacíos.
Valor: El código de país ISO.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

