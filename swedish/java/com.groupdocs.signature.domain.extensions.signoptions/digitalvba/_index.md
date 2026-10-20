---
title: "DigitalVBA"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar digital signatur för kalkylblads‑VBA‑projekt."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Representerar digital signatur för kalkylblads‑VBA‑projekt.
Den ger möjlighet att signera VBA-projekt i specifika kalkylbladsdokumentformat som Xlsm eller Xltm.
Om flera DigitalVBA-tillägg läggs till i DigitalSignOptions.Extensions används endast det första vid dokumentsignering.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Initierar en ny instans av DigitalVBA-klassen med certifikatfil. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Initierar en ny instans av DigitalVBA-klassen med certifikatström. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getComments()](#getComments--) | Hämtar eller anger signaturkommentarerna. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Hämtar eller anger signaturkommentarerna. |
|
|  | [getPassword()](#getPassword--) | Hämtar eller anger lösenordet för digitalt certifikat. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Hämtar eller anger lösenordet för digitalt certifikat. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Hämtar eller anger inställning för enbart signering av VBA-projekt. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Hämtar eller anger inställning för enbart signering av VBA-projekt. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Hämtar sökväg till digitalt certifikatfil. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Hämtar digitalt certifikatström. |
|
|  | [release()](#release--) | Åsidosätt metod för att rensa upp resurser efter signering. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Initierar en ny instans av DigitalVBA-klassen med certifikatfil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Sökväg till digitalt certifikatfil |
|
|  | lösenord | java.lang.String | Digitalt certifikatlösenord |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Initierar en ny instans av DigitalVBA-klassen med certifikatström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitalt certifikatström |
|
|  | lösenord | java.lang.String | Digitalt certifikatlösenord |
|

### getComments() {#getComments--}
```
public final String getComments()
```


Hämtar eller anger signaturkommentarerna.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Hämtar eller anger signaturkommentarerna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar eller anger lösenordet för digitalt certifikat.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Hämtar eller anger lösenordet för digitalt certifikat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Hämtar eller anger inställning för enbart signering av VBA-projekt.
Om satt till true kommer kalkylbladsdokumentet inte att signeras, men VBA-projektet kommer att signeras.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Hämtar eller anger inställning för enbart signering av VBA-projekt.
Om satt till true kommer kalkylbladsdokumentet inte att signeras, men VBA-projektet kommer att signeras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Hämtar sökväg till digitalt certifikatfil.
Denna egenskap används endast om CertificateStream inte är angiven.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Hämtar digitalt certifikatström.
Om denna egenskap är specificerad används den alltid istället för CertificateFilePath.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Åsidosätt metod för att rensa upp resurser efter signering.


