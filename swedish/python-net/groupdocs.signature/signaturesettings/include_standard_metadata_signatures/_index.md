---
title: "include_standard_metadata_signatures egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Flaggan som indikerar om standarddokumentmetadata-signaturer såsom Författare, Ägare, skapelsedatum och ändringsdatum inkluderas i metadata-listan."
type: docs
url: /sv/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

Flaggan som indikerar om standarddokumentmetadata-signaturer såsom Författare, Ägare, skapelsedatum och ändringsdatum inkluderas i metadata-listan.

Om den är satt till False (standard) kommer GetDocumentInfo inte att inkludera dessa metadata‑signaturer. När den är satt till True kommer dokumentinformationen att inkludera de standardmetadata‑signaturerna.

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### Se även
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
