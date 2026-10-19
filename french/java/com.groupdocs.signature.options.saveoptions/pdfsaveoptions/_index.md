---
title: "PdfSaveOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Options d'enregistrement pour les documents PDF."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
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
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Initialise une nouvelle instance de la classe PdfSaveOptions avec les valeurs par défaut. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Initialise une nouvelle instance de la classe PdfSaveOptions avec le format de fichier de sortie spécifié. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Initialise une nouvelle instance de la classe PdfSaveOptions avec le drapeau d'écrasement. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Initialise une nouvelle instance de la classe PdfSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Obtient ou définit le format de fichier du document signé. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Obtient ou définit le format de fichier du document signé. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Un mot de passe de permissions (le mot de passe principal) nécessite un mot de passe pour modifier les paramètres de permission. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Un mot de passe de permissions (le mot de passe principal) nécessite un mot de passe pour modifier les paramètres de permission. |
|
|  | [getPermissions()](#getPermissions--) | Les permissions du document PDF telles que l'impression, la modification et l'extraction de données. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Les permissions du document PDF telles que l'impression, la modification et l'extraction de données. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
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
|  | fileFormat | int | Type de fichier de sortie [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe PdfSaveOptions avec le drapeau d'écrasement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Drapeau indiquant s'il faut remplacer le fichier signé par le même fichier. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialise une nouvelle instance de la classe PdfSaveOptions avec le format de fichier de sortie spécifié et le drapeau d'écrasement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileFormat | int | Type de fichier de sortie [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
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

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Un mot de passe de permissions (le mot de passe principal) nécessite un mot de passe pour modifier les paramètres de permission.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Un mot de passe de permissions (le mot de passe principal) nécessite un mot de passe pour modifier les paramètres de permission.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Les permissions du document PDF telles que l'impression, la modification et l'extraction de données.


Pour modifier ces permissions, le
PermissionsPassword
doit être défini.
La valeur est une combinaison de drapeaux provenant de [Permissions](../../com.groupdocs.signature.options/permissions).
Un
null
valeur signifie qu'aucune permission explicite n'est appliquée.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Les permissions du document PDF telles que l'impression, la modification et l'extraction de données.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.


**Returns:**
java.lang.String -
