---
title: "PdfDigitalSignatureAppearance"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Describe la apariencia de la firma digital en documentos PDF."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Describe la apariencia de la firma digital en documentos PDF.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Crea un objeto de apariencia de firma con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | Obtiene o establece la etiqueta de información de contacto. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Obtiene o establece la etiqueta de información de contacto. |
|
|  | [getReasonLabel()](#getReasonLabel--) | Obtiene o establece la etiqueta de motivo. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Obtiene o establece la etiqueta de motivo. |
|
|  | [getLocationLabel()](#getLocationLabel--) | Obtiene o establece la etiqueta de ubicación. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Obtiene o establece la etiqueta de ubicación. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Obtiene o establece la etiqueta de firmado digital. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Obtiene o establece la etiqueta de firmado digital. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Obtiene o establece la etiqueta de fecha de firma. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Obtiene o establece la etiqueta de fecha de firma. |
|
|  | [getBackground()](#getBackground--) | Obtiene o establece el color de fondo de la apariencia de la firma. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | Obtiene o establece el color de fondo de la apariencia de la firma. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | Obtiene o establece el color de fondo de la apariencia de la firma. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | Obtiene o establece el nombre de la familia de fuentes para mostrar las etiquetas. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Obtiene o establece el nombre de la familia de fuentes para mostrar las etiquetas. |
|
|  | [getFontSize()](#getFontSize--) | Obtiene o establece el tamaño de fuente para mostrar las etiquetas. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | Obtiene o establece el tamaño de fuente para mostrar las etiquetas. |
|
|  | [getForeground()](#getForeground--) | Obtiene o establece el color del texto de primer plano de la apariencia de la firma. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | Obtiene o establece el color del texto de primer plano de la apariencia de la firma. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | Obtiene o establece el color del texto de primer plano de la apariencia de la firma. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Crea un objeto de apariencia de firma con valores predeterminados.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Obtiene o establece la etiqueta de información de contacto. Valor predeterminado: "Contact".
si este valor está vacío, no aparecerá ninguna etiqueta de contacto en el área de firma digital.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Obtiene o establece la etiqueta de información de contacto. Valor predeterminado: "Contact".
si este valor está vacío, no aparecerá ninguna etiqueta de contacto en el área de firma digital.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Obtiene o establece la etiqueta de motivo. Valor predeterminado: "Reason".
si este valor está vacío, no aparecerá ninguna etiqueta de motivo en el área de firma digital.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Obtiene o establece la etiqueta de motivo. Valor predeterminado: "Reason".
si este valor está vacío, no aparecerá ninguna etiqueta de motivo en el área de firma digital.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Obtiene o establece la etiqueta de ubicación. Valor predeterminado: "Location".
si este valor está vacío, no aparecerá ninguna etiqueta de ubicación en el área de firma digital.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Obtiene o establece la etiqueta de ubicación. Valor predeterminado: "Location".
si este valor está vacío, no aparecerá ninguna etiqueta de ubicación en el área de firma digital.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Obtiene o establece la etiqueta de firmado digital. Valor predeterminado: "Digitally signed by".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Obtiene o establece la etiqueta de firmado digital. Valor predeterminado: "Digitally signed by".


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Obtiene o establece la etiqueta de fecha de firma. Valor predeterminado: "Date".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Obtiene o establece la etiqueta de fecha de firma. Valor predeterminado: "Date".


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Obtiene o establece el color de fondo de la apariencia de la firma.
Por defecto, el valor es SystemColors.Windows


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Obtiene o establece el color de fondo de la apariencia de la firma.
Por defecto, el valor es SystemColors.Windows


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Obtiene o establece el color de fondo de la apariencia de la firma.
Por defecto, el valor es SystemColors.Windows


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Obtiene o establece el nombre de la familia de fuentes para mostrar las etiquetas. El valor predeterminado es "Arial".


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Obtiene o establece el nombre de la familia de fuentes para mostrar las etiquetas. El valor predeterminado es "Arial".


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Obtiene o establece el tamaño de fuente para mostrar las etiquetas. El valor predeterminado es 10.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Obtiene o establece el tamaño de fuente para mostrar las etiquetas. El valor predeterminado es 10.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Obtiene o establece el color del texto de primer plano de la apariencia de la firma.
Por defecto, el valor es Color.FromArgb(76, 100, 255)


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Obtiene o establece el color del texto de primer plano de la apariencia de la firma.
Por defecto, el valor es Color.FromArgb(76, 100, 255)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Obtiene o establece el color del texto de primer plano de la apariencia de la firma.
Por defecto, el valor es Color.FromArgb(76, 100, 255)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

