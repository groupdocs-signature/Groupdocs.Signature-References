---
title: "SearchOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar alternativ för att extrahera signaturer från dokument."
type: docs
weight: 17
url: /sv/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Representerar alternativ för att extrahera signaturer från dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Hämtar eller anger Document sidnummer för sökning. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Hämtar eller anger Document sidnummer för sökning. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Alternativ för att ange sidor för Signature-sökning. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Alternativ för att ange sidor för Signature-sökning. |
|
|  | [getAllPages()](#getAllPages--) | Flagga för att söka på varje Document-sida. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Flagga för att söka på varje Document-sida. |
|
|  | [getSkipExternal()](#getSkipExternal--) | Flagga för att endast returnera signaturer markerade som IsSignature. |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Flagga för att endast returnera signaturer markerade som IsSignature. |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | Virtuell metod för att hämta lista över sidor för Signature-extraktion. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Hämtar eller anger Document sidnummer för sökning.
Värdet är valfritt.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Hämtar eller anger Document sidnummer för sökning.
Värdet är valfritt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Alternativ för att ange sidor för Signature-sökning.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Alternativ för att ange sidor för Signature-sökning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Flagga för att söka på varje Document-sida. Som standard är detta värde satt till true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Flagga för att söka på varje Document-sida. Som standard är detta värde satt till true.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Flagga för att endast returnera signaturer markerade som IsSignature. Som standard är värdet false, vilket indikerar att alla signaturer som matchar angivna kriterier ska returneras.


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Flagga för att endast returnera signaturer markerade som IsSignature. Som standard är värdet false, vilket indikerar att alla signaturer som matchar angivna kriterier ska returneras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Virtuell metod för att hämta lista över sidor för Signature-extraktion.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | totalPages | int | Totalt antal sidor |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Lista över sidnummer

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
