---
title: "DigitalVBA"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta la firma digitale per progetti VBA di fogli di calcolo."
type: docs
weight: 10
url: /it/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Rappresenta la firma digitale per progetti VBA di fogli di calcolo.
Fornisce la possibilità di firmare il progetto VBA in formati di documento Spreadsheet specifici come Xlsm o Xltm.
Se vengono aggiunte diverse estensioni DigitalVBA a DigitalSignOptions.Extensions, solo la prima è coinvolta nella firma del documento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe DigitalVBA con il file del certificato. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Inizializza una nuova istanza della classe DigitalVBA con lo stream del certificato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getComments()](#getComments--) | Ottiene o imposta i commenti della firma. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Ottiene o imposta i commenti della firma. |
|
|  | [getPassword()](#getPassword--) | Ottiene o imposta la password del certificato digitale. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ottiene o imposta la password del certificato digitale. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Ottiene o imposta l'impostazione per la firma solo del progetto VBA. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Ottiene o imposta l'impostazione per la firma solo del progetto VBA. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Ottiene il percorso del file del certificato digitale. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Ottiene lo stream del certificato digitale. |
|
|  | [release()](#release--) | Metodo di override per liberare le risorse dopo la firma. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Inizializza una nuova istanza della classe DigitalVBA con il file del certificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Percorso del file del certificato digitale |
|
|  | password | java.lang.String | Password del certificato digitale |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Inizializza una nuova istanza della classe DigitalVBA con lo stream del certificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Stream del certificato digitale |
|
|  | password | java.lang.String | Password del certificato digitale |
|

### getComments() {#getComments--}
```
public final String getComments()
```


Ottiene o imposta i commenti della firma.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Ottiene o imposta i commenti della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene o imposta la password del certificato digitale.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ottiene o imposta la password del certificato digitale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Ottiene o imposta l'impostazione per la firma solo del progetto VBA.
Se impostato su true, il documento Spreadsheet non verrà firmato, ma il progetto VBA sarà firmato.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Ottiene o imposta l'impostazione per la firma solo del progetto VBA.
Se impostato su true, il documento Spreadsheet non verrà firmato, ma il progetto VBA sarà firmato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Ottiene il percorso del file del certificato digitale.
Questa proprietà è usata solo se CertificateStream non è specificato.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Ottiene lo stream del certificato digitale.
Se questa proprietà è specificata, viene sempre utilizzata al posto di CertificateFilePath.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Metodo di override per liberare le risorse dopo la firma.


