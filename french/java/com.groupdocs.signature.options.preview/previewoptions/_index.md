---
title: "PreviewOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options d'aperçu du document."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Représente les options d'aperçu du document.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Initialise l'objet PreviewOptions. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Initialise l'objet PreviewOptions. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Initialise l'objet PreviewOptions. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtient ou définit la largeur des images d'aperçu. |
|
|  | [setWidth(int value)](#setWidth-int-) | Obtient ou définit la largeur des images d'aperçu. |
|
|  | [getHeight()](#getHeight--) | Obtient ou définit la hauteur des images d'aperçu. |
|
|  | [setHeight(int value)](#setHeight-int-) | Obtient ou définit la hauteur des images d'aperçu. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Obtient ou définit les numéros de page des images d'aperçu. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Obtient ou définit les numéros de page des images d'aperçu. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Obtient ou définit le format des images d'aperçu. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Obtient ou définit le format des images d'aperçu. |
|
|  | [getHideSignatures()](#getHideSignatures--) | Obtient ou définit le drapeau pour masquer les signatures de l'image d'aperçu de page. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Obtient ou définit le drapeau pour masquer les signatures de l'image d'aperçu de page. |
|
|  | [getResolution()](#getResolution--) | Obtient la résolution des images d'aperçu en DPI (points par pouce). |
|
|  | [setResolution(int value)](#setResolution-int-) | Définit la résolution des images d'aperçu en DPI (points par pouce). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Initialise l'objet PreviewOptions.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Interface qui définit la méthode pour créer le flux d'aperçu de la page de sortie. |
|
|  | pageNumbers | int[] | Numéros de page souhaités |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Initialise l'objet PreviewOptions.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Interface qui définit la méthode pour créer le flux d'aperçu de la page de sortie. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Initialise l'objet PreviewOptions.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Chemin du fichier de sortie. |
|
|  | pageNumbers | int[] | Numéros de page souhaités |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient ou définit la largeur des images d'aperçu.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Obtient ou définit la largeur des images d'aperçu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient ou définit la hauteur des images d'aperçu.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Obtient ou définit la hauteur des images d'aperçu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtient ou définit les numéros de page des images d'aperçu.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Obtient ou définit les numéros de page des images d'aperçu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Obtient ou définit le format des images d'aperçu.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Obtient ou définit le format des images d'aperçu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Obtient ou définit le drapeau pour masquer les signatures de l'image d'aperçu de page.
Seules les signatures marquées comme IsSignature seront masquées de l'image de page du document généré.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Obtient ou définit le drapeau pour masquer les signatures de l'image d'aperçu de page.
Seules les signatures marquées comme IsSignature seront masquées de l'image de page du document généré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Obtient la résolution des images d'aperçu en DPI (points par pouce).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Définit la résolution des images d'aperçu en DPI (points par pouce).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

