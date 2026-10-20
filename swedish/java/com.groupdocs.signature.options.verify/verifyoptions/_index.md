---
title: "VerifyOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Behåller alternativ för att verifiera dokument."
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Behåller alternativ för att verifiera dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid()](#isValid--) | Giltig egenskapsflagga. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Giltig egenskapsflagga. |
|
|  | [getPageNumber()](#getPageNumber--) | Dokument sidnummer att verifieras. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Dokument sidnummer att verifieras. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Sidalternativ för att specificera sidor att verifieras. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Sidalternativ för att specificera sidor att verifieras. |
|
|  | [getAllPages()](#getAllPages--) | Flagga för att verifiera varje dokumentsida. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Flagga för att verifiera varje dokumentsida. |
|
|  | [getExtensions()](#getExtensions--) | Ytterligare tillägg för verifiering av alternativa signaturalternativ. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Ytterligare tillägg för verifiering av alternativa signaturalternativ. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


Giltig egenskapsflagga.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Giltig egenskapsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Dokument sidnummer att verifieras. Om egenskapen inte är inställd - alla sidor av
Dokumentet kommer att verifieras för första förekomsten.
Minimalt värde är 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Dokument sidnummer att verifieras. Om egenskapen inte är inställd - alla sidor av
Dokumentet kommer att verifieras för första förekomsten.
Minimalt värde är 1.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Sidalternativ för att specificera sidor att verifieras.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Sidalternativ för att specificera sidor att verifieras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Flagga för att verifiera varje dokumentsida. Standardvärdet är sant.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Flagga för att verifiera varje dokumentsida. Standardvärdet är sant.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Ytterligare tillägg för verifiering av alternativa signaturalternativ.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Ytterligare tillägg för verifiering av alternativa signaturalternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
