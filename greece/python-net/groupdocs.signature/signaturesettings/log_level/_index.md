---
title: "ιδιότητα log_level"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Οι σημαίες επιπέδου καταγραφής που καθορίζουν ποιοι τύποι μηνυμάτων περνούν στο SignatureSettings.Logger."
type: docs
url: /el/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

Οι σημαίες επιπέδου καταγραφής που καθορίζουν ποιοι τύποι μηνυμάτων περνούν στο [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

Η τιμή είναι ένα σύνολο σημαιών `LogLevel` που μπορούν να συνδυαστούν, για παράδειγμα `LogLevel.Error | LogLevel.Warning`. Το `LogLevel.None` δεν καταγράφει τίποτα. Η προεπιλογή είναι `LogLevel.All`: σφάλματα, προειδοποιήσεις και ίχνη.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Δείτε επίσης
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
