---
title: "MetadataSignOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de signature Metadata."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Représente les options de signature Metadata.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MetadataSignOptions()](#MetadataSignOptions--) | Initialise une nouvelle instance de la classe SignMetadataOptions avec les valeurs par défaut. |
| [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Initialise une nouvelle instance de la classe SignMetadataOptions avec les métadonnées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSignatures()](#getSignatures--) | Obtient ou définit les métadonnées de la signature. |
| [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | Obtient ou définit les métadonnées de la signature. |
| [getDataEncryption()](#getDataEncryption--) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés Texte ou Données de la signature QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés Texte ou Données de la signature QR-Code. |
| [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Crée une nouvelle PdfMetadataSignature avec les arguments fournis et l'ajoute à la collection. |
| [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Crée une nouvelle ImageMetadataSignature avec les arguments fournis et l'ajoute à la collection. |
| [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Ajoute une instance existante de MetadataSignature à la collection. |
| [validate()](#validate--) | Méthode interne pour valider les paramètres des options. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


Initialise une nouvelle instance de la classe SignMetadataOptions avec les valeurs par défaut.

### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Initialise une nouvelle instance de la classe SignMetadataOptions avec les métadonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Collection de signatures de métadonnées [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


Obtient ou définit les métadonnées de la signature.

**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


Obtient ou définit les métadonnées de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés Texte ou Données de la signature QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés Texte ou Données de la signature QR-Code.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Crée une nouvelle PdfMetadataSignature avec les arguments fournis et l'ajoute à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de l'objet de signature de métadonnées |
| valeur | java.lang.Object | Valeur de la signature de métadonnées |
| étiquette | java.lang.String | Étiquette préfixe de la signature de métadonnées |

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Crée une nouvelle ImageMetadataSignature avec les arguments fournis et l'ajoute à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | int | Identifiant unique du nom de la signature d'image de métadonnées. Voir les références pour les spécifications des balises Exif afin d'obtenir les valeurs d'identifiant possibles. |
| valeur | java.lang.Object | Valeur des métadonnées |

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Ajoute une instance existante de MetadataSignature à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | L'instance existante de MetadataSignature à ajouter |

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself
### validate() {#validate--}
```
public void validate()
```


Méthode interne pour valider les paramètres des options.

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.

**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
