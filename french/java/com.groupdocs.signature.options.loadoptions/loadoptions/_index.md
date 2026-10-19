---
title: "LoadOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Permet de spécifier des options supplémentaires comme le mot de passe lors de l'ouverture d'un document à signer."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Permet de spécifier des options supplémentaires (comme le mot de passe) lors de l'ouverture d'un document à signer.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialise une nouvelle instance de la classe LoadOptions. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Obtient ou définit le mot de passe pour ouvrir un document protégé. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtient ou définit le mot de passe pour ouvrir un document protégé. |
|
|  | [getLoadExternalResources()](#getLoadExternalResources--) | Obtient ou définit les options qui spécifient si les ressources externes du document doivent être chargées. |
|
|  | [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Obtient ou définit les options qui spécifient si les ressources externes du document doivent être chargées. |
|
|  | [getPermissions()](#getPermissions--) | Les permissions du document PDF telles que l'impression, la modification et l'extraction de données. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Définisseur interne, utilisé par les processeurs de chargement de documents pour enregistrer les autorisations extraites du fichier. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialise une nouvelle instance de la classe LoadOptions.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient ou définit le mot de passe pour ouvrir un document protégé.
Il sera également utilisé pour enregistrer le document signé en tant que protégé.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtient ou définit le mot de passe pour ouvrir un document protégé.
Il sera également utilisé pour enregistrer le document signé en tant que protégé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Obtient ou définit les options qui spécifient si les ressources externes du document doivent être chargées.
Cette option avec la valeur désactivée (false) permet de gagner du temps de chargement pour les documents contenant de nombreux liens ou des liens vers des ressources externes volumineuses.
Par défaut, la valeur est activée (true).


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Obtient ou définit les options qui spécifient si les ressources externes du document doivent être chargées.
Cette option avec la valeur désactivée (false) permet de gagner du temps de chargement pour les documents contenant de nombreux liens ou des liens vers des ressources externes volumineuses.
Par défaut, la valeur est activée (true).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Les permissions du document PDF telles que l'impression, la modification et l'extraction de données.
Uniquement pour les documents PDF. Lecture seule \\u2014 remplie automatiquement lors du chargement du document.
La valeur est une combinaison de drapeaux provenant de [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Définisseur interne, utilisé par les processeurs de chargement de documents pour enregistrer les autorisations extraites du fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

