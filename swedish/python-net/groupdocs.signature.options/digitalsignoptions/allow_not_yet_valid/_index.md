---
title: "allow_not_yet_valid egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Flaggan som tillåter signering med ett certifikat vars giltighetsperiod ännu inte har börjat."
type: docs
url: /sv/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

Flaggan som tillåter signering med ett certifikat vars giltighetsperiod ännu inte har börjat. Standardvärdet är False; signering med ett sådant certifikat kastar `GroupDocsSignatureException` och dokumentet signeras inte.

Validatorer rapporterar en signatur som gjordes innan certifikatet blir giltigt som ogiltig. Sådant certifikat utfärdas vanligtvis för ett senare datum, eller så är datorns klocka fel. När denna flagga är True signeras dokumentet, och en varning skrivs till loggern som är inställd i [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Certifikatet jämförs med den aktuella tiden i UTC. Flaggan gäller samma certifikat som [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), som styr certifikat vars giltighetsperiod har löpt ut.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Se även
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
