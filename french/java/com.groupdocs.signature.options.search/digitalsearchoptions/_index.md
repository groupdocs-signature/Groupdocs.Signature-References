---
title: "DigitalSearchOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options de base pour la recherche de signatures numériques"
type: docs
weight: 12
url: /fr/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Représente les options de base pour la recherche de signatures numériques

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | Initialise une nouvelle instance de la classe DigitalSearchOptions avec les valeurs par défaut. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getComments()](#getComments--) | Commentaires de la signature numérique à rechercher. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Commentaires de la signature numérique à rechercher. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Plage de date et d'heure de la signature numérique à rechercher. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Plage de date et d'heure de la signature numérique à rechercher. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Plage de date et d'heure de la signature numérique à rechercher. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Plage de date et d'heure de la signature numérique à rechercher. |
|
|  | [getSubjectName()](#getSubjectName--) | Pour les valeurs non vides, spécifie le nom distinctif du sujet du certificat à rechercher. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Pour les valeurs non vides, spécifie le nom distinctif du sujet du certificat à rechercher. |
|
|  | [getIssuerName()](#getIssuerName--) | Pour les valeurs non vides, spécifie le nom distinctif de l'émetteur du certificat à rechercher. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Pour les valeurs non vides, spécifie le nom distinctif de l'émetteur du certificat à rechercher. |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Initialise une nouvelle instance de la classe DigitalSearchOptions avec les valeurs par défaut.


### getComments() {#getComments--}
```
public final String getComments()
```


Commentaires de la signature numérique à rechercher.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Commentaires de la signature numérique à rechercher.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Plage de date et d'heure de la signature numérique à rechercher. Les valeurs nulles seront ignorées.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Plage de date et d'heure de la signature numérique à rechercher. Les valeurs nulles seront ignorées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Plage de date et d'heure de la signature numérique à rechercher. Les valeurs nulles seront ignorées.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Plage de date et d'heure de la signature numérique à rechercher. Les valeurs nulles seront ignorées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Pour les valeurs non vides, spécifie le nom distinctif du sujet du certificat à rechercher.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Pour les valeurs non vides, spécifie le nom distinctif du sujet du certificat à rechercher.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Pour les valeurs non vides, spécifie le nom distinctif de l'émetteur du certificat à rechercher.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Pour les valeurs non vides, spécifie le nom distinctif de l'émetteur du certificat à rechercher.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

