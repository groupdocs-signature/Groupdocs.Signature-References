---
title: "ImageSearchOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options de recherche pour les signatures d'image."
type: docs
weight: 14
url: /fr/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Représente les options de recherche pour les signatures d'image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | Initialise une nouvelle instance de la classe ImageSearchOptions avec les valeurs par défaut. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | Obtient ou définit le drapeau pour récupérer le contenu image de la signature sur la page du document. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtient ou définit le drapeau pour récupérer le contenu image de la signature sur la page du document. |
|
|  | [getMinContentSize()](#getMinContentSize--) | Pour une valeur non nulle, ce drapeau spécifie la taille minimale des images pour les critères de recherche. |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | Pour une valeur non nulle, ce drapeau spécifie la taille minimale des images pour les critères de recherche. |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | Pour une valeur non nulle, ce drapeau spécifie la taille maximale des images pour les critères de recherche. |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | Pour une valeur non nulle, ce drapeau spécifie la taille maximale des images pour les critères de recherche. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Spécifie le type de fichier du contenu retourné de la signature image lorsque la propriété ReturnContent est activée. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Spécifie le type de fichier du contenu retourné de la signature image lorsque la propriété ReturnContent est activée. |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Initialise une nouvelle instance de la classe ImageSearchOptions avec les valeurs par défaut.


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtient ou définit le drapeau pour récupérer le contenu image de la signature sur la page du document.
Si ce drapeau est défini à vrai, le contenu de la signature image conservera les données brutes de l'image dans le format requis.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Par défaut, cette option est désactivée.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtient ou définit le drapeau pour récupérer le contenu image de la signature sur la page du document.
Si ce drapeau est défini à vrai, le contenu de la signature image conservera les données brutes de l'image dans le format requis.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Par défaut, cette option est désactivée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Pour une valeur non nulle, ce drapeau spécifie la taille minimale des images pour les critères de recherche.
Par défaut, ce drapeau est réglé à zéro et n'affecte pas le résultat de la recherche.


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Pour une valeur non nulle, ce drapeau spécifie la taille minimale des images pour les critères de recherche.
Par défaut, ce drapeau est réglé à zéro et n'affecte pas le résultat de la recherche.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Pour une valeur non nulle, ce drapeau spécifie la taille maximale des images pour les critères de recherche.
Par défaut, ce drapeau est réglé à zéro et n'affecte pas le résultat de la recherche.


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Pour une valeur non nulle, ce drapeau spécifie la taille maximale des images pour les critères de recherche.
Par défaut, ce drapeau est réglé à zéro et n'affecte pas le résultat de la recherche.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Spécifie le type de fichier du contenu retourné de la signature image lorsque la propriété ReturnContent est activée.
Par défaut, il est réglé sur Null. Cela signifie que le contenu de l'image sera retourné dans son format original.
Ce format d'image est spécifié à
ImageSignature.Format

Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP.
Si le format fourni n'est pas pris en charge, le contenu de l'image sera retourné dans son format original.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Spécifie le type de fichier du contenu retourné de la signature image lorsque la propriété ReturnContent est activée.
Par défaut, il est réglé sur Null. Cela signifie que le contenu de l'image sera retourné dans son format original.
Ce format d'image est spécifié à
ImageSignature.Format

Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP.
Si le format fourni n'est pas pris en charge, le contenu de l'image sera retourné dans son format original.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

