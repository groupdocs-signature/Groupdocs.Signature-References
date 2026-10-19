---
title: "SaveOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Permet de spécifier des options supplémentaires telles que le mot de passe lors de l'enregistrement d'un document à signer."
type: docs
weight: 13
url: /fr/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Permet de spécifier des options supplémentaires (comme le mot de passe) lors de l'enregistrement d'un document à signer.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Initialise une nouvelle instance de la classe SaveOptions avec des valeurs par défaut. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Initialise une nouvelle instance de la classe SaveOptions avec le type de sortie spécifié et le drapeau de remplacement. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Obtient ou définit si le fichier existant doit être remplacé par le nouveau fichier de sortie. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Obtient ou définit si le fichier existant doit être remplacé par le nouveau fichier de sortie. |
|
|  | [getPassword()](#getPassword--) | Obtient ou définit le mot de passe pour enregistrer le document signé avec protection par mot de passe. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtient ou définit le mot de passe pour enregistrer le document signé avec protection par mot de passe. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | Obtient ou définit si le mot de passe provenant de LoadOptions doit être utilisé pour enregistrer le document signé en tant que protégé. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Obtient ou définit si le mot de passe provenant de LoadOptions doit être utilisé pour enregistrer le document signé en tant que protégé. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Obtient ou définit le drapeau pour ajouter automatiquement l'extension lorsqu'elle était manquante dans le chemin du fichier de sortie. |
La valeur par défaut est false.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Obtient ou définit le drapeau pour ajouter automatiquement l'extension lorsqu'elle était manquante dans le chemin du fichier de sortie. |
La valeur par défaut est false.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initialise une nouvelle instance de la classe SaveOptions avec des valeurs par défaut.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe SaveOptions avec le type de sortie spécifié et le drapeau de remplacement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Drapeau indiquant s'il faut remplacer le fichier signé par le même fichier. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Obtient ou définit si le fichier existant doit être remplacé par le nouveau fichier de sortie.
Sinon, un nouveau fichier sera créé avec un numéro en suffixe.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Obtient ou définit si le fichier existant doit être remplacé par le nouveau fichier de sortie.
Sinon, un nouveau fichier sera créé avec un numéro en suffixe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient ou définit le mot de passe pour enregistrer le document signé avec protection par mot de passe.
Cette propriété n'est pas prise en charge pour les documents Image.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtient ou définit le mot de passe pour enregistrer le document signé avec protection par mot de passe.
Cette propriété n'est pas prise en charge pour les documents Image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Obtient ou définit si le mot de passe provenant de LoadOptions doit être utilisé pour enregistrer le document signé en tant que protégé.
La valeur par défaut est true.
Cette propriété n'est pas prise en charge pour les documents Image.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Obtient ou définit si le mot de passe provenant de LoadOptions doit être utilisé pour enregistrer le document signé en tant que protégé.
La valeur par défaut est true.
Cette propriété n'est pas prise en charge pour les documents Image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Obtient ou définit le drapeau pour ajouter automatiquement l'extension lorsqu'elle était manquante dans le chemin du fichier de sortie.
La valeur par défaut est false.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Obtient ou définit le drapeau pour ajouter automatiquement l'extension lorsqu'elle était manquante dans le chemin du fichier de sortie.
La valeur par défaut est false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

