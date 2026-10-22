---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Décrit l'apparence de la ligne de signature pour la signature numérique."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Décrit l'apparence de Signature Line pour Digital Signature. Une Signature Line ne peut être appliquée qu'à une seule Digital Signature. Signature Line se trouve toujours sur la première page. Cette fonctionnalité peut être utile pour les formats de fichiers .docx, .doc, .odt et .xlsx.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Crée un objet d'apparence de Signature Line. |
| [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Crée une apparence de Signature Line avec les valeurs spécifiées (signer, title, email). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSigner()](#getSigner--) | Obtient ou définit le nom du signataire pour la Signature Line. |
| [setSigner(String value)](#setSigner-java.lang.String-) | Obtient ou définit le nom du signataire pour la Signature Line. |
| [getTitle()](#getTitle--) | Obtient ou définit un titre pour la Signature Line. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Obtient ou définit un titre pour la Signature Line. |
| [getEmail()](#getEmail--) | Obtient ou définit un courriel qui sera affiché dans la Signature Line. |
| [setEmail(String value)](#setEmail-java.lang.String-) | Obtient ou définit un courriel qui sera affiché dans la Signature Line. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Crée un objet d'apparence de Signature Line.

### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Crée une apparence de Signature Line avec les valeurs spécifiées (signer, title, email).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signataire | java.lang.String | Nom du signataire. |
| titre | java.lang.String | Titre de la signature. |
| courriel | java.lang.String | Courriel de l'auteur. |

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Obtient ou définit le nom du signataire pour la Signature Line.

**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Obtient ou définit le nom du signataire pour la Signature Line.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Obtient ou définit un titre pour la Signature Line.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Obtient ou définit un titre pour la Signature Line.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Obtient ou définit un courriel qui sera affiché dans la Signature Line.

**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Obtient ou définit un courriel qui sera affiché dans la Signature Line.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.

**Returns:**
java.lang.String -
