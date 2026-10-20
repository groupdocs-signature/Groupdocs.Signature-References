---
title: "SignOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar signaturalternativen."
type: docs
weight: 16
url: /sv/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Representerar signaturalternativen.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Hämtar eller anger sidnummer i dokumentet för signering. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Hämtar eller anger sidnummer i dokumentet för signering. |
|
|  | [getAllPages()](#getAllPages--) | Placera signatur på alla dokumentets sidor. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Placera signatur på alla dokumentets sidor. |
|
|  | [getAppearance()](#getAppearance--) | Ytterligare signaturutseende. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Ytterligare signaturutseende. |
|
|  | [getExtensions()](#getExtensions--) | Signaturtillägg. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Signaturtillägg. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Alternativ för att ange vilka sidor som ska signeras. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Alternativ för att ange vilka sidor som ska signeras. |
|
|  | [getSignatureType()](#getSignatureType--) | Hämta signaturtypen [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | Hämta eller ange dokumenttypen för signaturalternativen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | Hämta eller ange dokumenttypen för signaturalternativen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | Hämtar eller anger Z‑ordningspositionen för textsignatur. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | Hämtar eller anger Z‑ordningspositionen för textsignatur. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | Hämtar eller anger hash‑algoritmen som ska användas för kryptografiska operationer. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Hämtar eller anger hash‑algoritmen som ska användas för kryptografiska operationer. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Hämtar eller anger sidnummer i dokumentet för signering.
Minimalt och standardvärde är 1.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Hämtar eller anger sidnummer i dokumentet för signering.
Minimalt och standardvärde är 1.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Placera signatur på alla dokumentets sidor.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Placera signatur på alla dokumentets sidor.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Ytterligare signaturutseende.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Ytterligare signaturutseende.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Signaturtillägg.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Signaturtillägg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Alternativ för att ange vilka sidor som ska signeras.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Alternativ för att ange vilka sidor som ska signeras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Hämta signaturtypen [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Hämta eller ange dokumenttypen för signaturalternativen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Hämta eller ange dokumenttypen för signaturalternativen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Hämtar eller anger Z‑ordningspositionen för textsignatur.
Bestämmer visningsordningen för överlappande signaturer.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Hämtar eller anger Z‑ordningspositionen för textsignatur.
Bestämmer visningsordningen för överlappande signaturer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


Hämtar eller anger hash‑algoritmen som ska användas för kryptografiska operationer.
Stöds uteslutande för digitala signaturer i PDF‑filer.
Värdet är en av konstanterna i [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm).


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Hämtar eller anger hash‑algoritmen som ska användas för kryptografiska operationer.
Stöds uteslutande för digitala signaturer i PDF‑filer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
