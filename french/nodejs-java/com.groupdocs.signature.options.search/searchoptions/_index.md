---
title: "SearchOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options d'extraction des signatures du document."
type: docs
weight: 17
url: /fr/nodejs-java/com.groupdocs.signature.options.search/searchoptions/
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
| [getPageNumber()](#getPageNumber--) | Obtient ou définit le numéro de page du document pour la recherche. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Obtient ou définit le numéro de page du document pour la recherche. |
| [getPagesSetup()](#getPagesSetup--) | Options pour spécifier les pages pour la recherche de signature. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Options pour spécifier les pages pour la recherche de signature. |
| [getAllPages()](#getAllPages--) | Indicateur pour rechercher sur chaque page du document. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Indicateur pour rechercher sur chaque page du document. |
| [getSkipExternal()](#getSkipExternal--) | Indicateur pour ne retourner que les signatures marquées comme IsSignature. |
| [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Indicateur pour ne retourner que les signatures marquées comme IsSignature. |
| [getSearchPages(int totalPages)](#getSearchPages-int-) | Méthode virtuelle pour obtenir la liste des pages pour l'extraction de signature. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Obtient ou définit le numéro de page du document pour la recherche. La valeur est facultative.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Obtient ou définit le numéro de page du document pour la recherche. La valeur est facultative.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Options pour spécifier les pages pour la recherche de signature.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Options pour spécifier les pages pour la recherche de signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Indicateur pour rechercher sur chaque page du document. Par défaut, cette valeur est définie sur true.

**Returns:**
booléen
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Indicateur pour rechercher sur chaque page du document. Par défaut, cette valeur est définie sur true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Indicateur pour ne retourner que les signatures marquées comme IsSignature. Par défaut, la valeur est false, ce qui indique de retourner toutes les signatures correspondant aux critères spécifiés.

**Returns:**
booléen
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Indicateur pour ne retourner que les signatures marquées comme IsSignature. Par défaut, la valeur est false, ce qui indique de retourner toutes les signatures correspondant aux critères spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Méthode virtuelle pour obtenir la liste des pages pour l'extraction de signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| totalPages | int | Nombre total de pages |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Liste des numéros de page
### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.

**Returns:**
java.lang.String -
