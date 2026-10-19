---
title: "DigitalSignatureAppearance"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Décrit l'apparence de la ligne de signature pour la signature numérique."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Décrit l'apparence de la ligne de signature pour la signature numérique.
Une ligne de signature ne peut être appliquée qu'à une seule signature numérique.
La ligne de signature se trouve toujours sur la première page.
Cette fonctionnalité peut être utile pour les formats de fichiers .docx, .doc, .odt et .xlsx.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Crée un objet d'apparence de ligne de signature. |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Crée une apparence de ligne de signature avec les valeurs spécifiées (signataire, titre, e‑mail). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSigner()](#getSigner--) | Obtient ou définit le nom du signataire pour la ligne de signature. |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | Obtient ou définit le nom du signataire pour la ligne de signature. |
|
|  | [getTitle()](#getTitle--) | Obtient ou définit un titre pour la ligne de signature. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Obtient ou définit un titre pour la ligne de signature. |
|
|  | [getEmail()](#getEmail--) | Obtient ou définit un e‑mail qui sera affiché dans la ligne de signature. |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | Obtient ou définit un e‑mail qui sera affiché dans la ligne de signature. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Crée un objet d'apparence de ligne de signature.


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Crée une apparence de ligne de signature avec les valeurs spécifiées (signataire, titre, e‑mail).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signataire | java.lang.String | Nom du signataire. |
|
|  | titre | java.lang.String | Titre de la signature. |
|
|  | e‑mail | java.lang.String | E‑mail de l'auteur. |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Obtient ou définit le nom du signataire pour la ligne de signature.


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Obtient ou définit le nom du signataire pour la ligne de signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Obtient ou définit un titre pour la ligne de signature.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Obtient ou définit un titre pour la ligne de signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Obtient ou définit un e‑mail qui sera affiché dans la ligne de signature.


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Obtient ou définit un e‑mail qui sera affiché dans la ligne de signature.


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
