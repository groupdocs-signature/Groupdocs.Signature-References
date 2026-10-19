---
title: "DigitalVBA"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente la signature numérique pour les projets VBA de feuilles de calcul."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Représente la signature numérique pour les projets VBA de feuilles de calcul.
Il fournit la capacité de signer le projet VBA dans des formats de documents Tableur spécifiques comme Xlsm ou Xltm.
Si plusieurs extensions DigitalVBA sont ajoutées à DigitalSignOptions.Extensions, seule la première est impliquée dans la signature du document.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe DigitalVBA avec le fichier de certificat. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Initialise une nouvelle instance de la classe DigitalVBA avec le flux de certificat. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getComments()](#getComments--) | Obtient ou définit les commentaires de la signature. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Obtient ou définit les commentaires de la signature. |
|
|  | [getPassword()](#getPassword--) | Obtient ou définit le mot de passe du certificat numérique. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtient ou définit le mot de passe du certificat numérique. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Obtient ou définit le paramètre de signature uniquement du projet VBA. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Obtient ou définit le paramètre de signature uniquement du projet VBA. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Obtient le chemin du fichier du certificat numérique. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Obtient le flux du certificat numérique. |
|
|  | [release()](#release--) | Méthode de substitution pour libérer les ressources après la signature. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Initialise une nouvelle instance de la classe DigitalVBA avec le fichier de certificat.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Chemin du fichier du certificat numérique |
|
|  | mot de passe | java.lang.String | Mot de passe du certificat numérique |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Initialise une nouvelle instance de la classe DigitalVBA avec le flux de certificat.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flux du certificat numérique |
|
|  | mot de passe | java.lang.String | Mot de passe du certificat numérique |
|

### getComments() {#getComments--}
```
public final String getComments()
```


Obtient ou définit les commentaires de la signature.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Obtient ou définit les commentaires de la signature.


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

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Obtient ou définit le paramètre de signature uniquement du projet VBA.
Si défini sur true, le document SpreadSheet ne sera pas signé, mais le projet VBA sera signé.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Obtient ou définit le paramètre de signature uniquement du projet VBA.
Si défini sur true, le document SpreadSheet ne sera pas signé, mais le projet VBA sera signé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Obtient le chemin du fichier du certificat numérique.
Cette propriété n'est utilisée que si CertificateStream n'est pas spécifié.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Obtient le flux du certificat numérique.
Si cette propriété est spécifiée, elle est toujours utilisée à la place de CertificateFilePath.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Méthode de substitution pour libérer les ressources après la signature.


