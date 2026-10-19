---
title: "SignOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die Signaturoptionen dar."
type: docs
weight: 16
url: /de/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Stellt die Signaturoptionen dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Liest oder setzt die Dokumentseitenzahl für die Signatur. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Liest oder setzt die Dokumentseitenzahl für die Signatur. |
|
|  | [getAllPages()](#getAllPages--) | Signatur auf allen Dokumentseiten platzieren. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Signatur auf allen Dokumentseiten platzieren. |
|
|  | [getAppearance()](#getAppearance--) | Zusätzliches Signatur‑Aussehen. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Zusätzliches Signatur‑Aussehen. |
|
|  | [getExtensions()](#getExtensions--) | Signatur‑Erweiterungen. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Signatur‑Erweiterungen. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Optionen zum Festlegen der zu signierenden Seiten. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Optionen zum Festlegen der zu signierenden Seiten. |
|
|  | [getSignatureType()](#getSignatureType--) | Erhalte den Signaturtyp [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | Lese oder setze den Dokumenttyp der Signaturoptionen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | Lese oder setze den Dokumenttyp der Signaturoptionen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | Liest oder setzt die Z‑Reihenfolge‑Position der Textsignatur. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | Liest oder setzt die Z‑Reihenfolge‑Position der Textsignatur. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | Liest oder setzt den Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Liest oder setzt den Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Liest oder setzt die Dokumentseitenzahl für die Signatur.
Minimaler und Standardwert ist 1.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Liest oder setzt die Dokumentseitenzahl für die Signatur.
Minimaler und Standardwert ist 1.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Signatur auf allen Dokumentseiten platzieren.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Signatur auf allen Dokumentseiten platzieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Zusätzliches Signatur‑Aussehen.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Zusätzliches Signatur‑Aussehen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Signatur‑Erweiterungen.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Signatur‑Erweiterungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Optionen zum Festlegen der zu signierenden Seiten.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Optionen zum Festlegen der zu signierenden Seiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Erhalte den Signaturtyp [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Lese oder setze den Dokumenttyp der Signaturoptionen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Lese oder setze den Dokumenttyp der Signaturoptionen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Liest oder setzt die Z‑Reihenfolge‑Position der Textsignatur.
Bestimmt die Anzeigereihenfolge überlappender Signaturen.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Liest oder setzt die Z‑Reihenfolge‑Position der Textsignatur.
Bestimmt die Anzeigereihenfolge überlappender Signaturen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


Liest oder setzt den Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird.
Unterstützt ausschließlich digitale Signaturen in PDF‑Dateien.
Der Wert ist einer der Konstanten in [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm).


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Liest oder setzt den Hash‑Algorithmus, der für kryptografische Vorgänge verwendet wird.
Unterstützt ausschließlich digitale Signaturen in PDF‑Dateien.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
