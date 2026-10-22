---
title: "BaseSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Décrit la classe de base pour les signatures."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Décrit la classe de base pour les signatures.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSignatureType()](#getSignatureType--) | Spécifie le type de signature. |
| [getPageNumber()](#getPageNumber--) | Spécifie la page sur laquelle la signature a été trouvée. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Spécifie la page sur laquelle la signature a été trouvée. |
| [getSignatureId()](#getSignatureId--) | Identifiant unique de la signature pour modifier la signature dans le document via les méthodes Update ou Delete. |
| [isSignature()](#isSignature--) | Obtenir ou définir le drapeau indiquant si cet élément est une signature ou le contenu du document. |
| [setSignature(boolean value)](#setSignature-boolean-) | Obtenir ou définir le drapeau indiquant si cet élément est une signature ou le contenu du document. |
| [getDeleted()](#getDeleted--) | Obtenir ou définir le drapeau indiquant si cette signature a été supprimée du document. |
| [getCreatedOn()](#getCreatedOn--) | Obtenir ou définir la date de création de la signature. |
| [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Obtenir ou définir la date de création de la signature. |
| [getModifiedOn()](#getModifiedOn--) | Obtenir ou définir la date de modification de la signature. |
| [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Obtenir ou définir la date de modification de la signature. |
| [getTop()](#getTop--) | Spécifie la position supérieure de la signature. |
| [setTop(int value)](#setTop-int-) | Spécifie la position supérieure de la signature. |
| [getLeft()](#getLeft--) | Spécifie la position gauche de la signature. |
| [setLeft(int value)](#setLeft-int-) | Spécifie la position gauche de la signature. |
| [getWidth()](#getWidth--) | Spécifie la largeur de la signature. |
| [setWidth(int value)](#setWidth-int-) | Spécifie la largeur de la signature. |
| [getHeight()](#getHeight--) | Spécifie la hauteur de la signature. |
| [setHeight(int value)](#setHeight-int-) | Spécifie la hauteur de la signature. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
| [toString()](#toString--) |  |
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Spécifie le type de signature. La signature numérique aura cette propriété.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Spécifie la page sur laquelle la signature a été trouvée.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Spécifie la page sur laquelle la signature a été trouvée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Identifiant unique de la signature pour modifier la signature dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel des méthodes Sign ou Search. Si cette propriété a été enregistrée auparavant, elle peut être définie manuellement pour manipuler la signature.

**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Obtenir ou définir le drapeau indiquant si cet élément est une signature ou le contenu du document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément du document (false).

**Returns:**
booléen
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Obtenir ou définir le drapeau indiquant si cet élément est une signature ou le contenu du document. Cette propriété est utilisée avec la méthode Update pour définir l'élément comme signature (true) ou élément du document (false).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Obtenir ou définir le drapeau indiquant si cette signature a été supprimée du document. Cette propriété est utilisée uniquement pour les enregistrements du journal d'historique du document afin de conserver la liste des signatures supprimées.

**Returns:**
booléen
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Obtenir ou définir la date de création de la signature.

**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Obtenir ou définir la date de création de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Obtenir ou définir la date de modification de la signature.

**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Obtenir ou définir la date de modification de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Spécifie la position supérieure de la signature.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Spécifie la position supérieure de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Spécifie la position gauche de la signature.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Spécifie la position gauche de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Spécifie la largeur de la signature.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Spécifie la largeur de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Spécifie la hauteur de la signature.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Spécifie la hauteur de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Écrase la méthode Equals pour comparer les propriétés de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Objet de signature à comparer. |

**Returns:**
boolean - Retourne true si l'objet signature passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode

**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
booléen
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
