---
title: "BarcodeSignOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options de signature de code-barres."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Représente les options de signature de code-barres.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec les valeurs par défaut. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Obtient ou définit le type de code-barres. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Obtient ou définit le type de code-barres. |
|
|  | [getForeColor()](#getForeColor--) | Obtient ou définit la couleur de premier plan des barres du code-barres |
L'utilisation de cette propriété pourrait poser des problèmes lors de la vérification.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Obtient ou définit la couleur de premier plan des barres du code-barres |
L'utilisation de cette propriété pourrait poser des problèmes lors de la vérification.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Obtient ou définit la couleur de premier plan des barres du code-barres |
L'utilisation de cette propriété pourrait poser des problèmes lors de la vérification.
|
|  | [getInnerMargins()](#getInnerMargins--) | Obtient ou définit l'espace entre les éléments du code-barres et les bordures de l'image résultante. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Obtient ou définit l'espace entre les éléments du code-barres et les bordures de l'image résultante. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Obtient ou définit l'alignement du texte dans l'image du code-barres résultante. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Obtient ou définit l'alignement du texte dans l'image du code-barres résultante. |
|
|  | [getReturnContent()](#getReturnContent--) | Obtient ou définit le drapeau pour récupérer le contenu image du code-barres d'une signature placée sur la page du document. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtient ou définit le drapeau pour récupérer le contenu image du code-barres d'une signature placée sur la page du document. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Spécifie le type de fichier du contenu image retourné de la signature du code-barres lorsque la propriété ReturnContent est activée. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Spécifie le type de fichier du contenu image retourné de la signature du code-barres lorsque la propriété ReturnContent est activée. |
|
|  | [validate()](#validate--) | Méthode interne pour valider les paramètres des options du code-barres. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Initialise une nouvelle instance de la classe BarcodeSignOptions avec les valeurs par défaut.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Texte du code-barres |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Texte du code-barres |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Type d'encodage du code-barres voir [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Obtient ou définit le type de code-barres.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Obtient ou définit le type de code-barres.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Obtient ou définit la couleur de premier plan des barres du code-barres
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Obtient ou définit la couleur de premier plan des barres du code-barres
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Obtient ou définit la couleur de premier plan des barres du code-barres
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Obtient ou définit l'espace entre les éléments du code-barres et les bordures de l'image résultante.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Obtient ou définit l'espace entre les éléments du code-barres et les bordures de l'image résultante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Obtient ou définit l'alignement du texte dans l'image du code-barres résultante.
La valeur par défaut est None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Obtient ou définit l'alignement du texte dans l'image du code-barres résultante.
La valeur par défaut est None.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtient ou définit le drapeau pour récupérer le contenu image du code-barres d'une signature placée sur la page du document.
Si ce drapeau est défini sur true, le contenu de l'image de la signature Barcode conservera les données d'image brutes au format requis
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Par défaut, cette option est désactivée.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtient ou définit le drapeau pour récupérer le contenu image du code-barres d'une signature placée sur la page du document.
Si ce drapeau est défini sur true, le contenu de l'image de la signature Barcode conservera les données d'image brutes au format requis
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Par défaut, cette option est désactivée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Spécifie le type de fichier du contenu image retourné de la signature du code-barres lorsque la propriété ReturnContent est activée.
Par défaut, il est réglé sur Null. Cela signifie que le contenu de l'image Barcode sera renvoyé dans son format original.
Ce format d'image est spécifié à
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP.
Si le format fourni n'est pas pris en charge, le contenu de l'image Barcode sera renvoyé au format .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Spécifie le type de fichier du contenu image retourné de la signature du code-barres lorsque la propriété ReturnContent est activée.
Par défaut, il est réglé sur Null. Cela signifie que le contenu de l'image Barcode sera renvoyé dans son format original.
Ce format d'image est spécifié à
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP.
Si le format fourni n'est pas pris en charge, le contenu de l'image Barcode sera renvoyé au format .png.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Méthode interne pour valider les paramètres des options du code-barres.


### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.


**Returns:**
java.lang.String -
