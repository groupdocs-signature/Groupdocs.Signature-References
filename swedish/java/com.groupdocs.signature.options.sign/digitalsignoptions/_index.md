---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar Digital‑signaturalternativen."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Representerar Digital‑signaturalternativen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | Initierar en ny instans av klassen DigitalSignOptions med standardvärden. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil och bildfil. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Initierar en ny instans av klassen DigitalSignOptions med certifikatfil och bildström. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström och bildfil. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Initierar en ny instans av klassen DigitalSignOptions med certifikatström och bildström. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getReason()](#getReason--) | Hämtar eller anger orsaken till signaturen. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Hämtar eller anger orsaken till signaturen. |
|
|  | [getContact()](#getContact--) | Hämtar eller anger signaturens kontakt. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Hämtar eller anger signaturens kontakt. |
|
|  | [getLocation()](#getLocation--) | Hämtar eller anger signaturens plats. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Hämtar eller anger signaturens plats. |
|
|  | [getPassword()](#getPassword--) | Hämtar eller anger lösenordet för digitalt certifikat. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Hämtar eller anger lösenordet för digitalt certifikat. |
|
|  | [getSignature()](#getSignature--) | Hämtar eller anger egenskaper för dokumentets digitala signatur. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Hämtar eller anger egenskaper för dokumentets digitala signatur. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Hämtar eller anger sökvägen till den digitala certifikatfilen. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Hämtar eller anger GUID för den digitala certifikatfilen. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Hämtar eller anger digital certifikatström. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Hämtar eller anger digital certifikatström. |
|
|  | [getVisible()](#getVisible--) | Hämtar eller anger signaturens synlighet. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger signaturens synlighet. |
|
|  | [getUseLtv()](#getUseLtv--) | Hämtar/anger LTV (Long Term Validation) valideringsflagga. |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | Hämtar/anger LTV (Long Term Validation) valideringsflagga. |
|
|  | [getAllowExpired()](#getAllowExpired--) | Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod har löpt ut. |
|
|  | [setAllowExpired(boolean value)](#setAllowExpired-boolean-) | Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod har löpt ut. |
|
|  | [getAllowNotYetValid()](#getAllowNotYetValid--) | Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod ännu inte har börjat. |
|
|  | [setAllowNotYetValid(boolean value)](#setAllowNotYetValid-boolean-) | Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod ännu inte har börjat. |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Hämtar eller anger en anpassad hash‑signeringsimplementation, som tillåter anroparna att ansluta sin egen |
digital signeringslogik (HSM, fjärrsignatur, mjukvarunyckel, etc.).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Anger en anpassad hash‑signeringsimplementation, som tillåter anroparna att ansluta sin egen |
digital signeringslogik.
|
|  | [getXAdESType()](#getXAdESType--) | XAdES-typ |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES-typ |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Initierar en ny instans av klassen DigitalSignOptions med standardvärden.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Initierar en ny instans av klassen DigitalSignOptions med certifikatfil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Sökväg till digitalt certifikatfil |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Initierar en ny instans av klassen DigitalSignOptions med certifikatström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitalt certifikatström |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Initierar en ny instans av klassen DigitalSignOptions med certifikatfil och bildfil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Sökväg till digitalt certifikatfil |
|
|  | imageFilePath | java.lang.String | Sökväg till bildfil för signaturutseende |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Initierar en ny instans av klassen DigitalSignOptions med certifikatfil och bildström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Sökväg till digitalt certifikatfil |
|
|  | appearenceImageStream | java.io.InputStream | Ström för signaturutseende bild |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Initierar en ny instans av klassen DigitalSignOptions med certifikatström och bildfil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitalt certifikatström |
|
|  | imageFilePath | java.lang.String | Sökväg till bildfil för signaturutseende |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Initierar en ny instans av klassen DigitalSignOptions med certifikatström och bildström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitalt certifikatström |
|
|  | appearenceImageStream | java.io.InputStream | Ström för signaturutseende bild |
|

### getReason() {#getReason--}
```
public final String getReason()
```


Hämtar eller anger orsaken till signaturen.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Hämtar eller anger orsaken till signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Hämtar eller anger signaturens kontakt.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Hämtar eller anger signaturens kontakt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Hämtar eller anger signaturens plats.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Hämtar eller anger signaturens plats.


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

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Hämtar eller anger egenskaper för dokumentets digitala signatur.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Hämtar eller anger egenskaper för dokumentets digitala signatur.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Hämtar eller anger sökvägen till den digitala certifikatfilen.
Denna egenskap används endast om CertificateStream inte är angiven.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Hämtar eller anger GUID för den digitala certifikatfilen.
Denna egenskap används endast om CertificateStream inte är angiven.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Hämtar eller anger digital certifikatström.
Om denna egenskap anges används den alltid istället för CertificateGuid.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Hämtar eller anger digital certifikatström.
Om denna egenskap anges används den alltid istället för CertificateGuid.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Hämtar eller anger signaturens synlighet.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Hämtar eller anger signaturens synlighet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Hämtar/anger LTV (Long Term Validation) valideringsflagga.


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Hämtar/anger LTV (Long Term Validation) valideringsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getAllowExpired() {#getAllowExpired--}
```
public final boolean getAllowExpired()
```


Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod har löpt ut.
Standardvärdet är false: signering med ett utgånget certifikat kastar
GroupDocsSignatureException
,
och dokumentet signeras inte.


Validatorer rapporterar en signatur gjord med ett utgånget certifikat som ogiltig. Ställ in denna egenskap till true endast när
du ändå behöver en sådan signatur, till exempel för att testa med ett gammalt certifikat. Dokumentet signeras då, och en
varning skrivs till loggaren som är inställd i
SignatureSettings
.


Certifikatet jämförs med den aktuella tiden i UTC, inte med
DigitalSignature.SignTime
. Flaggan
gäller för certifikatet som ges av
CertificateFilePath
,
CertificateStream
or
Signature
,
och, när ett kalkylblad signeras, till certifikatet för den första
DigitalVBA
tillägg. Digital
signaturer av bilder använder inte ett certifikat och kontrolleras inte. Ett certifikat vars giltighetsperiod inte har
börjat ännu kontrolleras av
AllowNotYetValid
.


**Returns:**
boolean
### setAllowExpired(boolean value) {#setAllowExpired-boolean-}
```
public final void setAllowExpired(boolean value)
```


Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod har löpt ut.
Standardvärdet är falskt. Se #getAllowExpired().getAllowExpired().


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getAllowNotYetValid() {#getAllowNotYetValid--}
```
public final boolean getAllowNotYetValid()
```


Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod ännu inte har börjat.
Standardvärdet är falskt: signering med ett sådant certifikat kastar
GroupDocsSignatureException
,
och dokumentet signeras inte.


Validatorer rapporterar en signatur skapad innan certifikatet blir giltigt som ogiltig. Ett sådant certifikat var
vanligtvis utfärdat för ett senare datum, eller så är datorns klocka fel. När denna egenskap är sann, är dokumentet
signerat, och en varning skrivs till loggaren som är inställd i
SignatureSettings
.


Certifikatet jämförs med den aktuella tiden i UTC. Flaggan gäller samma certifikat som

AllowExpired
, som styr certifikat vars giltighetsperiod har avslutats.


**Returns:**
boolean
### setAllowNotYetValid(boolean value) {#setAllowNotYetValid-boolean-}
```
public final void setAllowNotYetValid(boolean value)
```


Hämtar eller anger en flagga som tillåter signering med ett certifikat vars giltighetsperiod ännu inte har börjat.
Standardvärdet är falskt. Se #getAllowNotYetValid().getAllowNotYetValid().


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Hämtar eller anger en anpassad hash‑signeringsimplementation, som tillåter anroparna att ansluta sin egen
digital signeringslogik (HSM, fjärrsignatur, mjukvarunyckel, etc.).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Anger en anpassad hash‑signeringsimplementation, som tillåter anroparna att ansluta sin egen
digital signeringslogik.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES-typ
XAdESType
. Standardvärdet är None (XAdES är avstängt).
För närvarande stöds XAdES-signaturtypen endast för kalkylbladsdokument under .NET Framework (inte under .NET Standard)


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES-typ
XAdESType
. Standardvärdet är None (XAdES är avstängt).
För närvarande stöds XAdES-signaturtypen endast för kalkylbladsdokument under .NET Framework (inte under .NET Standard)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
