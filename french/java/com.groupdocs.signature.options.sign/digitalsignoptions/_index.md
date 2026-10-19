---
title: "DigitalSignOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options de signature numérique."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Représente les options de signature numérique.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | Initialise une nouvelle instance de la classe DigitalSignOptions avec les valeurs par défaut. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificat. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat et le fichier d'image. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat et le flux d'image. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificat et le fichier d'image. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificat et le flux d'image. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getReason()](#getReason--) | Obtient ou définit la raison de la signature. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Obtient ou définit la raison de la signature. |
|
|  | [getContact()](#getContact--) | Obtient ou définit le contact de la signature. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Obtient ou définit le contact de la signature. |
|
|  | [getLocation()](#getLocation--) | Obtient ou définit l'emplacement de la signature. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Obtient ou définit l'emplacement de la signature. |
|
|  | [getPassword()](#getPassword--) | Obtient ou définit le mot de passe du certificat numérique. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtient ou définit le mot de passe du certificat numérique. |
|
|  | [getSignature()](#getSignature--) | Obtient ou définit les propriétés de la signature numérique du document. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Obtient ou définit les propriétés de la signature numérique du document. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Obtient ou définit le chemin du fichier du certificat numérique. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Obtient ou définit le GUID du fichier du certificat numérique. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Obtient ou définit le flux du certificat numérique. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Obtient ou définit le flux du certificat numérique. |
|
|  | [getVisible()](#getVisible--) | Obtient ou définit la visibilité de la signature. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Obtient ou définit la visibilité de la signature. |
|
|  | [getUseLtv()](#getUseLtv--) | Obtient/définit le drapeau de validation LTV (Long Term Validation). |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | Obtient/définit le drapeau de validation LTV (Long Term Validation). |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Obtient ou définit une implémentation personnalisée de signature de hachage, permettant aux appelants d'intégrer la leur |
logique de signature numérique (HSM, signataire distant, magasin de clés logiciel, etc.).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Définit une implémentation personnalisée de signature de hachage, permettant aux appelants d'intégrer la leur |
logique de signature numérique.
|
|  | [getXAdESType()](#getXAdESType--) | type XAdES |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | type XAdES |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Initialise une nouvelle instance de la classe DigitalSignOptions avec les valeurs par défaut.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Chemin du fichier du certificat numérique |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificat.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flux du certificat numérique |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat et le fichier d'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Chemin du fichier du certificat numérique |
|
|  | imageFilePath | java.lang.String | Chemin du fichier image d'apparence de la signature |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Initialise une nouvelle instance de la classe DigitalSignOptions avec le fichier de certificat et le flux d'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Chemin du fichier du certificat numérique |
|
|  | appearenceImageStream | java.io.InputStream | Flux d'image d'apparence de la signature |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificat et le fichier d'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flux du certificat numérique |
|
|  | imageFilePath | java.lang.String | Chemin du fichier image d'apparence de la signature |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Initialise une nouvelle instance de la classe DigitalSignOptions avec le flux de certificat et le flux d'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flux du certificat numérique |
|
|  | appearenceImageStream | java.io.InputStream | Flux d'image d'apparence de la signature |
|

### getReason() {#getReason--}
```
public final String getReason()
```


Obtient ou définit la raison de la signature.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Obtient ou définit la raison de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Obtient ou définit le contact de la signature.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Obtient ou définit le contact de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Obtient ou définit l'emplacement de la signature.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Obtient ou définit l'emplacement de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient ou définit le mot de passe du certificat numérique.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtient ou définit le mot de passe du certificat numérique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Obtient ou définit les propriétés de la signature numérique du document.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Obtient ou définit les propriétés de la signature numérique du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Obtient ou définit le chemin du fichier du certificat numérique.
Cette propriété n'est utilisée que si CertificateStream n'est pas spécifié.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Obtient ou définit le GUID du fichier du certificat numérique.
Cette propriété n'est utilisée que si CertificateStream n'est pas spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Obtient ou définit le flux du certificat numérique.
Si cette propriété est spécifiée, elle est toujours utilisée à la place de CertificateGuid.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Obtient ou définit le flux du certificat numérique.
Si cette propriété est spécifiée, elle est toujours utilisée à la place de CertificateGuid.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Obtient ou définit la visibilité de la signature.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Obtient ou définit la visibilité de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Obtient/définit le drapeau de validation LTV (Long Term Validation).


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Obtient/définit le drapeau de validation LTV (Long Term Validation).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Obtient ou définit une implémentation personnalisée de signature de hachage, permettant aux appelants d'intégrer la leur
logique de signature numérique (HSM, signataire distant, magasin de clés logiciel, etc.).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Définit une implémentation personnalisée de signature de hachage, permettant aux appelants d'intégrer la leur
logique de signature numérique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


type XAdES
XAdESType
. Valeur par défaut : Aucun (XAdES est désactivé).
Pour le moment, le type de signature XAdES n'est pris en charge que pour les documents Spreadsheet sous .NET Framework uniquement (pas sous .NET Standard).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


type XAdES
XAdESType
. Valeur par défaut : Aucun (XAdES est désactivé).
Pour le moment, le type de signature XAdES n'est pris en charge que pour les documents Spreadsheet sous .NET Framework uniquement (pas sous .NET Standard).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.


**Returns:**
java.lang.String -
