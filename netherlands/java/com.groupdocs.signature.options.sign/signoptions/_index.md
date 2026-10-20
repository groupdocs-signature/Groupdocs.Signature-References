---
title: "SignOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt de handtekeningopties."
type: docs
weight: 16
url: /nl/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Vertegenwoordigt de handtekeningopties.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Haalt op of stelt het paginanummer van het document in voor ondertekening. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Haalt op of stelt het paginanummer van het document in voor ondertekening. |
|
|  | [getAllPages()](#getAllPages--) | Plaats handtekening op alle documentpagina's. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Plaats handtekening op alle documentpagina's. |
|
|  | [getAppearance()](#getAppearance--) | Aanvullende handtekeningweergave. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Aanvullende handtekeningweergave. |
|
|  | [getExtensions()](#getExtensions--) | Handtekeningextensies. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Handtekeningextensies. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opties om de te ondertekenen pagina's op te geven. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opties om de te ondertekenen pagina's op te geven. |
|
|  | [getSignatureType()](#getSignatureType--) | Haal het handtekeningtype op [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | Haal op of stel het documenttype van de handtekeningopties in [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | Haal op of stel het documenttype van de handtekeningopties in [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | Haalt op of stelt de Z-orde positie van de teksthandtekening in. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | Haalt op of stelt de Z-orde positie van de teksthandtekening in. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | Haalt op of stelt het hash-algoritme in dat gebruikt wordt voor cryptografische bewerkingen. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Haalt op of stelt het hash-algoritme in dat gebruikt wordt voor cryptografische bewerkingen. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Haalt op of stelt het paginanummer van het document in voor ondertekening.
Minimale en standaardwaarde is 1.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Haalt op of stelt het paginanummer van het document in voor ondertekening.
Minimale en standaardwaarde is 1.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Plaats handtekening op alle documentpagina's.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Plaats handtekening op alle documentpagina's.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Aanvullende handtekeningweergave.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Aanvullende handtekeningweergave.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Handtekeningextensies.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Handtekeningextensies.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Opties om de te ondertekenen pagina's op te geven.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Opties om de te ondertekenen pagina's op te geven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Haal het handtekeningtype op [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Haal op of stel het documenttype van de handtekeningopties in [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Haal op of stel het documenttype van de handtekeningopties in [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Haalt op of stelt de Z-orde positie van de teksthandtekening in.
Bepaalt de weergavevolgorde van overlappende handtekeningen.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Haalt op of stelt de Z-orde positie van de teksthandtekening in.
Bepaalt de weergavevolgorde van overlappende handtekeningen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


Haalt op of stelt het hash-algoritme in dat gebruikt wordt voor cryptografische bewerkingen.
Alleen ondersteund voor digitale handtekeningen in PDF-bestanden.
Waarde is een van de constanten op [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm).


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Haalt op of stelt het hash-algoritme in dat gebruikt wordt voor cryptografische bewerkingen.
Alleen ondersteund voor digitale handtekeningen in PDF-bestanden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
