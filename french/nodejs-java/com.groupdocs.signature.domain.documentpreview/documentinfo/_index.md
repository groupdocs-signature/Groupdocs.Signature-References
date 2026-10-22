---
title: "DocumentInfo"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Définit les propriétés de description du document."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Définit les propriétés de description du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DocumentInfo()](#DocumentInfo--) | Initialise une nouvelle instance de la classe [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageCount()](#getPageCount--) | Nombre de pages du document. |
| [setPageCount(int value)](#setPageCount-int-) | Nombre de pages du document. |
| [getPages()](#getPages--) | Collection des descriptions des pages du document. |
| [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Collection des descriptions des pages du document. |
| [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Spécifie la largeur pour la hauteur maximale de la page. |
| [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Spécifie la largeur pour la hauteur maximale de la page. |
| [getMaxPageHeight()](#getMaxPageHeight--) | Spécifie la hauteur maximale de la page. |
| [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Spécifie la hauteur maximale de la page. |
| [getFileType()](#getFileType--) | Type de format de fichier. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Type de format de fichier. |
| [getSize()](#getSize--) | Taille du document en octets. |
| [setSize(long value)](#setSize-long-) | Taille du document en octets. |
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
| [getTextSignatures()](#getTextSignatures--) | Collection des signatures texte du document. |
| [getImageSignatures()](#getImageSignatures--) | Collection des signatures image du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature). |
| [getDigitalSignatures()](#getDigitalSignatures--) | Collection des signatures numériques du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature). |
| [getBarcodeSignatures()](#getBarcodeSignatures--) | Collection des signatures code-barres du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature). |
| [getQrCodeSignatures()](#getQrCodeSignatures--) | Collection des signatures QR-code du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature). |
| [getFormFieldSignatures()](#getFormFieldSignatures--) | Collection des signatures de champ de formulaire du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature). |
| [getFormFields()](#getFormFields--) | Collection de tous les champs de formulaire pris en charge existants dans le document. |
| [getMetadataSignatures()](#getMetadataSignatures--) | Collection des signatures de métadonnées du document. |
| [getProcessLogs()](#getProcessLogs--) | Collection des processus d'historique du document tels que Signer, Mettre à jour, Supprimer. |
| [getSignatures()](#getSignatures--) | Collection de toutes les signatures de tous les types du document [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Initialise une nouvelle instance de la classe [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo).

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Nombre de pages du document.

**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Nombre de pages du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Collection des descriptions des pages du document.

**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Collection des descriptions des pages du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Spécifie la largeur pour la hauteur maximale de la page.

**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Spécifie la largeur pour la hauteur maximale de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Spécifie la hauteur maximale de la page.

**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Spécifie la hauteur maximale de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Type de format de fichier.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Type de format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Taille du document en octets.

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Taille du document en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageWidth | int |  |
| pageHeight | int |  |
| pageIndex | int |  |

**Returns:**
[PageInfo](../../com.groupdocs.signature.domain/pageinfo)
### getTextSignatures() {#getTextSignatures--}
```
public final List<TextSignature> getTextSignatures()
```


Collection des signatures texte du document.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Collection des signatures image du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Collection des signatures numériques du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Collection des signatures code-barres du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Collection des signatures QR-code du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Collection des signatures de champ de formulaire du document ajoutées ou mises à jour par les méthodes [Signature](../../com.groupdocs.signature/signature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Collection de tous les champs de formulaire pris en charge existants dans le document. Cette propriété n'est prise en charge que pour les types de documents PDF et de traitement de texte.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Collection des signatures de métadonnées du document.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Collection des processus d'historique du document tels que Signer, Mettre à jour, Supprimer.

**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Collection de toutes les signatures de tous les types du document [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
