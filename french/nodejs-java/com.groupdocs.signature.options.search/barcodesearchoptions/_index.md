---
title: "BarcodeSearchOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de recherche abstraites pour les signatures de code-barres."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Représente les options de recherche abstraites pour les signatures de code-barres.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Initialise une nouvelle instance de la classe SearchBarcodeOptions avec les valeurs par défaut. |
| [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initialise une nouvelle instance de la classe SearchBarcodeOptions avec la valeur du type d'encodage. |
| [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Initialise une nouvelle instance de la classe SearchBarcodeOptions avec les valeurs du type d'encodage et du texte. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Spécifie la propriété Encode Type pour rechercher les codes-barres. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Spécifie la propriété Encode Type pour rechercher les codes-barres. |
| [getText()](#getText--) | Spécifie le texte de la signature Barcode si elle doit être recherchée et correspondante. |
| [setText(String value)](#setText-java.lang.String-) | Spécifie le texte de la signature Barcode si elle doit être recherchée et correspondante. |
| [getMatchType()](#getMatchType--) | Obtient ou définit la recherche du type de correspondance du texte Barcode. |
| [setMatchType(int value)](#setMatchType-int-) | Obtient ou définit la recherche du type de correspondance du texte Barcode. |
| [getReturnContent()](#getReturnContent--) | Obtient ou définit le drapeau pour récupérer le contenu image du code-barres de la signature sur la page du document. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtient ou définit le drapeau pour récupérer le contenu image du code-barres de la signature sur la page du document. |
| [getReturnContentType()](#getReturnContentType--) | Spécifie le type de fichier du contenu image retourné de la signature de code-barres lorsque la propriété ReturnContent est activée. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Spécifie le type de fichier du contenu image retourné de la signature de code-barres lorsque la propriété ReturnContent est activée. |
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Initialise une nouvelle instance de la classe SearchBarcodeOptions avec les valeurs par défaut.

### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Initialise une nouvelle instance de la classe SearchBarcodeOptions avec la valeur du type d'encodage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Spécifie le type d'encodage du code-barres. |

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Initialise une nouvelle instance de la classe SearchBarcodeOptions avec les valeurs du type d'encodage et du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Spécifie le type d'encodage du code-barres. |
| texte | java.lang.String | Définit le texte de la signature Barcode. |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Spécifie la propriété Encode Type pour rechercher les codes-barres. Si cette valeur n'est pas définie, la recherche est effectuée pour tous les types de codes-barres pris en charge.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Spécifie la propriété Encode Type pour rechercher les codes-barres. Si cette valeur n'est pas définie, la recherche est effectuée pour tous les types de codes-barres pris en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Spécifie le texte de la signature Barcode si elle doit être recherchée et correspondante.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Spécifie le texte de la signature Barcode si elle doit être recherchée et correspondante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtient ou définit la recherche du type de correspondance du texte Barcode. Elle n'est utilisée que lorsque la propriété Text est définie.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtient ou définit la recherche du type de correspondance du texte Barcode. Elle n'est utilisée que lorsque la propriété Text est définie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtient ou définit le drapeau pour récupérer le contenu image du code-barres de la signature sur la page du document. Si ce drapeau est défini sur true, le contenu image de la signature Barcode conservera les données d'image brutes au format requis ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Par défaut, cette option est désactivée.

**Returns:**
booléen
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtient ou définit le drapeau pour récupérer le contenu image du code-barres de la signature sur la page du document. Si ce drapeau est défini sur true, le contenu image de la signature Barcode conservera les données d'image brutes au format requis ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Par défaut, cette option est désactivée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Spécifie le type de fichier du contenu image retourné de la signature de code-barres lorsque la propriété ReturnContent est activée. Par défaut, il est défini sur Null. Cela signifie que le contenu image du code-barres sera retourné dans son format d'origine. Ce format d'image est spécifié dans BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP. Si le format fourni n'est pas supporté, le contenu image du code-barres sera retourné au format .png.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Spécifie le type de fichier du contenu image retourné de la signature de code-barres lorsque la propriété ReturnContent est activée. Par défaut, il est défini sur Null. Cela signifie que le contenu image du code-barres sera retourné dans son format d'origine. Ce format d'image est spécifié dans BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP. Si le format fourni n'est pas supporté, le contenu image du code-barres sera retourné au format .png.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

