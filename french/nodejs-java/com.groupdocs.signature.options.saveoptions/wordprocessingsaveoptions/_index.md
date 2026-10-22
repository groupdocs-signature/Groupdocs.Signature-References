---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Options d'enregistrement pour les documents de traitement de texte."
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
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
| [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec les valeurs par défaut. |
| [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le format de fichier de sortie spécifié. |
| [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le type de sortie spécifié et le drapeau d'écrasement. |
| [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Obtient ou définit le format de fichier du document signé. |
| [setFileFormat(int value)](#setFileFormat-int-) | Obtient ou définit le format de fichier du document signé. |
| [toString()](#toString--) | Remplacer la conversion de chaîne |
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
| fileFormat | int | Type de fichier de sortie [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le type de sortie spécifié et le drapeau d'écrasement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| overwriteExistingFile | booléen | Indique s'il faut écraser le fichier signé avec le même fichier. |

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe WordProcessingSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileFormat | int | Type de fichier de sortie [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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


Remplacer la conversion de chaîne

**Returns:**
java.lang.String -
