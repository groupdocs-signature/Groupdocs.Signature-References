---
title: "CertificateSearchOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de recherche pour les signatures de métadonnées de certificat."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

Représente les options de recherche pour les signatures de métadonnées de certificat.

--------------------

 **Learn more** 

 *  
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CertificateSearchOptions()](#CertificateSearchOptions--) | Initialise une nouvelle instance de la classe TextSearchOptions avec les valeurs par défaut. |
| [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | Initialise une nouvelle instance de la classe TextSearchOptions avec une valeur texte. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Spécifie le texte de la propriété du certificat à faire correspondre lors de la recherche. |
| [setText(String value)](#setText-java.lang.String-) | Spécifie le texte de la propriété du certificat à faire correspondre lors de la recherche. |
| [getMatchType()](#getMatchType--) | Obtient ou définit le type de correspondance du texte pour la recherche. |
| [setMatchType(int value)](#setMatchType-int-) | Obtient ou définit le type de correspondance du texte pour la recherche. |
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


Initialise une nouvelle instance de la classe TextSearchOptions avec les valeurs par défaut.

### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
```


Initialise une nouvelle instance de la classe TextSearchOptions avec une valeur texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Définir le texte de la signature texte. |

### getText() {#getText--}
```
public final String getText()
```


Spécifie le texte de la propriété du certificat à faire correspondre lors de la recherche.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Spécifie le texte de la propriété du certificat à faire correspondre lors de la recherche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtient ou définit le type de correspondance du texte pour la recherche.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtient ou définit le type de correspondance du texte pour la recherche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

