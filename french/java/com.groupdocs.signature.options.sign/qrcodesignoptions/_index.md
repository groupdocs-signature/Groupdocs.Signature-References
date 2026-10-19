---
title: "QrCodeSignOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options de signature de QR-Code."
type: docs
weight: 15
url: /fr/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Représente les options de signature de QR-Code.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | Initialise une nouvelle instance de la classe QRCodeSignOptions avec les valeurs par défaut. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Initialise une nouvelle instance de la classe QRCodeSignOptions avec du texte. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Obtient ou définit le type QRCode. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Obtient ou définit le type QRCode. |
|
|  | [getForeColor()](#getForeColor--) | Obtient ou définit la couleur de premier plan des barres QR-Code. |
L'utilisation de cette propriété pourrait poser des problèmes lors de la vérification.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Obtient ou définit la couleur de premier plan des barres QR-Code. |
L'utilisation de cette propriété pourrait poser des problèmes lors de la vérification.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Obtient ou définit la couleur de premier plan des barres QR-Code. |
L'utilisation de cette propriété pourrait poser des problèmes lors de la vérification.
|
|  | [getInnerMargins()](#getInnerMargins--) | Obtient ou définit l'espace entre les éléments QRCode et les bordures de l'image résultante. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Obtient ou définit l'espace entre les éléments QRCode et les bordures de l'image résultante. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Obtient ou définit l'alignement du texte dans l'image QR-code résultante. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Obtient ou définit l'alignement du texte dans l'image QR-code résultante. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | Obtient ou définit le nom de fichier de l'image du logo QR-code. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Obtient ou définit le nom de fichier de l'image du logo QR-code. |
|
|  | [getLogoStream()](#getLogoStream--) | Obtient ou définit le flux d'image du logo QR-code. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Obtient ou définit le flux d'image du logo QR-code. |
|
|  | [getData()](#getData--) | Obtient ou définit l'objet personnalisé à sérialiser dans le contenu QR-Code. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | Obtient ou définit l'objet personnalisé à sérialiser dans le contenu QR-Code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder le texte ou les propriétés de données de la signature QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder le texte ou les propriétés de données de la signature QR-Code. |
|
|  | [getReturnContent()](#getReturnContent--) | Obtient ou définit le drapeau permettant d'obtenir le contenu image QR-Code d'une signature placée sur la page du document. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtient ou définit le drapeau permettant d'obtenir le contenu image QR-Code d'une signature placée sur la page du document. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Spécifie le type de fichier du contenu image retourné de la signature QR-Code lorsque la propriété ReturnContent est activée. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Spécifie le type de fichier du contenu image retourné de la signature QR-Code lorsque la propriété ReturnContent est activée. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Initialise une nouvelle instance de la classe QRCodeSignOptions avec les valeurs par défaut.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Initialise une nouvelle instance de la classe QRCodeSignOptions avec du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Texte de la signature. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Texte QRCode |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Type d'encodage QRCode voir [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Obtient ou définit le type QRCode.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Obtient ou définit le type QRCode.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Obtient ou définit la couleur de premier plan des barres QR-Code.
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Obtient ou définit la couleur de premier plan des barres QR-Code.
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Obtient ou définit la couleur de premier plan des barres QR-Code.
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Obtient ou définit l'espace entre les éléments QRCode et les bordures de l'image résultante.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Obtient ou définit l'espace entre les éléments QRCode et les bordures de l'image résultante.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Obtient ou définit l'alignement du texte dans l'image QR-code résultante.
La valeur par défaut est None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Obtient ou définit l'alignement du texte dans l'image QR-code résultante.
La valeur par défaut est None.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Obtient ou définit le nom de fichier de l'image du logo QR-code.
Cette propriété est utilisée uniquement si LogoStream n'est pas spécifié.
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Obtient ou définit le nom de fichier de l'image du logo QR-code.
Cette propriété est utilisée uniquement si LogoStream n'est pas spécifié.
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Obtient ou définit le flux d'image du logo QR-code.
Si cette propriété est spécifiée, elle est toujours utilisée à la place de LogoGuid.
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Obtient ou définit le flux d'image du logo QR-code.
Si cette propriété est spécifiée, elle est toujours utilisée à la place de LogoGuid.
L'utilisation de cette propriété pourrait causer des problèmes de vérification. Utilisez-la avec précaution.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Obtient ou définit l'objet personnalisé à sérialiser dans le contenu QR-Code.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Obtient ou définit l'objet personnalisé à sérialiser dans le contenu QR-Code.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

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


Obtient ou définit le drapeau permettant d'obtenir le contenu image QR-Code d'une signature placée sur la page du document.
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


Obtient ou définit le drapeau permettant d'obtenir le contenu image QR-Code d'une signature placée sur la page du document.
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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP.
Si le format fourni n'est pas pris en charge, le contenu image QR-Code sera retourné au format .png.


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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Les valeurs prises en charge possibles sont : FileType.JPEG, FileType.PNG, FileType.BMP.
Si le format fourni n'est pas pris en charge, le contenu image QR-Code sera retourné au format .png.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
