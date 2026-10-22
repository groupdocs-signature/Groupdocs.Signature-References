---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Options d'enregistrement pour les documents PDF."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Options d'enregistrement pour les documents PDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Initialise une nouvelle instance de la classe PdfSaveOptions avec les valeurs par défaut. |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Initialise une nouvelle instance de la classe PdfSaveOptions avec le format de fichier de sortie spécifié. |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Initialise une nouvelle instance de la classe PdfSaveOptions avec le drapeau d'écrasement. |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Initialise une nouvelle instance de la classe PdfSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Obtient ou définit le format de fichier du document signé. |
| [setFileFormat(int value)](#setFileFormat-int-) | Obtient ou définit le format de fichier du document signé. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Initialise une nouvelle instance de la classe PdfSaveOptions avec les valeurs par défaut.

### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Initialise une nouvelle instance de la classe PdfSaveOptions avec le format de fichier de sortie spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileFormat | int | Type de fichier de sortie [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe PdfSaveOptions avec le drapeau d'écrasement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| overwriteExistingFile | booléen | Indique s'il faut écraser le fichier signé avec le même fichier. |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe PdfSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileFormat | int | Type de fichier de sortie [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
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
