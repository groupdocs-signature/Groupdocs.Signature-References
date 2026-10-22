---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de la signature de code-barres."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Contient les propriétés de la signature de code-barres.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Initialisez l'objet BarcodeSignature avec l'identifiant de signature obtenu après le processus de recherche. |
| [BarcodeSignature()](#BarcodeSignature--) | Initialisez BarcodeSignature avec les paramètres par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Spécifie le type d'encodage du code-barres. |
| [getText()](#getText--) | Spécifie le texte du code-barres. |
| [getFormat()](#getFormat--) | Spécifie le format de l'image de signature du code-barres. |
| [getContent()](#getContent--) | Spécifie le contenu d'image de données binaires du code-barres de type Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Clone une instance de Barcode Signature. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Initialisez l'objet BarcodeSignature avec l'identifiant de signature obtenu après le processus de recherche. Cet identifiant unique est utilisé pour trouver des propriétés supplémentaires pour cette signature dans la couche d'informations de signature du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String | Identifiant unique de signature obtenu par la méthode Sign ou Search de la classe Signature [Signature](../../com.groupdocs.signature/signature). |

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Initialisez BarcodeSignature avec les paramètres par défaut.

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Spécifie le type d'encodage du code-barres.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Spécifie le texte du code-barres.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Spécifie le format de l'image de signature du code-barres.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Spécifie le contenu d'image de données binaires du code-barres de type Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Par défaut, cette propriété ne sera pas définie. Utilisez la propriété BarcodeSearchOptions.ReturnContent ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\#setReturnContent-boolean-)) pour activer cette fonctionnalité.

**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Écrase la méthode Equals pour comparer les propriétés de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Objet de signature à comparer. |

**Returns:**
boolean - Retourne true si l'objet signature passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode

**Returns:**
int - Code de hachage de la signature
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone une instance de Barcode Signature.

**Returns:**
java.lang.Object - Retourne une instance clonée de Barcode Signature.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| image | java.awt.image.BufferedImage |  |

