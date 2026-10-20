---
title: "DigitalVBA"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt digitale handtekening voor spreadsheets VBA-projecten."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Vertegenwoordigt digitale handtekening voor spreadsheets VBA-projecten.
Het biedt de mogelijkheid om VBA-projecten te ondertekenen in specifieke Spreadsheet-documentformaten zoals Xlsm of Xltm.
Als er meerdere DigitalVBA-extensies worden toegevoegd aan DigitalSignOptions.Extensions, wordt alleen de eerste betrokken bij het ondertekenen van het document.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatbestand. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatstroom. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getComments()](#getComments--) | Haalt de handtekeningopmerkingen op of stelt ze in. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Haalt de handtekeningopmerkingen op of stelt ze in. |
|
|  | [getPassword()](#getPassword--) | Haalt op of stelt het wachtwoord van het digitale certificaat in. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Haalt op of stelt het wachtwoord van het digitale certificaat in. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Haalt de instelling op of stelt deze in voor alleen het ondertekenen van VBA-projecten. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Haalt de instelling op of stelt deze in voor alleen het ondertekenen van VBA-projecten. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Haalt het pad naar het digitale certificaatbestand op. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Haalt de digitale certificaatstroom op. |
|
|  | [release()](#release--) | Overschrijft de methode om bronnen op te ruimen na het ondertekenen. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatbestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Pad naar digitaal certificaatbestand |
|
|  | wachtwoord | java.lang.String | Wachtwoord voor digitaal certificaat |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Initialiseert een nieuw exemplaar van de DigitalVBA-klasse met een certificaatstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitale certificaatstroom |
|
|  | wachtwoord | java.lang.String | Wachtwoord voor digitaal certificaat |
|

### getComments() {#getComments--}
```
public final String getComments()
```


Haalt de handtekeningopmerkingen op of stelt ze in.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Haalt de handtekeningopmerkingen op of stelt ze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Haalt op of stelt het wachtwoord van het digitale certificaat in.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Haalt op of stelt het wachtwoord van het digitale certificaat in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Haalt de instelling op of stelt deze in voor alleen het ondertekenen van VBA-projecten.
Indien ingesteld op true, wordt het SpreadSheet-document niet ondertekend, maar wordt het VBA-project wel ondertekend.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Haalt de instelling op of stelt deze in voor alleen het ondertekenen van VBA-projecten.
Indien ingesteld op true, wordt het SpreadSheet-document niet ondertekend, maar wordt het VBA-project wel ondertekend.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Haalt het pad naar het digitale certificaatbestand op.
Deze eigenschap wordt alleen gebruikt als CertificateStream niet is opgegeven.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Haalt de digitale certificaatstroom op.
Als deze eigenschap is gespecificeerd, wordt deze altijd gebruikt in plaats van CertificateFilePath.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Overschrijft de methode om bronnen op te ruimen na het ondertekenen.


