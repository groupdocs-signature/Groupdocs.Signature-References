---
title: "SearchOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Geeft weer de opties voor het extraheren van handtekeningen uit een document."
type: docs
weight: 17
url: /nl/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Geeft weer de opties voor het extraheren van handtekeningen uit een document.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Haalt op of stelt het paginanummer van het document in voor zoeken. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Haalt op of stelt het paginanummer van het document in voor zoeken. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opties om pagina's op te geven voor het zoeken naar handtekeningen. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opties om pagina's op te geven voor het zoeken naar handtekeningen. |
|
|  | [getAllPages()](#getAllPages--) | Vlag om op elke Document-pagina te zoeken. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Vlag om op elke Document-pagina te zoeken. |
|
|  | [getSkipExternal()](#getSkipExternal--) | Vlag om alleen handtekeningen die gemarkeerd zijn als IsSignature terug te geven. |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Vlag om alleen handtekeningen die gemarkeerd zijn als IsSignature terug te geven. |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | Virtuele methode om een lijst met pagina's voor handtekeningextractie op te halen. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Haalt op of stelt het paginanummer van het document in voor zoeken.
Waarde is optioneel.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Haalt op of stelt het paginanummer van het document in voor zoeken.
Waarde is optioneel.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Opties om pagina's op te geven voor het zoeken naar handtekeningen.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Opties om pagina's op te geven voor het zoeken naar handtekeningen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Vlag om op elke Document-pagina te zoeken. Standaard is deze waarde ingesteld op true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Vlag om op elke Document-pagina te zoeken. Standaard is deze waarde ingesteld op true.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Vlag om alleen handtekeningen die gemarkeerd zijn als IsSignature terug te geven. Standaard is de waarde false, wat aangeeft dat alle handtekeningen die aan de opgegeven criteria voldoen worden teruggegeven.


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Vlag om alleen handtekeningen die gemarkeerd zijn als IsSignature terug te geven. Standaard is de waarde false, wat aangeeft dat alle handtekeningen die aan de opgegeven criteria voldoen worden teruggegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Virtuele methode om een lijst met pagina's voor handtekeningextractie op te halen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | totalPages | int | Totaal aantal pagina's |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Lijst met paginanummers

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
