---
title: "PdfDigitalSignatureAppearance"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Décrit l'apparence de la signature numérique sur les documents PDF."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Décrit l'apparence de la signature numérique sur les documents PDF.

--------------------

**Learn more**

 *  See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures][]
 *  See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties][]


[Advanced signing document with Digital electronic signatures]: https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/
[Advanced electronic signatures properties]: https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Crée un objet d'apparence de signature avec les valeurs par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContactInfoLabel()](#getContactInfoLabel--) | Obtient ou définit l'étiquette d'informations de contact. |
| [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Obtient ou définit l'étiquette d'informations de contact. |
| [getReasonLabel()](#getReasonLabel--) | Obtient ou définit l'étiquette de raison. |
| [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Obtient ou définit l'étiquette de raison. |
| [getLocationLabel()](#getLocationLabel--) | Obtient ou définit l'étiquette d'emplacement. |
| [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Obtient ou définit l'étiquette d'emplacement. |
| [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Obtient ou définit l'étiquette signée numériquement. |
| [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Obtient ou définit l'étiquette signée numériquement. |
| [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Obtient ou définit l'étiquette de date de signature. |
| [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Obtient ou définit l'étiquette de date de signature. |
| [getBackground()](#getBackground--) | Obtient ou définit la couleur d'arrière-plan de l'apparence de la signature. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Obtient ou définit la couleur d'arrière-plan de l'apparence de la signature. |
| [setBackground(String value)](#setBackground-java.lang.String-) | Obtient ou définit la couleur d'arrière-plan de l'apparence de la signature. |
| [getFontFamilyName()](#getFontFamilyName--) | Obtient ou définit le nom de la famille de la Font pour afficher les étiquettes. |
| [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Obtient ou définit le nom de la famille de la Font pour afficher les étiquettes. |
| [getFontSize()](#getFontSize--) | Obtient ou définit la taille de la Font pour afficher les étiquettes. |
| [setFontSize(double value)](#setFontSize-double-) | Obtient ou définit la taille de la Font pour afficher les étiquettes. |
| [getForeground()](#getForeground--) | Obtient ou définit la couleur du texte au premier plan de l'apparence de la signature. |
| [setForeground(Color value)](#setForeground-java.awt.Color-) | Obtient ou définit la couleur du texte au premier plan de l'apparence de la signature. |
| [setForeground(String value)](#setForeground-java.lang.String-) | Obtient ou définit la couleur du texte au premier plan de l'apparence de la signature. |
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Crée un objet d'apparence de signature avec les valeurs par défaut.

### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Obtient ou définit l'étiquette d'informations de contact. Valeur par défaut : \"Contact\". Si cette valeur est vide, aucune étiquette de contact n'apparaîtra dans la zone de signature numérique.

**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Obtient ou définit l'étiquette d'informations de contact. Valeur par défaut : \"Contact\". Si cette valeur est vide, aucune étiquette de contact n'apparaîtra dans la zone de signature numérique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Obtient ou définit l'étiquette de raison. Valeur par défaut : \"Reason\". Si cette valeur est vide, aucune étiquette de raison n'apparaîtra dans la zone de signature numérique.

**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Obtient ou définit l'étiquette de raison. Valeur par défaut : \"Reason\". Si cette valeur est vide, aucune étiquette de raison n'apparaîtra dans la zone de signature numérique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Obtient ou définit l'étiquette d'emplacement. Valeur par défaut : \"Location\". Si cette valeur est vide, aucune étiquette d'emplacement n'apparaîtra dans la zone de signature numérique.

**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Obtient ou définit l'étiquette d'emplacement. Valeur par défaut : \"Location\". Si cette valeur est vide, aucune étiquette d'emplacement n'apparaîtra dans la zone de signature numérique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Obtient ou définit l'étiquette signée numériquement. Valeur par défaut : \"Digitally signed by\".

**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Obtient ou définit l'étiquette signée numériquement. Valeur par défaut : \"Digitally signed by\".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Obtient ou définit l'étiquette de date de signature. Valeur par défaut : \"Date\".

**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Obtient ou définit l'étiquette de date de signature. Valeur par défaut : \"Date\".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Obtient ou définit la couleur d'arrière-plan de l'apparence de la signature. Par défaut, la valeur est SystemColors.Windows

**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Obtient ou définit la couleur d'arrière-plan de l'apparence de la signature. Par défaut, la valeur est SystemColors.Windows

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Obtient ou définit la couleur d'arrière-plan de l'apparence de la signature. Par défaut, la valeur est SystemColors.Windows

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Obtient ou définit le nom de la famille de la Font pour afficher les étiquettes. La valeur par défaut est \"Arial\".

**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Obtient ou définit le nom de la famille de la Font pour afficher les étiquettes. La valeur par défaut est \"Arial\".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Obtient ou définit la taille de la Font pour afficher les étiquettes. La valeur par défaut est 10.

**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Obtient ou définit la taille de la Font pour afficher les étiquettes. La valeur par défaut est 10.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Obtient ou définit la couleur du texte au premier plan de l'apparence de la signature. Par défaut, la valeur est Color.FromArgb(76, 100, 255)

**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Obtient ou définit la couleur du texte au premier plan de l'apparence de la signature. Par défaut, la valeur est Color.FromArgb(76, 100, 255)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Obtient ou définit la couleur du texte au premier plan de l'apparence de la signature. Par défaut, la valeur est Color.FromArgb(76, 100, 255)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

