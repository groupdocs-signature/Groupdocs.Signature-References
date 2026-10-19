---
title: "CertificateVerifyOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Conserve les options pour vérifier les documents de certificat."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Conserve les options pour vérifier les documents de certificat.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Initialise une nouvelle instance de TextVerifyOptions avec les valeurs par défaut. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Initialise une nouvelle instance de CertificateVerifyOptions avec le sujet à vérifier. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Spécifiez l'émetteur du certificat s'il doit être vérifié. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Spécifiez l'émetteur du certificat s'il doit être vérifié. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Spécifiez le numéro de série du certificat s'il doit être vérifié. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Spécifiez le numéro de série du certificat s'il doit être vérifié. |
|
|  | [getSubject()](#getSubject--) | Spécifiez le sujet du certificat s'il doit être vérifié. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Spécifiez le sujet du certificat s'il doit être vérifié. |
|
|  | [getThumbprint()](#getThumbprint--) | Spécifiez l'empreinte du certificat s'il doit être vérifié. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Spécifiez l'empreinte du certificat s'il doit être vérifié. |
|
|  | [getMatchType()](#getMatchType--) | Obtient ou définit la vérification du type de correspondance du texte. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Obtient ou définit la vérification du type de correspondance du texte. |
|
|  | [getExpired()](#getExpired--) | Indique si le certificat est expiré en fonction du résultat de validation. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Indique si le certificat est expiré en fonction du résultat de validation. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Obtenez ou définissez si le processus de vérification doit fournir la validation de la chaîne X.509 en utilisant la politique de validation de base. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Obtenez ou définissez si le processus de vérification doit fournir la validation de la chaîne X.509 en utilisant la politique de validation de base. |
|
|  | [toString()](#toString--) | Redéfinit la conversion en chaîne. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Initialise une nouvelle instance de TextVerifyOptions avec les valeurs par défaut.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Initialise une nouvelle instance de CertificateVerifyOptions avec le sujet à vérifier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | sujet | java.lang.String | Sujet à vérifier |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Spécifiez l'émetteur du certificat s'il doit être vérifié.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Spécifiez l'émetteur du certificat s'il doit être vérifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Spécifiez le numéro de série du certificat s'il doit être vérifié.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Spécifiez le numéro de série du certificat s'il doit être vérifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Spécifiez le sujet du certificat s'il doit être vérifié.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Spécifiez le sujet du certificat s'il doit être vérifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Spécifiez l'empreinte du certificat s'il doit être vérifié.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Spécifiez l'empreinte du certificat s'il doit être vérifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtient ou définit la vérification du type de correspondance du texte.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtient ou définit la vérification du type de correspondance du texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Indique si le certificat est expiré en fonction du résultat de validation.
La propriété est en lecture seule.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Indique si le certificat est expiré en fonction du résultat de validation.
La propriété est en lecture seule.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Obtenez ou définissez si le processus de vérification doit fournir la validation de la chaîne X.509 en utilisant la politique de validation de base.
Par défaut, cette valeur est vraie.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Obtenez ou définissez si le processus de vérification doit fournir la validation de la chaîne X.509 en utilisant la politique de validation de base.
Par défaut, cette valeur est vraie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Redéfinit la conversion en chaîne.


**Returns:**
java.lang.String -
