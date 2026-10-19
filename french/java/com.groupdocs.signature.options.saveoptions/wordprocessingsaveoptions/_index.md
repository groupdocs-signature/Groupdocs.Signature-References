---
title: "WordProcessingSaveOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Options d'enregistrement pour les documents de traitement de texte."
type: docs
weight: 15
url: /fr/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Options d'enregistrement pour les documents de traitement de texte.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec les valeurs par défaut. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le format de fichier de sortie spécifié. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le type de sortie spécifié et le drapeau d'écrasement. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Obtient ou définit le format de fichier du document signé. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Obtient ou définit le format de fichier du document signé. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec les valeurs par défaut.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le format de fichier de sortie spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileFormat | int | Type de fichier de sortie [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le type de sortie spécifié et le drapeau d'écrasement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Drapeau indiquant s'il faut remplacer le fichier signé par le même fichier. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileFormat | int | Type de fichier de sortie [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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


Remplace la conversion de chaîne


**Returns:**
java.lang.String -
