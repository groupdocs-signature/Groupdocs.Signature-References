---
title: allow_expired property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag that allows signing with a certificate whose validity period has ended."
type: docs
url: /python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

The flag that allows signing with a certificate whose validity period has ended. The default value is False; signing with an expired certificate raises `GroupDocsSignatureException` and the document is not signed.

Validators report a signature made with an expired certificate as not valid. Set this property to True only when you need such a signature anyway, for example to test with an old certificate. The document is then signed, and a warning is written to the logger set in [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

The certificate is compared with the current time in UTC, not with [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). The flag applies to the certificate given by [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) or [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), and, when a spreadsheet is signed, to the certificate of the first [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) extension. Digital signatures of images do not use a certificate and are not checked. A certificate whose validity period has not started yet is controlled by [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### See Also
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
