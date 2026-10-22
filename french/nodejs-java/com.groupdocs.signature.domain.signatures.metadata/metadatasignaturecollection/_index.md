---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Collection d'objets de signature de métadonnées."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Collection d'objets de signature de métadonnées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Crée une collection de signatures de métadonnées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient le nombre d'éléments dans la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [contains(String name)](#contains-java.lang.String-) | Renvoie vrai si une métadonnée avec le nom spécifié existe dans la collection. |
| [indexOf(String name)](#indexOf-java.lang.String-) | Obtient l'index d'une propriété par son nom. |
| [remove(String name)](#remove-java.lang.String-) | Supprime une signature de métadonnées avec le nom spécifié de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime une signature de métadonnées à l'index spécifié. |
| [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Ajoute un objet de signature de métadonnées à la collection. |
| [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Ajoute une collection de signatures de métadonnées. |
| [deepClone()](#deepClone--) | Clone la classe Collection de signatures de métadonnées avec les éléments de signature de métadonnées. |
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Crée une collection de signatures de métadonnées.

### getCount() {#getCount--}
```
public final int getCount()
```


Obtient le nombre d'éléments dans la collection.

**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Supprime tous les éléments de la collection.

### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Renvoie vrai si une métadonnée avec le nom spécifié existe dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de la propriété, insensible à la casse. |

**Returns:**
booléen - Vrai si la métadonnée existe dans la collection ; faux sinon.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Obtient l'index d'une propriété par son nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de la signature de métadonnées, insensible à la casse. |

**Returns:**
int - L'index basé sur zéro. Valeur négative si non trouvé.
### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Supprime une signature de métadonnées avec le nom spécifié de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de la signature de métadonnées, insensible à la casse. |

**Returns:**
booléen -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Supprime une signature de métadonnées à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro. |

**Returns:**
booléen
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Ajoute un objet de signature de métadonnées à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Signature de métadonnées à ajouter à la collection. |

--------------------

Lance une exception si la valeur du nom n'est pas unique dans l'ensemble de la collection existante |

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Ajoute une collection de signatures de métadonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Collection de signatures à ajouter. |

--------------------

Lance une exception si la valeur du nom n'est pas unique dans l'ensemble de la collection existante |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clone la classe Collection de signatures de métadonnées avec les éléments de signature de métadonnées.

**Returns:**
java.lang.Object - Retourne une instance copiée avec les éléments de signature clonés
