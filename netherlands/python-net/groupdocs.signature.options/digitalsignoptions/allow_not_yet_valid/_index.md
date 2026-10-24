---
title: "allow_not_yet_valid eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De vlag die ondertekenen met een certificaat mogelijk maakt waarvan de geldigheidsperiode nog niet is begonnen."
type: docs
url: /nl/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

De vlag die ondertekenen met een certificaat waarvan de geldigheidsperiode nog niet is begonnen toestaat. De standaardwaarde is False; ondertekenen met zo'n certificaat veroorzaakt `GroupDocsSignatureException` en het document wordt niet ondertekend.

Validators melden een handtekening die is gemaakt voordat het certificaat geldig wordt als niet geldig. Zo'n certificaat wordt meestal uitgegeven voor een latere datum, of de klok van de computer staat verkeerd. Wanneer deze vlag True is, wordt het document ondertekend en wordt er een waarschuwing geschreven naar de logger die is ingesteld in [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Het certificaat wordt vergeleken met de huidige tijd in UTC. De vlag is van toepassing op dezelfde certificaten als [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), die certificaten beheert waarvan de geldigheidsperiode is beëindigd.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Zie ook
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
