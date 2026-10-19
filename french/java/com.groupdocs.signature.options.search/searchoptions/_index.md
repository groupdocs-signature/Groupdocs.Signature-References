---
title: "SearchOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options d'extraction des signatures du document."
type: docs
weight: 17
url: /fr/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Représente les options d'extraction des signatures du document.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Obtient ou définit le numéro de page du Document pour la recherche. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Obtient ou définit le numéro de page du Document pour la recherche. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Options pour spécifier les pages pour la recherche de Signature. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Options pour spécifier les pages pour la recherche de Signature. |
|
|  | [getAllPages()](#getAllPages--) | Indicateur pour rechercher sur chaque page du Document. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Indicateur pour rechercher sur chaque page du Document. |
|
|  | [getSkipExternal()](#getSkipExternal--) | Indicateur pour ne retourner que les signatures marquées comme IsSignature. |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Indicateur pour ne retourner que les signatures marquées comme IsSignature. |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | Méthode virtuelle pour obtenir la liste des pages pour l'extraction de Signature. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Obtient ou définit le numéro de page du Document pour la recherche.
La valeur est facultative.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Obtient ou définit le numéro de page du Document pour la recherche.
La valeur est facultative.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Options pour spécifier les pages pour la recherche de Signature.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Options pour spécifier les pages pour la recherche de Signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Indicateur pour rechercher sur chaque page du Document. Par défaut, cette valeur est définie sur true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Indicateur pour rechercher sur chaque page du Document. Par défaut, cette valeur est définie sur true.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Indicateur pour ne retourner que les signatures marquées comme IsSignature. Par défaut, la valeur est false, ce qui indique de retourner toutes les signatures correspondant aux critères spécifiés.


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Indicateur pour ne retourner que les signatures marquées comme IsSignature. Par défaut, la valeur est false, ce qui indique de retourner toutes les signatures correspondant aux critères spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Méthode virtuelle pour obtenir la liste des pages pour l'extraction de Signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | totalPages | int | Nombre total de pages |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Liste des numéros de page

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.


**Returns:**
java.lang.String -
