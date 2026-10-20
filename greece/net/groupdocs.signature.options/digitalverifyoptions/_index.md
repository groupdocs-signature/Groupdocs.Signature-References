---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Διατηρεί επιλογές για την επαλήθευση της Ψηφιακής υπογραφής του εγγράφου."
type: docs
weight: 1570
url: /el/net/groupdocs.signature.options/digitalverifyoptions/
---
## DigitalVerifyOptions class

Διατηρεί επιλογές για την επαλήθευση της Ψηφιακής υπογραφής του εγγράφου.

```csharp
public class DigitalVerifyOptions : VerifyOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DigitalVerifyOptions](digitalverifyoptions#constructor)() | Δημιουργεί Digital Verification Option με προεπιλεγμένες τιμές. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_1)(Stream) | Δημιουργεί Digital Verification Option με δεδομένο ρεύμα πιστοποιητικού. |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_2)(string) | Δημιουργεί Digital Verification Option με δεδομένη διαδρομή αρχείου ψηφιακού πιστοποιητικού. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Σημαία για την επαλήθευση κάθε σελίδας του εγγράφου. Η προεπιλεγμένη τιμή είναι true. |
| [Certificate](../../groupdocs.signature.options/digitalverifyoptions/certificate) { get; } | Λάβετε το Πιστοποιητικό X509Certificate2 από το FilePath του Πιστοποιητικού ή το Stream. |
| [CertificateFilePath](../../groupdocs.signature.options/digitalverifyoptions/certificatefilepath) { get; set; } | Διαδρομή αρχείου του Digital Certificate. |
| [CertificateStream](../../groupdocs.signature.options/digitalverifyoptions/certificatestream) { get; set; } | Ρεύμα του Digital Certificate. |
| [Comments](../../groupdocs.signature.options/digitalverifyoptions/comments) { get; set; } | Σχόλια της Digital Signature για επαλήθευση. |
| [Contact](../../groupdocs.signature.options/digitalverifyoptions/contact) { get; set; } | Επαφή Υπογραφής για επαλήθευση. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής. |
| [IssuerName](../../groupdocs.signature.options/digitalverifyoptions/issuername) { get; set; } | Όνομα εκδότη του πιστοποιητικού για επαλήθευση. Η τιμή είναι ευαίσθητη σε πεζά/κεφαλαία. Εάν αυτή η ιδιότητα οριστεί, η επαλήθευση θα ελέγξει εάν το όνομα εκδότη της Υπογραφής περιέχει ή ισούται με την περασμένη τιμή. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Έγκυρη σημαία ιδιότητας. |
| [Location](../../groupdocs.signature.options/digitalverifyoptions/location) { get; set; } | Τοποθεσία Υπογραφής για επαλήθευση. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Αριθμός σελίδας εγγράφου που πρέπει να επαληθευτεί. Εάν η ιδιότητα δεν έχει οριστεί - όλες οι Σελίδες του Εγγράφου θα επαληθευτούν για την πρώτη εμφάνιση. Η ελάχιστη τιμή είναι 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν. |
| [Password](../../groupdocs.signature.options/digitalverifyoptions/password) { get; set; } | Κωδικός πρόσβασης του Digital Certificate εάν απαιτείται. |
| [Reason](../../groupdocs.signature.options/digitalverifyoptions/reason) { get; set; } | Αιτία της Digital Signature για επαλήθευση. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Καθορίζει τη θέση του σχήματος στη διάταξη του εγγράφου. Για επαλήθευση υπογραφών σε κεφαλίδες/υποσέλιδα. |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalverifyoptions/signdatetimefrom) { get; set; } | Η ημερομηνία και η χρονική περίοδος της Ψηφιακής Υπογραφής για επαλήθευση. Η τιμή Nullable θα αγνοηθεί. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalverifyoptions/signdatetimeto) { get; set; } | Η ημερομηνία και η χρονική περίοδος της Ψηφιακής Υπογραφής για επαλήθευση. Η τιμή Nullable θα αγνοηθεί. |
| [SubjectName](../../groupdocs.signature.options/digitalverifyoptions/subjectname) { get; set; } | Το διακριτικό όνομα του θέματος του πιστοποιητικού για επαλήθευση. Η τιμή είναι ευαίσθητη σε πεζά/κεφαλαία. Εάν αυτή η ιδιότητα οριστεί, η επαλήθευση θα ελέγξει εάν το όνομα θέματος της Υπογραφής περιέχει ή ισούται με την περασμένη τιμή. |

### Παρατηρήσεις

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings]()

### Δείτε επίσης

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
