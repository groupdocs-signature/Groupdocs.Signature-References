---
title: "allow_expired-Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Das Flag, das das Signieren mit einem Zertifikat erlaubt, dessen Gültigkeitszeitraum beendet ist."
type: docs
url: /de/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

Das Flag, das das Signieren mit einem Zertifikat ermöglicht, dessen Gültigkeitszeitraum abgelaufen ist. Der Standardwert ist False; das Signieren mit einem abgelaufenen Zertifikat löst `GroupDocsSignatureException` aus und das Dokument wird nicht signiert.

Validatoren melden eine mit einem abgelaufenen Zertifikat erstellte Signatur als ungültig. Setzen Sie diese Eigenschaft nur auf True, wenn Sie eine solche Signatur trotzdem benötigen, zum Beispiel zum Testen mit einem alten Zertifikat. Das Dokument wird dann signiert und eine Warnung wird in den Logger geschrieben, der in [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) festgelegt ist.

Das Zertifikat wird mit der aktuellen UTC-Zeit verglichen, nicht mit [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). Das Flag gilt für das Zertifikat, das über [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) oder [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/) bereitgestellt wird, und, wenn eine Tabellenkalkulation signiert wird, für das Zertifikat der ersten [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) Erweiterung. Digitale Signaturen von Bildern verwenden kein Zertifikat und werden nicht geprüft. Ein Zertifikat, dessen Gültigkeitszeitraum noch nicht begonnen hat, wird durch [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) gesteuert.

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Siehe auch
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
