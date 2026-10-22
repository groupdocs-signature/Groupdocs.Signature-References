---
title: "SignOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die Signaturoptionen dar."
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.signature.options.sign/signoptions/
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
| [getPageNumber()](#getPageNumber--) | Liest oder setzt die Dokumentseitenzahl für die Signatur. |
| [setPageNumber(int value)](#setPageNumber-int-) | Liest oder setzt die Dokumentseitenzahl für die Signatur. |
| [getAllPages()](#getAllPages--) | Signatur auf allen Dokumentseiten platzieren. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Signatur auf allen Dokumentseiten platzieren. |
| [getAppearance()](#getAppearance--) | Zusätzliches Signatur‑Erscheinungsbild. |
| [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Zusätzliches Signatur‑Erscheinungsbild. |
| [getExtensions()](#getExtensions--) | Signatur‑Erweiterungen. |
| [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Signatur‑Erweiterungen. |
| [getPagesSetup()](#getPagesSetup--) | Optionen, um die zu signierenden Seiten anzugeben. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Optionen, um die zu signierenden Seiten anzugeben. |
| [getSignatureType()](#getSignatureType--) | Abrufen des Signaturtyps [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
| [getDocumentType()](#getDocumentType--) | Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [setDocumentType(int value)](#setDocumentType-int-) | Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [getZOrder()](#getZOrder--) | Abrufen oder Festlegen der Z-order-Position der Textsignatur. |
| [setZOrder(int value)](#setZOrder-int-) | Abrufen oder Festlegen der Z-order-Position der Textsignatur. |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Abrufen oder Festlegen der Dokumentseitenzahl für die Signatur. Minimaler und Standardwert ist 1.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Abrufen oder Festlegen der Dokumentseitenzahl für die Signatur. Minimaler und Standardwert ist 1.

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


Zusätzliches Signatur‑Erscheinungsbild.

**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Zusätzliches Signatur‑Erscheinungsbild.

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


Optionen, um die zu signierenden Seiten anzugeben.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Optionen, um die zu signierenden Seiten anzugeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Abrufen des Signaturtyps [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)

**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Abrufen oder Festlegen des Dokumenttyps der Signaturoptionen [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Abrufen oder Festlegen der Z-order-Position der Textsignatur. Bestimmt die Anzeigereihenfolge überlappender Signaturen.

**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Abrufen oder Festlegen der Z-order-Position der Textsignatur. Bestimmt die Anzeigereihenfolge überlappender Signaturen.

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
