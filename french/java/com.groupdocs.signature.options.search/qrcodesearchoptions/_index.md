---
title: "QrCodeSearchOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options de recherche abstraites pour les signatures de QR-Code."
type: docs
weight: 16
url: /fr/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Représente les options de recherche abstraites pour les signatures de QR-Code.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec les valeurs par défaut. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec la valeur du type d'encodage. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Initialise une nouvelle instance de la classe QRCodeSearchOptions avec les valeurs du type d'encodage et du texte. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Spécifie la propriété Type d'encodage pour rechercher les QR-Codes. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Spécifie la propriété Type d'encodage pour rechercher les QR-Codes. |
|
|  | [getText()](#getText--) | Spécifie le texte de la signature QR-Code s'il doit être recherché et correspondre. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Spécifie le texte de la signature QR-Code s'il doit être recherché et correspondre. |
|
|  | [getMatchType()](#getMatchType--) | Obtient ou définit le type de correspondance du texte QR-Code pour la recherche. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Obtient ou définit le type de correspondance du texte QR-Code pour la recherche. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder le texte ou les propriétés de données de la signature QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder le texte ou les propriétés de données de la signature QR-Code. |
|
|  | [getReturnContent()](#getReturnContent--) | Obtient ou définit le drapeau pour récupérer le contenu image du QR-Code de la signature sur la page du document. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtient ou définit le drapeau pour récupérer le contenu image du QR-Code de la signature sur la page du document. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Spécifie le type de fichier du contenu image retourné de la signature QR-Code lorsque la propriété ReturnContent est activée. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Spécifie le type de fichier du contenu image retourné de la signature QR-Code lorsque la propriété ReturnContent est activée. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Initialise une nouvelle instance de la classe QRCodeSearchOptions avec les valeurs par défaut.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Initialise une nouvelle instance de la classe QRCodeSearchOptions avec la valeur du type d'encodage.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Spécifie le type d'encodage du QR-Code. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Initialise une nouvelle instance de la classe QRCodeSearchOptions avec les valeurs du type d'encodage et du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Spécifie le type d'encodage du QR-Code. |
|
|  | texte | java.lang.String | Définit le texte de la signature QR-Code. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Spécifie la propriété Type d'encodage pour rechercher les QR-Codes.
Si cette valeur n'est pas définie, la recherche est effectuée pour tous les types de QR-Code pris en charge.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Spécifie la propriété Type d'encodage pour rechercher les QR-Codes.
Si cette valeur n'est pas définie, la recherche est effectuée pour tous les types de QR-Code pris en charge.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Spécifie le texte de la signature QR-Code s'il doit être recherché et correspondre.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Spécifie le texte de la signature QR-Code s'il doit être recherché et correspondre.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtient ou définit le type de correspondance du texte QR-Code pour la recherche. Il n'est utilisé que lorsque la propriété Text est définie.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtient ou définit le type de correspondance du texte QR-Code pour la recherche. Il n'est utilisé que lorsque la propriété Text est définie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder le texte ou les propriétés de données de la signature QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder le texte ou les propriétés de données de la signature QR-Code.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtient ou définit le drapeau pour récupérer le contenu image du QR-Code de la signature sur la page du document.
Si ce drapeau est défini sur vrai, le contenu image de la signature QR-Code conservera les données d'image brutes au format requis.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Par défaut, cette option est désactivée.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtient ou définit le drapeau pour récupérer le contenu image du QR-Code de la signature sur la page du document.
Si ce drapeau est défini sur vrai, le contenu image de la signature QR-Code conservera les données d'image brutes au format requis.
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


Spécifie le type de fichier du contenu image retourné de la signature QR-Code lorsque la propriété ReturnContent est activée.
Par défaut, il est défini sur Null. Cela signifie que le contenu image QR-Code sera retourné dans son format original.
Ce format d'image est spécifié à
QrCodeSignature.Format
()
Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP.
Si le format fourni n'est pas pris en charge, le contenu image du QR-Code au format .png original sera renvoyé.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Spécifie le type de fichier du contenu image retourné de la signature QR-Code lorsque la propriété ReturnContent est activée.
Par défaut, il est défini sur Null. Cela signifie que le contenu image QR-Code sera retourné dans son format original.
Ce format d'image est spécifié à
QrCodeSignature.Format
()
Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP.
Si le format fourni n'est pas pris en charge, le contenu image du QR-Code au format .png original sera renvoyé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

