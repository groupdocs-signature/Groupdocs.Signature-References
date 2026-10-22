---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de signature des métadonnées PDF."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Contient les propriétés de signature des métadonnées PDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Crée une signature Pdf Metadata avec un nom prédéfini et une valeur vide |
| [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Crée une signature Pdf Metadata avec des valeurs prédéfinies |
| [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Crée une signature Pdf Metadata avec des valeurs prédéfinies |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTagPrefix()](#getTagPrefix--) | Le préfixe du tag du nom de la signature Pdf Metadata. |
| [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Le préfixe du tag du nom de la signature Pdf Metadata. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Clone l'instance de Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clone l'instance de Pdf Metadata Signature avec la valeur donnée. |
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Crée une signature Pdf Metadata avec un nom prédéfini et une valeur vide

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de la signature Pdf Metadata |

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Crée une signature Pdf Metadata avec des valeurs prédéfinies

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de l'objet de signature de métadonnées |
| valeur | java.lang.Object | Valeur de la signature de métadonnées |

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Crée une signature Pdf Metadata avec des valeurs prédéfinies

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de l'objet de signature de métadonnées |
| valeur | java.lang.Object | Valeur de la signature de métadonnées |
| étiquette | java.lang.String | Étiquette préfixe de la signature de métadonnées |

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Le préfixe du tag du nom de la signature Pdf Metadata. Par défaut, cette propriété est définie sur "xmp". Les valeurs possibles sont

**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Le préfixe du tag du nom de la signature Pdf Metadata. Par défaut, cette propriété est définie sur "xmp". Les valeurs possibles sont

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Écrase la méthode Equals pour comparer les propriétés de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Objet de signature à comparer. |

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


Clone l'instance de Metadata Signature.

**Returns:**
java.lang.Object - Renvoie l'instance clonée de Metadata Signature
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clone l'instance de Pdf Metadata Signature avec la valeur donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | Valeur pour le nouvel objet cloné. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
