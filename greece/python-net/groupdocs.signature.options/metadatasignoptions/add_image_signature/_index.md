---
title: "add_image_signature μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί ένα νέο ImageMetadataSignature με τα δοσμένα επιχειρήματα και το προσθέτει στη συλλογή."
type: docs
url: /el/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

Δημιουργεί ένα νέο ImageMetadataSignature με τα δοσμένα επιχειρήματα και το προσθέτει στη συλλογή.

```python
def add_image_signature(self, id, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| id | `System.UInt16` | Μοναδικό αναγνωριστικό για το όνομα της Image Metadata Signature. Δείτε τις αναφορές για τις προδιαγραφές ετικετών Exif για πιθανές τιμές αναγνωριστικού. |
| value | `Any` | Τιμή μεταδεδομένων. |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### Δείτε επίσης
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
