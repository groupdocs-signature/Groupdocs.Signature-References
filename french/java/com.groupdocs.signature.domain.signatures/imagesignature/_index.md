---
title: "ImageSignature"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Contient les propriétés de la signature d'image."
type: docs
weight: 14
url: /fr/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Contient les propriétés de la signature d'image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Initialisez l'objet ImageSignature avec l'identifiant de signature qui a été obtenu après le processus de recherche. |
|
|  | [ImageSignature()](#ImageSignature--) | Initialisez ImageSignature avec les paramètres par défaut. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSize()](#getSize--) | Spécifie la taille en octets de l'image de signature. |
|
|  | [setSize(int value)](#setSize-int-) | Spécifie la taille en octets de l'image de signature. |
|
|  | [getFormat()](#getFormat--) | Spécifie le format de l'image de signature. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Spécifie le format de l'image de signature. |
|
|  | [getContent()](#getContent--) | Spécifie le contenu des données binaires de l'image de type |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Remplace la méthode Equals pour comparer les propriétés de la signature |
|
|  | [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Cloner l’instance de signature de code-barres. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Initialisez l'objet ImageSignature avec l'identifiant de signature qui a été obtenu après le processus de recherche.
Cet identifiant unique est utilisé pour trouver des propriétés supplémentaires pour cette signature à partir de la couche d'informations de signature du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signatureId | java.lang.String | Identifiant de signature unique obtenu par la méthode Sign ou Search de la classe Signature [Signature](../../com.groupdocs.signature/signature). |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Initialisez ImageSignature avec les paramètres par défaut.


### getSize() {#getSize--}
```
public final int getSize()
```


Spécifie la taille en octets de l'image de signature.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Spécifie la taille en octets de l'image de signature.



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Spécifie le format de l'image de signature.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Spécifie le format de l'image de signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Spécifie le contenu des données binaires de l'image de type
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Par défaut, cette propriété ne sera pas définie.
Utilisez la propriété
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) pour activer cette fonctionnalité.


**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Remplace la méthode Equals pour comparer les propriétés de la signature


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signature | java.lang.Object | Objet de signature à comparer. |
|

**Returns:**
boolean - Retourne true si l'objet signature passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode


**Returns:**
int - Code de hachage de la signature

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Cloner l’instance de signature de code-barres.


**Returns:**
java.lang.Object - Retourne une instance de Signature Barcode clonée.

