---
title: "ιδιότητα allow_expired"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η σημαία που επιτρέπει την υπογραφή με πιστοποιητικό του οποίου η περίοδος ισχύος έχει λήξει."
type: docs
url: /el/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

Η σημαία που επιτρέπει την υπογραφή με ένα πιστοποιητικό του οποίου η περίοδος ισχύος έχει λήξει. Η προεπιλεγμένη τιμή είναι False· η υπογραφή με ληγμένο πιστοποιητικό προκαλεί την εξαίρεση `GroupDocsSignatureException` και το έγγραφο δεν υπογράφεται.

Οι επικυρωτές αναφέρουν μια υπογραφή που δημιουργήθηκε με ληγμένο πιστοποιητικό ως μη έγκυρη. Ορίστε αυτή την ιδιότητα σε True μόνο όταν χρειάζεστε τέτοια υπογραφή οπωσδήποτε, για παράδειγμα για δοκιμή με παλιό πιστοποιητικό. Το έγγραφο τότε υπογράφεται και γράφεται μια προειδοποίηση στον καταγραφέα που έχει οριστεί στο [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Το πιστοποιητικό συγκρίνεται με την τρέχουσα ώρα σε UTC, όχι με το [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). Η σημαία εφαρμόζεται στο πιστοποιητικό που παρέχεται από το [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/), το [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) ή το [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/), και, όταν υπογράφεται ένα spreadsheet, στο πιστοποιητικό της πρώτης επέκτασης [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/). Οι ψηφιακές υπογραφές εικόνων δεν χρησιμοποιούν πιστοποιητικό και δεν ελέγχονται. Ένα πιστοποιητικό του οποίου η περίοδος ισχύος δεν έχει ακόμη ξεκινήσει ελέγχεται από το [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### Δείτε επίσης
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
