---
title: "SignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las opciones de firma."
type: docs
weight: 16
url: /es/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Representa las opciones de firma.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Obtiene o establece el número de página del documento para la firma. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Obtiene o establece el número de página del documento para la firma. |
|
|  | [getAllPages()](#getAllPages--) | Coloque la firma en todas las páginas del documento. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Coloque la firma en todas las páginas del documento. |
|
|  | [getAppearance()](#getAppearance--) | Apariencia adicional de la firma. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Apariencia adicional de la firma. |
|
|  | [getExtensions()](#getExtensions--) | Extensiones de firma. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Extensiones de firma. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opciones para especificar las páginas a firmar. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opciones para especificar las páginas a firmar. |
|
|  | [getSignatureType()](#getSignatureType--) | Obtenga el tipo de firma [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | Obtener o establecer el Tipo de Documento de las Opciones de Firma [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | Obtener o establecer el Tipo de Documento de las Opciones de Firma [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | Obtiene o establece la posición Z-order de la firma de texto. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | Obtiene o establece la posición Z-order de la firma de texto. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Obtiene o establece el número de página del documento para la firma.
El valor mínimo y predeterminado es 1.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Obtiene o establece el número de página del documento para la firma.
El valor mínimo y predeterminado es 1.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Coloque la firma en todas las páginas del documento.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Coloque la firma en todas las páginas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Apariencia adicional de la firma.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Apariencia adicional de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Extensiones de firma.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Extensiones de firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Opciones para especificar las páginas a firmar.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Opciones para especificar las páginas a firmar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Obtenga el tipo de firma [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Obtener o establecer el Tipo de Documento de las Opciones de Firma [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Obtener o establecer el Tipo de Documento de las Opciones de Firma [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Obtiene o establece la posición Z-order de la firma de texto.
Determina el orden de visualización de firmas superpuestas.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Obtiene o establece la posición Z-order de la firma de texto.
Determina el orden de visualización de firmas superpuestas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas.
Compatible exclusivamente con firmas digitales en archivos PDF.
El valor es una de las constantes en [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm).


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Obtiene o establece el algoritmo hash que se utilizará para operaciones criptográficas.
Compatible exclusivamente con firmas digitales en archivos PDF.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
