---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de la signature numérique PDF."
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Contient les propriétés de la signature numérique PDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfDigitalSignature()](#PdfDigitalSignature--) | Initialise Pdf Digital Signature sans certificat. |
| [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Crée une signature numérique PDF avec le certificat spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContactInfo()](#getContactInfo--) | Informations fournies par le signataire pour permettre au destinataire de contacter le signataire afin de vérifier la signature, p. ex. |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Informations fournies par le signataire pour permettre au destinataire de contacter le signataire afin de vérifier la signature, p. ex. |
| [getLocation()](#getLocation--) | Le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Le nom d'hôte du CPU ou l'emplacement physique de la signature. |
| [getReason()](#getReason--) | La raison de la signature, telle que (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [setReason(String value)](#setReason-java.lang.String-) | La raison de la signature, telle que (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [getType()](#getType--) | Type de signature numérique PDF. |
| [setType(int value)](#setType-int-) | Type de signature numérique PDF. |
| [getTimeStamp()](#getTimeStamp--) | Horodatage pour la signature numérique PDF. |
| [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Horodatage pour la signature numérique PDF. |
| [getShowProperties()](#getShowProperties--) | Force l'affichage/masquage des propriétés de la signature. |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | Force l'affichage/masquage des propriétés de la signature. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Clone une instance de Barcode Signature. |
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Initialise Pdf Digital Signature sans certificat.

### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Crée une signature numérique PDF avec le certificat spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| certificat | java.security.KeyStore | Certificat X509. |

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Informations fournies par le signataire pour permettre au destinataire de contacter le signataire afin de vérifier la signature, par ex. un numéro de téléphone.

**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Informations fournies par le signataire pour permettre au destinataire de contacter le signataire afin de vérifier la signature, par ex. un numéro de téléphone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Le nom d'hôte du CPU ou l'emplacement physique de la signature.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Le nom d'hôte du CPU ou l'emplacement physique de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


La raison de la signature, telle que (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


La raison de la signature, telle que (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Type de signature numérique PDF.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Type de signature numérique PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Horodatage pour la signature numérique PDF. La valeur par défaut est null.

**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Horodatage pour la signature numérique PDF. La valeur par défaut est null.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Force l'affichage/masquage des propriétés de la signature. Dans le cas où ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini Signé numériquement par \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} Date : \{Date\} Raison : \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} Lieu : \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} ShowProperties est vrai par défaut.

**Returns:**
booléen
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Force l'affichage/masquage des propriétés de la signature. Dans le cas où ShowProperties est vrai, le champ de signature a un format d'apparence prédéfini Signé numériquement par \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} Date : \{Date\} Raison : \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} Lieu : \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} ShowProperties est vrai par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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
