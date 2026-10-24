---
title: "allow_expired‑egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Flaggan som tillåter signering med ett certifikat vars giltighetsperiod har löpt ut."
type: docs
url: /sv/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

Flaggan som tillåter signering med ett certifikat vars giltighetsperiod har löpt ut. Standardvärdet är False; signering med ett utgånget certifikat kastar `GroupDocsSignatureException` och dokumentet signeras inte.

Validatorer rapporterar en signatur som skapats med ett utgånget certifikat som ogiltig. Ställ in denna egenskap till True endast när du ändå behöver en sådan signatur, till exempel för att testa med ett gammalt certifikat. Dokumentet signeras då, och en varning skrivs till loggern som är inställd i [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Certifikatet jämförs med den aktuella tiden i UTC, inte med [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). Flaggan gäller för certifikatet som anges av [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) eller [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), och när ett kalkylblad signeras, för certifikatet för den första [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)‑tillägget. Digitala signaturer för bilder använder inte ett certifikat och kontrolleras inte. Ett certifikat vars giltighetsperiod ännu inte har börjat styrs av [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Se även
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
