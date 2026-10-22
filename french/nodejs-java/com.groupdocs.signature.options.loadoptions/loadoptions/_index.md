---
title: "LoadOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Permet de spécifier des options supplémentaires telles que le mot de passe lors de l'ouverture d'un document à signer."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.options.loadoptions/loadoptions/
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
| [LoadOptions()](#LoadOptions--) | Initialise une nouvelle instance de la classe LoadOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Obtient ou définit le mot de passe pour ouvrir un document protégé. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtient ou définit le mot de passe pour ouvrir un document protégé. |
| [getLoadExternalResources()](#getLoadExternalResources--) | Obtient ou définit les options qui spécifient si les ressources externes du document doivent être chargées. |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Obtient ou définit les options qui spécifient si les ressources externes du document doivent être chargées. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialise une nouvelle instance de la classe LoadOptions.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient ou définit le mot de passe pour ouvrir un document protégé. Il sera également utilisé pour enregistrer le document signé en tant que protégé.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtient ou définit le mot de passe pour ouvrir un document protégé. Il sera également utilisé pour enregistrer le document signé en tant que protégé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Obtient ou définit les options qui spécifient si les ressources externes du document doivent être chargées. Cette option avec la valeur désactivée (false) permet de gagner du temps de chargement pour les documents contenant de nombreux ou de gros liens de ressources externes. Par défaut, la valeur est activée (true).

**Returns:**
booléen
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Obtient ou définit les options qui spécifient si les ressources externes du document doivent être chargées. Cette option avec la valeur désactivée (false) permet de gagner du temps de chargement pour les documents contenant de nombreux ou de gros liens de ressources externes. Par défaut, la valeur est activée (true).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

