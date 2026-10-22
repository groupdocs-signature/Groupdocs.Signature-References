---
title: "SignOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de signature."
type: docs
weight: 16
url: /fr/nodejs-java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Représente les options de signature.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Obtient ou définit le numéro de page du document pour la signature. |
| [setPageNumber(int value)](#setPageNumber-int-) | Obtient ou définit le numéro de page du document pour la signature. |
| [getAllPages()](#getAllPages--) | Place la signature sur toutes les pages du document. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Place la signature sur toutes les pages du document. |
| [getAppearance()](#getAppearance--) | Apparence supplémentaire de la signature. |
| [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Apparence supplémentaire de la signature. |
| [getExtensions()](#getExtensions--) | Extensions de signature. |
| [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Extensions de signature. |
| [getPagesSetup()](#getPagesSetup--) | Options pour spécifier les pages à signer. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Options pour spécifier les pages à signer. |
| [getSignatureType()](#getSignatureType--) | Obtenez le type de signature [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
| [getDocumentType()](#getDocumentType--) | Obtenez ou définissez le type de document des options de signature [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [setDocumentType(int value)](#setDocumentType-int-) | Obtenez ou définissez le type de document des options de signature [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [getZOrder()](#getZOrder--) | Obtient ou définit la position Z-order de la signature texte. |
| [setZOrder(int value)](#setZOrder-int-) | Obtient ou définit la position Z-order de la signature texte. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Obtient ou définit le numéro de page du document pour la signature. La valeur minimale et par défaut est 1.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Obtient ou définit le numéro de page du document pour la signature. La valeur minimale et par défaut est 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Place la signature sur toutes les pages du document.

**Returns:**
booléen
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Place la signature sur toutes les pages du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Apparence supplémentaire de la signature.

**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Apparence supplémentaire de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Extensions de signature.

**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Extensions de signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Options pour spécifier les pages à signer.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Options pour spécifier les pages à signer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Obtenez le type de signature [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)

**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Obtenez ou définissez le type de document des options de signature [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Obtenez ou définissez le type de document des options de signature [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Obtient ou définit la position Z-order de la signature texte. Détermine l'ordre d'affichage des signatures qui se chevauchent.

**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Obtient ou définit la position Z-order de la signature texte. Détermine l'ordre d'affichage des signatures qui se chevauchent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.

**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
