---
title: "SearchOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die Optionen zum Extrahieren von Signaturen aus dem Dokument dar."
type: docs
weight: 17
url: /de/nodejs-java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Stellt die Optionen zum Extrahieren von Signaturen aus dem Dokument dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Liest oder setzt die Dokumentenseitenzahl für die Suche. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Liest oder setzt die Dokumentenseitenzahl für die Suche. |
| [getPagesSetup()](#getPagesSetup--) | Optionen zum Festlegen von Seiten für die Signatursuche. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Optionen zum Festlegen von Seiten für die Signatursuche. |
| [getAllPages()](#getAllPages--) | Flag zum Durchsuchen jeder Dokumentenseite. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Flag zum Durchsuchen jeder Dokumentenseite. |
| [getSkipExternal()](#getSkipExternal--) | Flag zum Zurückgeben nur von Signaturen, die als IsSignature markiert sind. |
| [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Flag zum Zurückgeben nur von Signaturen, die als IsSignature markiert sind. |
| [getSearchPages(int totalPages)](#getSearchPages-int-) | Virtuelle Methode zum Abrufen einer Liste von Seiten für die Signaturextraktion. |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Liest oder setzt die Dokumentenseitenzahl für die Suche. Der Wert ist optional.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Liest oder setzt die Dokumentenseitenzahl für die Suche. Der Wert ist optional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Optionen zum Festlegen von Seiten für die Signatursuche.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Optionen zum Festlegen von Seiten für die Signatursuche.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Flag zum Durchsuchen jeder Dokumentenseite. Standardmäßig ist dieser Wert auf true gesetzt.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Flag zum Durchsuchen jeder Dokumentenseite. Standardmäßig ist dieser Wert auf true gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Flag zum Zurückgeben nur von Signaturen, die als IsSignature markiert sind. Standardmäßig ist der Wert false, was bedeutet, dass alle Signaturen zurückgegeben werden, die den angegebenen Kriterien entsprechen.

**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Flag zum Zurückgeben nur von Signaturen, die als IsSignature markiert sind. Standardmäßig ist der Wert false, was bedeutet, dass alle Signaturen zurückgegeben werden, die den angegebenen Kriterien entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Virtuelle Methode zum Abrufen einer Liste von Seiten für die Signaturextraktion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| totalPages | int | Gesamtzahl der Seiten |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Liste von Seitenzahlen
### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.

**Returns:**
java.lang.String -
