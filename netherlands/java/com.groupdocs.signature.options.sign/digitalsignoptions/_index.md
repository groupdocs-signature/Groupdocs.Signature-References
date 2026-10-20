---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt de digitale handtekeningopties."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Vertegenwoordigt de digitale handtekeningopties.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met standaardwaarden. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met certificaatbestand. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatstroom. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatbestand en afbeeldingsbestand. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatbestand en afbeeldingstroom. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatstroom en afbeeldingsbestand. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatstroom en afbeeldingstroom. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getReason()](#getReason--) | Haalt op of stelt de reden van de handtekening in. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Haalt op of stelt de reden van de handtekening in. |
|
|  | [getContact()](#getContact--) | Haalt op of stelt het handtekeningcontact in. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Haalt op of stelt het handtekeningcontact in. |
|
|  | [getLocation()](#getLocation--) | Haalt op of stelt de locatie van de handtekening in. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Haalt op of stelt de locatie van de handtekening in. |
|
|  | [getPassword()](#getPassword--) | Haalt op of stelt het wachtwoord van het digitale certificaat in. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Haalt op of stelt het wachtwoord van het digitale certificaat in. |
|
|  | [getSignature()](#getSignature--) | Haalt op of stelt eigenschappen van de digitale ondertekening van het document in. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Haalt op of stelt eigenschappen van de digitale ondertekening van het document in. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Haalt op of stelt het bestandspad van het digitale certificaat in. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Haalt op of stelt de GUID van het digitale certificaatbestand in. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Haalt op of stelt de digitale certificaatstroom in. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Haalt op of stelt de digitale certificaatstroom in. |
|
|  | [getVisible()](#getVisible--) | Haalt op of stelt de zichtbaarheid van de handtekening in. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Haalt op of stelt de zichtbaarheid van de handtekening in. |
|
|  | [getUseLtv()](#getUseLtv--) | Haalt op/stelt de LTV (Long Term Validation) validatie‑vlag in. |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | Haalt op/stelt de LTV (Long Term Validation) validatie‑vlag in. |
|
|  | [getAllowExpired()](#getAllowExpired--) | Haalt op of stelt een vlag in die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode is verlopen. |
|
|  | [setAllowExpired(boolean value)](#setAllowExpired-boolean-) | Haalt op of stelt een vlag in die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode is verlopen. |
|
|  | [getAllowNotYetValid()](#getAllowNotYetValid--) | Haalt op of stelt een vlag in die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode nog niet is begonnen. |
|
|  | [setAllowNotYetValid(boolean value)](#setAllowNotYetValid-boolean-) | Haalt op of stelt een vlag in die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode nog niet is begonnen. |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Haalt op of stelt een aangepaste hash‑ondertekeningsimplementatie in, waardoor aanroepers hun eigen kunnen integreren |
digitale ondertekeningslogica (HSM, externe ondertekenaar, software‑sleutelopslag, enz.).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Stelt een aangepaste hash‑ondertekeningsimplementatie in, waardoor aanroepers hun eigen kunnen integreren |
digitale ondertekeningslogica.
|
|  | [getXAdESType()](#getXAdESType--) | XAdES-type |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES-type |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met standaardwaarden.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Initialiseert een nieuw exemplaar van de DigitalSignOptions-klasse met certificaatbestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Pad naar digitaal certificaatbestand |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitale certificaatstroom |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatbestand en afbeeldingsbestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Pad naar digitaal certificaatbestand |
|
|  | imageFilePath | java.lang.String | Handtekeningweergave afbeelding bestandspad |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatbestand en afbeeldingstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Pad naar digitaal certificaatbestand |
|
|  | appearenceImageStream | java.io.InputStream | Handtekeningweergave afbeeldingstroom |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatstroom en afbeeldingsbestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitale certificaatstroom |
|
|  | imageFilePath | java.lang.String | Handtekeningweergave afbeelding bestandspad |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Initialiseert een nieuw exemplaar van de DigitalSignOptions‑klasse met certificaatstroom en afbeeldingstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitale certificaatstroom |
|
|  | appearenceImageStream | java.io.InputStream | Handtekeningweergave afbeeldingstroom |
|

### getReason() {#getReason--}
```
public final String getReason()
```


Haalt op of stelt de reden van de handtekening in.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Haalt op of stelt de reden van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Haalt op of stelt het handtekeningcontact in.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Haalt op of stelt het handtekeningcontact in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Haalt op of stelt de locatie van de handtekening in.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Haalt op of stelt de locatie van de handtekening in.


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

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Haalt op of stelt eigenschappen van de digitale ondertekening van het document in.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Haalt op of stelt eigenschappen van de digitale ondertekening van het document in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Haalt op of stelt het bestandspad van het digitale certificaat in.
Deze eigenschap wordt alleen gebruikt als CertificateStream niet is opgegeven.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Haalt op of stelt de GUID van het digitale certificaatbestand in.
Deze eigenschap wordt alleen gebruikt als CertificateStream niet is opgegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Haalt op of stelt de digitale certificaatstroom in.
Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van CertificateGuid.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Haalt op of stelt de digitale certificaatstroom in.
Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van CertificateGuid.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Haalt op of stelt de zichtbaarheid van de handtekening in.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Haalt op of stelt de zichtbaarheid van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Haalt op/stelt de LTV (Long Term Validation) validatie‑vlag in.


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Haalt op/stelt de LTV (Long Term Validation) validatie‑vlag in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getAllowExpired() {#getAllowExpired--}
```
public final boolean getAllowExpired()
```


Haalt op of stelt een vlag in die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode is verlopen.
De standaardwaarde is false: ondertekenen met een verlopen certificaat gooit
GroupDocsSignatureException
,
en het document wordt niet ondertekend.


Validatoren melden een handtekening gemaakt met een verlopen certificaat als niet geldig. Stel deze eigenschap in op true alleen wanneer
je toch zo'n handtekening nodig hebt, bijvoorbeeld om te testen met een oud certificaat. Het document wordt dan ondertekend, en een
waarschuwing wordt geschreven naar de logger die is ingesteld in
SignatureSettings
.


Het certificaat wordt vergeleken met de huidige tijd in UTC, niet met
DigitalSignature.SignTime
. De vlag
geldt voor het certificaat dat wordt opgegeven door
CertificateFilePath
,
CertificateStream
of
Signature
,
en, wanneer een spreadsheet wordt ondertekend, naar het certificaat van de eerste
DigitalVBA
extensie. Digital
handtekeningen van afbeeldingen gebruiken geen certificaat en worden niet gecontroleerd. Een certificaat waarvan de geldigheidsperiode nog niet
begonnen is, wordt gecontroleerd door
AllowNotYetValid
.


**Returns:**
boolean
### setAllowExpired(boolean value) {#setAllowExpired-boolean-}
```
public final void setAllowExpired(boolean value)
```


Haalt op of stelt een vlag in die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode is verlopen.
De standaardwaarde is false. Zie #getAllowExpired().getAllowExpired().


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getAllowNotYetValid() {#getAllowNotYetValid--}
```
public final boolean getAllowNotYetValid()
```


Haalt op of stelt een vlag in die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode nog niet is begonnen.
De standaardwaarde is false: ondertekenen met zo'n certificaat veroorzaakt een fout.
GroupDocsSignatureException
,
en het document wordt niet ondertekend.


Validators rapporteren een handtekening gemaakt vóórdat het certificaat geldig wordt als niet geldig. Zo'n certificaat was
meestal uitgegeven voor een latere datum, of de klok van de computer is verkeerd. Wanneer deze eigenschap true is, is het document
ondertekend, en een waarschuwing wordt geschreven naar de logger ingesteld in
SignatureSettings
.


Het certificaat wordt vergeleken met de huidige tijd in UTC. De vlag is van toepassing op dezelfde certificaten als

AllowExpired
, die certificaten regelt waarvan de geldigheidsperiode is verlopen.


**Returns:**
boolean
### setAllowNotYetValid(boolean value) {#setAllowNotYetValid-boolean-}
```
public final void setAllowNotYetValid(boolean value)
```


Haalt op of stelt een vlag in die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode nog niet is begonnen.
De standaardwaarde is false. Zie #getAllowNotYetValid().getAllowNotYetValid().


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Haalt op of stelt een aangepaste hash‑ondertekeningsimplementatie in, waardoor aanroepers hun eigen kunnen integreren
digitale ondertekeningslogica (HSM, externe ondertekenaar, software‑sleutelopslag, enz.).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Stelt een aangepaste hash‑ondertekeningsimplementatie in, waardoor aanroepers hun eigen kunnen integreren
digitale ondertekeningslogica.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES-type
XAdESType
 . Standaardwaarde is None (XAdES is uit).
Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten onder .NET Framework (niet onder .NET Standard).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES-type
XAdESType
 . Standaardwaarde is None (XAdES is uit).
Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten onder .NET Framework (niet onder .NET Standard).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
