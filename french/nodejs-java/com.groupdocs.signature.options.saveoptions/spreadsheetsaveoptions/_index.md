---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Options d'enregistrement pour les documents de feuille de calcul."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Options d'enregistrement pour les documents de feuille de calcul.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Initialise une nouvelle instance de la classe SpreadsheetSaveOptions avec les valeurs par défaut. |
| [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Initialise une nouvelle instance de la classe SpreadsheetSaveOptions avec le format de fichier de sortie prédéfini. |
| [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Initialise une nouvelle instance de la classe SpreadsheetSaveOptions avec le type de sortie spécifié et le drapeau d'écrasement. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Obtient ou définit le format de fichier du document signé. |
| [setFileFormat(int value)](#setFileFormat-int-) | Obtient ou définit le format de fichier du document signé. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Initialise une nouvelle instance de la classe SpreadsheetSaveOptions avec les valeurs par défaut.

### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Initialise une nouvelle instance de la classe SpreadsheetSaveOptions avec le format de fichier de sortie prédéfini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileFormat | int | Spécifie le format de fichier de sortie. |

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe SpreadsheetSaveOptions avec le type de sortie spécifié et le drapeau d'écrasement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileFormat | int | Spécifie le format de fichier de sortie. |
| overwriteExistingFile | booléen | Indique s'il faut écraser le fichier signé avec le même fichier. |

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
