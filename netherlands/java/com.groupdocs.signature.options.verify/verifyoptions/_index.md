---
title: "VerifyOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat opties om een document te verifiëren."
type: docs
weight: 15
url: /nl/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Bevat opties om een document te verifiëren.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid()](#isValid--) | Geldige eigenschapsvlag. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Geldige eigenschapsvlag. |
|
|  | [getPageNumber()](#getPageNumber--) | Paginanummer van het document dat moet worden geverifieerd. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Paginanummer van het document dat moet worden geverifieerd. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Pagina-opties om de te verifiëren pagina's op te geven. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Pagina-opties om de te verifiëren pagina's op te geven. |
|
|  | [getAllPages()](#getAllPages--) | Vlag om elke documentpagina te verifiëren. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Vlag om elke documentpagina te verifiëren. |
|
|  | [getExtensions()](#getExtensions--) | Aanvullende extensies voor verificatie van alternatieve handtekeningopties. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Aanvullende extensies voor verificatie van alternatieve handtekeningopties. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


Geldige eigenschapsvlag.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Geldige eigenschapsvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Paginanummer van het document dat moet worden geverifieerd. Als de eigenschap niet is ingesteld - alle pagina's van
Document wordt geverifieerd voor de eerste gebeurtenis.
Minimale waarde is 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Paginanummer van het document dat moet worden geverifieerd. Als de eigenschap niet is ingesteld - alle pagina's van
Document wordt geverifieerd voor de eerste gebeurtenis.
Minimale waarde is 1.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Pagina-opties om de te verifiëren pagina's op te geven.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Pagina-opties om de te verifiëren pagina's op te geven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Vlag om elke documentpagina te verifiëren. Standaardwaarde is true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Vlag om elke documentpagina te verifiëren. Standaardwaarde is true.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Aanvullende extensies voor verificatie van alternatieve handtekeningopties.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Aanvullende extensies voor verificatie van alternatieve handtekeningopties.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
