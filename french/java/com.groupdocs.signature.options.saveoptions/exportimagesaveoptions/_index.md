---
title: "ExportImageSaveOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Options d'enregistrement pour l'exportation de documents en image."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Options d'enregistrement pour l'exportation de documents en image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Initialise une nouvelle instance de la classe ExportAsImageSaveOptions avec les valeurs par défaut. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Initialise une nouvelle instance de la classe ExportAsImageSaveOptions avec le format de fichier spécifié. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Obtient ou définit le numéro de page du document pour l'exportation. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Obtient ou définit le numéro de page du document pour l'exportation. |
|
|  | [getExportAllPages()](#getExportAllPages--) | Drapeau pour exporter chaque page. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Drapeau pour exporter chaque page. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Options pour spécifier les pages à signer. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Options pour spécifier les pages à signer. |
|
|  | [getPageColumns()](#getPageColumns--) | Obtient ou définit le nombre de colonnes pour les images exportées. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | Obtient ou définit le nombre de colonnes pour les images exportées. |
|
|  | [getBorder()](#getBorder--) | Obtient ou définit les paramètres de bordure de l'image. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Obtient ou définit les paramètres de bordure de l'image. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Place les pages du document sur des cadres différents dans l'image Tiff. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Place les pages du document sur des cadres différents dans l'image Tiff. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Initialise une nouvelle instance de la classe ExportAsImageSaveOptions avec les valeurs par défaut.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Initialise une nouvelle instance de la classe ExportAsImageSaveOptions avec le format de fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileFormat | int | Format de fichier image de sortie. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Obtient ou définit le numéro de page du document pour l'exportation.
La valeur minimale est 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Obtient ou définit le numéro de page du document pour l'exportation.
La valeur minimale est 1.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Drapeau pour exporter chaque page.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Drapeau pour exporter chaque page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Options pour spécifier les pages à signer.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Options pour spécifier les pages à signer.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Obtient ou définit le nombre de colonnes pour les images exportées.
Utilisez cette propriété si vous devez placer les images en ligne.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Obtient ou définit le nombre de colonnes pour les images exportées.
Utilisez cette propriété si vous devez placer les images en ligne.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Obtient ou définit les paramètres de bordure de l'image. Par défaut, cette valeur n'est pas définie.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Obtient ou définit les paramètres de bordure de l'image. Par défaut, cette valeur n'est pas définie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Place les pages du document sur des cadres différents dans l'image Tiff.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Place les pages du document sur des cadres différents dans l'image Tiff.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.


**Returns:**
java.lang.String -
