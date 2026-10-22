---
title: "DigitalSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de la signature numérique."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Contient les propriétés de la signature numérique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DigitalSignature()](#DigitalSignature--) | Initialise la signature numérique avec les paramètres par défaut. |
| [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Initialise la signature numérique avec un SignatureId connu. |
| [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Crée une signature numérique avec le certificat spécifié. |
| [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Crée une signature numérique basée sur le certificat X509Certificate et la clé privée PrivateKey. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Obtient ou définit le certificat KeyStore. |
| [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Obtient ou définit le certificat KeyStore. |
| [getX509Certificate()](#getX509Certificate--) | Obtient ou définit le certificat X509. |
| [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Obtient ou définit le certificat X509. |
| [getPrivateKey()](#getPrivateKey--) | Obtient ou définit la clé privée PrivateKey du certificat. |
| [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Obtient ou définit la clé privée PrivateKey du certificat. |
| [getCertificateName()](#getCertificateName--) | Obtient ou définit le nom du certificat X509. |
| [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Obtient ou définit le nom du certificat X509. |
| [getComments()](#getComments--) | Obtient ou définit le commentaire du but de la signature. |
| [setComments(String value)](#setComments-java.lang.String-) | Obtient ou définit le commentaire du but de la signature. |
| [isValid()](#isValid--) | Reste vrai si cette signature numérique est valide et que le document n'a pas été altéré. |
| [setValid(boolean value)](#setValid-boolean-) | Reste vrai si cette signature numérique est valide et que le document n'a pas été altéré. |
| [getSignTime()](#getSignTime--) | Obtient ou définit l'heure à laquelle le document a été signé. |
| [setSignTime(Date value)](#setSignTime-java.util.Date-) | Obtient ou définit l'heure à laquelle le document a été signé. |
| [getXAdESType()](#getXAdESType--) | XAdES type XAdESType. |
| [setXAdESType(int value)](#setXAdESType-int-) | XAdES type XAdESType. |
| [getThumbprint()](#getThumbprint--) | Obtient l'empreinte d'un certificat. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Clone une instance de Barcode Signature. |
| [loadDigitalSignatures()](#loadDigitalSignatures--) | Charge la signature numérique depuis tous les magasins de certificats X509 du système. |
| [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Charge la signature numérique depuis le magasin de certificats X509 fourni. |
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Initialise la signature numérique avec les paramètres par défaut.

### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Initialise la signature numérique avec un SignatureId connu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Crée une signature numérique avec le certificat spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| certificat | java.security.KeyStore | Certificat X509. |

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Crée une signature numérique basée sur le certificat X509Certificate et la clé privée PrivateKey.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cert | java.security.cert.X509Certificate | X509Certificate certificat. |
| clé | java.security.PrivateKey | Clé privée du certificat. |

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Obtient ou définit le certificat KeyStore.

**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Obtient ou définit le certificat KeyStore.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Obtient ou définit le certificat X509.

**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Obtient ou définit le certificat X509.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Obtient ou définit la clé privée PrivateKey du certificat.

**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Obtient ou définit la clé privée PrivateKey du certificat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Obtient ou définit le nom du certificat X509.

**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Obtient ou définit le nom du certificat X509.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Obtient ou définit le commentaire du but de la signature.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Obtient ou définit le commentaire du but de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Reste vrai si cette signature numérique est valide et que le document n'a pas été altéré.

**Returns:**
booléen
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Reste vrai si cette signature numérique est valide et que le document n'a pas été altéré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Obtient ou définit l'heure à laquelle le document a été signé.

**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Obtient ou définit l'heure à laquelle le document a été signé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES type  XAdESType . La valeur par défaut est None (XAdES est désactivé). À ce moment, le type de signature XAdES n'est pris en charge que pour les documents Spreadsheet.

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES type  XAdESType . La valeur par défaut est None (XAdES est désactivé). À ce moment, le type de signature XAdES n'est pris en charge que pour les documents Spreadsheet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Obtient l'empreinte d'un certificat.

**Returns:**
java.lang.String
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
### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Charge la signature numérique depuis tous les magasins de certificats X509 du système.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Retourne la liste des [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) signatures numériques.
### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Charge la signature numérique depuis le magasin de certificats X509 fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Retourne la liste des [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) signatures numériques.
