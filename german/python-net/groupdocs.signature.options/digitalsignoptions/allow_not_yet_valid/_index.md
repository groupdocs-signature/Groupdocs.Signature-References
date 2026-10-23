---
title: "allow_not_yet_valid-Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Das Flag, das das Signieren mit einem Zertifikat erlaubt, dessen Gültigkeitszeitraum noch nicht begonnen hat."
type: docs
url: /de/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

Das Flag, das das Signieren mit einem Zertifikat ermöglicht, dessen Gültigkeitszeitraum noch nicht begonnen hat. Der Standardwert ist False; das Signieren mit einem solchen Zertifikat löst `GroupDocsSignatureException` aus und das Dokument wird nicht signiert.

Validatoren melden eine Signatur, die vor dem Inkrafttreten des Zertifikats erstellt wurde, als ungültig. Ein solches Zertifikat wird normalerweise für ein späteres Datum ausgestellt, oder die Uhr des Computers ist falsch. Wenn dieses Flag True ist, wird das Dokument signiert und eine Warnung in den Logger geschrieben, der in [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/) festgelegt ist.

Das Zertifikat wird mit der aktuellen Zeit in UTC verglichen. Das Flag gilt für dieselben Zertifikate wie [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/), das Zertifikate steuert, deren Gültigkeitszeitraum beendet ist.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### Siehe auch
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
