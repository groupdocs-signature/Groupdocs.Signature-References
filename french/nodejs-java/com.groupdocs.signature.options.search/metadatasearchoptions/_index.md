---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de recherche abstraites pour les signatures de métadonnées."
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Représente les options de recherche abstraites pour les signatures de métadonnées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MetadataSearchOptions()](#MetadataSearchOptions--) | Initialise une nouvelle instance de la classe SearchMetadataOptions avec les valeurs par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Spécifie le nom de la signature Metadata si elle doit être recherchée et correspondante. |
| [setName(String value)](#setName-java.lang.String-) | Spécifie le nom de la signature Metadata si elle doit être recherchée et correspondante. |
| [getNameMatchType()](#getNameMatchType--) | Obtient ou définit Metadata name Match Type pour la recherche. |
| [setNameMatchType(int value)](#setNameMatchType-int-) | Obtient ou définit Metadata name Match Type pour la recherche. |
| [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Indique si les propriétés intégrées du document comme les statistiques du document, les informations, etc. doivent être incluses dans le résultat de la recherche. |
| [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Indique si les propriétés intégrées du document comme les statistiques du document, les informations, etc. doivent être incluses dans le résultat de la recherche. |
| [getDataEncryption()](#getDataEncryption--) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés Texte ou Données de la signature QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés Texte ou Données de la signature QR-Code. |
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Initialise une nouvelle instance de la classe SearchMetadataOptions avec les valeurs par défaut.

### getName() {#getName--}
```
public final String getName()
```


Spécifie le nom de la signature Metadata si elle doit être recherchée et correspondante.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Spécifie le nom de la signature Metadata si elle doit être recherchée et correspondante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Obtient ou définit Metadata name Match Type pour la recherche. Il n'est utilisé que lorsque la propriété Name est définie.

**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Obtient ou définit Metadata name Match Type pour la recherche. Il n'est utilisé que lorsque la propriété Name est définie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Indique si les propriétés intégrées du document comme les statistiques du document, les informations, etc. doivent être incluses dans le résultat de la recherche. Ce drapeau a du sens pour les types de fichiers de présentation, Spreadhsheet et de traitement de texte.

**Returns:**
booléen
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Indique si les propriétés intégrées du document comme les statistiques du document, les informations, etc. doivent être incluses dans le résultat de la recherche. Ce drapeau a du sens pour les types de fichiers de présentation, Spreadhsheet et de traitement de texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

