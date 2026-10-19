---
title: "PresentationSaveOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Options d'enregistrement pour les documents de présentation."
type: docs
weight: 12
url: /fr/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Options d'enregistrement pour les documents de présentation.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Initialise une nouvelle instance de la classe PresentationSaveOptions avec les valeurs par défaut. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Initialise une nouvelle instance de la classe PresentationSaveOptions avec le format de fichier de sortie spécifié. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Initialise une nouvelle instance de la classe PresentationSaveOptions avec le type de sortie spécifié et le drapeau d'écrasement. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Initialise une nouvelle instance de la classe PresentationSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Obtient ou définit le format de fichier du document signé. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Obtient ou définit le format de fichier du document signé. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Initialise une nouvelle instance de la classe PresentationSaveOptions avec les valeurs par défaut.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Initialise une nouvelle instance de la classe PresentationSaveOptions avec le format de fichier de sortie spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileFormat | int | Type de fichier de sortie [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe PresentationSaveOptions avec le type de sortie spécifié et le drapeau d'écrasement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Drapeau indiquant s'il faut remplacer le fichier signé par le même fichier. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe PresentationSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileFormat | int | Type de fichier de sortie [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|
|  | overwriteExistingFile | boolean | Drapeau indiquant s'il faut remplacer le fichier signé par le même fichier. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Obtient ou définit le format de fichier du document signé.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Obtient ou définit le format de fichier du document signé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.


**Returns:**
java.lang.String -
