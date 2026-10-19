---
title: "VerifyOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Optionen zum Verifizieren eines Dokuments."
type: docs
weight: 15
url: /de/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Enthält Optionen zum Verifizieren eines Dokuments.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValid()](#isValid--) | Gültiges Eigenschafts-Flag. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Gültiges Eigenschafts-Flag. |
|
|  | [getPageNumber()](#getPageNumber--) | Dokumentseitenzahl, die verifiziert werden soll. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Dokumentseitenzahl, die verifiziert werden soll. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Seitenoptionen, um die zu verifizierenden Seiten anzugeben. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Seitenoptionen, um die zu verifizierenden Seiten anzugeben. |
|
|  | [getAllPages()](#getAllPages--) | Flag, um jede Dokumentseite zu verifizieren. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Flag, um jede Dokumentseite zu verifizieren. |
|
|  | [getExtensions()](#getExtensions--) | Zusätzliche Erweiterungen für die Verifizierung alternativer Signaturoptionen. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Zusätzliche Erweiterungen für die Verifizierung alternativer Signaturoptionen. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


Gültiges Eigenschafts-Flag.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Gültiges Eigenschafts-Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Dokumentseitenzahl, die verifiziert werden soll. Wenn die Eigenschaft nicht gesetzt ist – alle Seiten von
Das Dokument wird für das erste Vorkommen verifiziert.
Der minimale Wert ist 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Dokumentseitenzahl, die verifiziert werden soll. Wenn die Eigenschaft nicht gesetzt ist – alle Seiten von
Das Dokument wird für das erste Vorkommen verifiziert.
Der minimale Wert ist 1.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Seitenoptionen, um die zu verifizierenden Seiten anzugeben.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Seitenoptionen, um die zu verifizierenden Seiten anzugeben.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Flag, um jede Dokumentseite zu verifizieren. Der Standardwert ist true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Flag, um jede Dokumentseite zu verifizieren. Der Standardwert ist true.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Zusätzliche Erweiterungen für die Verifizierung alternativer Signaturoptionen.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Zusätzliche Erweiterungen für die Verifizierung alternativer Signaturoptionen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
