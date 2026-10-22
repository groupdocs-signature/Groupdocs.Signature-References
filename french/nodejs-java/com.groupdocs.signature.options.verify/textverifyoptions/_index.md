---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Conserve les options pour vérifier la signature texte du document."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Conserve les options pour vérifier la signature texte du document.

--------------------

**Learn more**

 *  Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/
[Advanced usage of eVerification Barcode signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-text-signatures/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextVerifyOptions()](#TextVerifyOptions--) | Initialise une nouvelle instance de TextVerifyOptions avec les valeurs par défaut. |
| [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Initialise une nouvelle instance de TextVerifyOptions avec le texte de vérification. |
| [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Initialise une nouvelle instance de TextVerifyOptions avec la propriété Text à vérifier et l'implémentation de la signature. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Spécifiez le texte de la signature s'il doit être vérifié. |
| [setText(String value)](#setText-java.lang.String-) | Spécifiez le texte de la signature s'il doit être vérifié. |
| [getMatchType()](#getMatchType--) | Obtient ou définit la vérification du type de correspondance du texte. |
| [setMatchType(int value)](#setMatchType-int-) | Obtient ou définit la vérification du type de correspondance du texte. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Type de signature à vérifier. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Type de signature à vérifier. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Obtient ou définit le titre du champ de formulaire à vérifier. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Obtient ou définit le titre du champ de formulaire à vérifier. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Obtient ou définit le type du champ de formulaire à vérifier. |
| [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Obtient ou définit le type du champ de formulaire à vérifier. |
| [getSignatureID()](#getSignatureID--) | Spécifiez un ID de signature texte supérieur à zéro s'il doit être vérifié. |
| [setSignatureID(int value)](#setSignatureID-int-) | Spécifiez un ID de signature texte supérieur à zéro s'il doit être vérifié. |
| [toString()](#toString--) | Surcharge la conversion en chaîne. |
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Initialise une nouvelle instance de TextVerifyOptions avec les valeurs par défaut.

### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Initialise une nouvelle instance de TextVerifyOptions avec le texte de vérification.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Texte à vérifier |

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Initialise une nouvelle instance de TextVerifyOptions avec la propriété Text à vérifier et l'implémentation de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Texte à vérifier. |
| implémentation | int | Type d'implémentation de la signature. |

### getText() {#getText--}
```
public final String getText()
```


Spécifiez le texte de la signature s'il doit être vérifié.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Spécifiez le texte de la signature s'il doit être vérifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtient ou définit la vérification du type de correspondance du texte.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtient ou définit la vérification du type de correspondance du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Type de signature à vérifier.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Type de signature à vérifier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Obtient ou définit le titre du champ de formulaire à vérifier. Si cette propriété est définie, le texte ne sera trouvé que dans les champs de formulaire texte.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Obtient ou définit le titre du champ de formulaire à vérifier. Si cette propriété est définie, le texte ne sera trouvé que dans les champs de formulaire texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Obtient ou définit le type du champ de formulaire à vérifier. Si cette propriété est définie, le texte ne sera trouvé que dans les champs de formulaire texte.

**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Obtient ou définit le type du champ de formulaire à vérifier. Si cette propriété est définie, le texte ne sera trouvé que dans les champs de formulaire texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Spécifiez un ID de signature texte supérieur à zéro s'il doit être vérifié. Cette propriété n'est prise en charge que pour les documents PDF.

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Spécifiez un ID de signature texte supérieur à zéro s'il doit être vérifié. Cette propriété n'est prise en charge que pour les documents PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### toString() {#toString--}
```
public String toString()
```


Surcharge la conversion en chaîne.

**Returns:**
java.lang.String -
