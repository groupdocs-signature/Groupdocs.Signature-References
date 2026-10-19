---
title: "QrCodeSignature"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Contient les propriétés de la signature QR-code."
type: docs
weight: 16
url: /fr/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Contient les propriétés de la signature QR-code.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Initialise l'objet QrCodeSignature avec l'identifiant de signature qui a été obtenu après le processus de recherche. |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Spécifie le type d'encodage du QR-code. |
|
|  | [getText()](#getText--) | Spécifie le texte du QR-code. |
|
|  | [getFormat()](#getFormat--) | Spécifie le format de l'image de signature du QR-code. |
|
|  | [getContent()](#getContent--) | Spécifie le contenu d'image de données binaires du QR-code de type |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Obtient l'objet à partir du texte de signature QR-Code lors de la désérialisation. |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Obtient l'objet à partir du texte de signature QR-Code lors de la désérialisation. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Remplace la méthode Equals pour comparer les propriétés de la signature |
|
|  | [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clone l'instance de signature QR-Code. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Initialise l'objet QrCodeSignature avec l'identifiant de signature qui a été obtenu après le processus de recherche.
Cet identifiant unique est utilisé pour trouver des propriétés supplémentaires pour cette signature à partir de la couche d'informations de signature du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signatureId | java.lang.String | Identifiant de signature unique obtenu par la méthode de signature ou de recherche. |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Spécifie le type d'encodage du QR-code.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Spécifie le texte du QR-code.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Spécifie le format de l'image de signature du QR-code.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Spécifie le contenu d'image de données binaires du QR-code de type
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Par défaut, cette propriété ne sera pas définie.
Utilisez la propriété
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) pour activer cette fonctionnalité.


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Obtient l'objet à partir du texte de signature QR-Code lors de la désérialisation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | java.lang.Class<T> |  |

**Returns:**
T -
T
: Type d'objet à désérialiser à partir du texte du code QR

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Obtient l'objet à partir du texte de signature QR-Code lors de la désérialisation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Définir une implémentation de chiffrement des données personnalisée |


T
: Type d'objet à désérialiser à partir du texte du code QR
|
| type | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Remplace la méthode Equals pour comparer les propriétés de la signature


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signature | java.lang.Object | Objet de signature à comparer. |
|

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


Clone l'instance de signature QR-Code.


**Returns:**
java.lang.Object - Retourne une instance de Signature QR-code clonée.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| image | java.awt.image.BufferedImage |  |

