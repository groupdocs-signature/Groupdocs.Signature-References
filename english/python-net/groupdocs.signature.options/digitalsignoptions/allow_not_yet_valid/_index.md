---
title: allow_not_yet_valid property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag that allows signing with a certificate whose validity period has not started yet."
type: docs
url: /python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

The flag that allows signing with a certificate whose validity period has not started yet. The default value is False; signing with such a certificate raises `GroupDocsSignatureException` and the document is not signed.

Validators report a signature made before the certificate becomes valid as not valid. Such a certificate is usually issued for a later date, or the computer's clock is wrong. When this flag is True, the document is signed, and a warning is written to the logger set in [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

The certificate is compared with the current time in UTC. The flag applies to the same certificates as [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), which controls certificates whose validity period has ended.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### See Also
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
