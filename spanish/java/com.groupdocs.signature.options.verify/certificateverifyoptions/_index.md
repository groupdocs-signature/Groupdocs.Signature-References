---
title: "CertificateVerifyOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Mantiene opciones para verificar documentos de certificado."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Mantiene opciones para verificar documentos de certificado.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Inicializa una nueva instancia de TextVerifyOptions con valores predeterminados. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Inicializa una nueva instancia de CertificateVerifyOptions con el sujeto a verificar. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Especifique el emisor del certificado si debe verificarse. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Especifique el emisor del certificado si debe verificarse. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Especifique el número de serie del certificado si debe verificarse. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Especifique el número de serie del certificado si debe verificarse. |
|
|  | [getSubject()](#getSubject--) | Especifique el sujeto del certificado si debe verificarse. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Especifique el sujeto del certificado si debe verificarse. |
|
|  | [getThumbprint()](#getThumbprint--) | Especifique la huella digital del certificado si debe verificarse. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Especifique la huella digital del certificado si debe verificarse. |
|
|  | [getMatchType()](#getMatchType--) | Obtiene o establece la verificación del Tipo de Coincidencia de Texto. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Obtiene o establece la verificación del Tipo de Coincidencia de Texto. |
|
|  | [getExpired()](#getExpired--) | Indica si el certificado está vencido según el resultado de la validación. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Indica si el certificado está vencido según el resultado de la validación. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Obtenga o establezca si el proceso de verificación debe proporcionar la validación de cadena X.509 usando la política de validación básica. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Obtenga o establezca si el proceso de verificación debe proporcionar la validación de cadena X.509 usando la política de validación básica. |
|
|  | [toString()](#toString--) | Sobrescribe la conversión a cadena. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Inicializa una nueva instancia de TextVerifyOptions con valores predeterminados.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Inicializa una nueva instancia de CertificateVerifyOptions con el sujeto a verificar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | asunto | java.lang.String | Sujeto a verificar |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Especifique el emisor del certificado si debe verificarse.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Especifique el emisor del certificado si debe verificarse.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Especifique el número de serie del certificado si debe verificarse.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Especifique el número de serie del certificado si debe verificarse.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Especifique el sujeto del certificado si debe verificarse.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Especifique el sujeto del certificado si debe verificarse.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Especifique la huella digital del certificado si debe verificarse.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Especifique la huella digital del certificado si debe verificarse.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtiene o establece la verificación del Tipo de Coincidencia de Texto.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtiene o establece la verificación del Tipo de Coincidencia de Texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Indica si el certificado está vencido según el resultado de la validación.
La propiedad es de solo lectura.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Indica si el certificado está vencido según el resultado de la validación.
La propiedad es de solo lectura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Obtenga o establezca si el proceso de verificación debe proporcionar la validación de cadena X.509 usando la política de validación básica.
Por defecto, este valor es verdadero.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Obtenga o establezca si el proceso de verificación debe proporcionar la validación de cadena X.509 usando la política de validación básica.
Por defecto, este valor es verdadero.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribe la conversión a cadena.


**Returns:**
java.lang.String - 
