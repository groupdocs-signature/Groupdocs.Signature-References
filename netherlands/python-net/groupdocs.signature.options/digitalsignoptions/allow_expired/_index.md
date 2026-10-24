---
title: "allow_expired eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De vlag die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode is beëindigd."
type: docs
url: /nl/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

De vlag die ondertekenen met een certificaat waarvan de geldigheidsperiode is verlopen toestaat. De standaardwaarde is False; ondertekenen met een verlopen certificaat veroorzaakt `GroupDocsSignatureException` en het document wordt niet ondertekend.

Validators melden een handtekening die is gemaakt met een verlopen certificaat als niet geldig. Stel deze eigenschap in op True alleen wanneer je toch zo'n handtekening nodig hebt, bijvoorbeeld om te testen met een oud certificaat. Het document wordt dan ondertekend en wordt er een waarschuwing geschreven naar de logger die is ingesteld in [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Het certificaat wordt vergeleken met de huidige tijd in UTC, niet met [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). De vlag is van toepassing op het certificaat dat wordt opgegeven door [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) of [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), en, wanneer een spreadsheet wordt ondertekend, op het certificaat van de eerste [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) extensie. Digitale handtekeningen van afbeeldingen gebruiken geen certificaat en worden niet gecontroleerd. Een certificaat waarvan de geldigheidsperiode nog niet is begonnen, wordt beheerd door [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Zie ook
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
