---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Περιέχει ιδιότητες ψηφιακής υπογραφής PDF."
type: docs
weight: 840
url: /el/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Περιέχει ιδιότητες ψηφιακής υπογραφής PDF.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Αρχικοποιήστε την Ψηφιακή Υπογραφή PDF χωρίς πιστοποιητικό. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Δημιουργήστε ψηφιακή υπογραφή PDF με το καθορισμένο πιστοποιητικό. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Αρχικοποιήστε την Ψηφιακή Υπογραφή PDF βάσει του καθορισμένου καταστήματος X509. Θα χρησιμοποιηθεί το πρώτο πιστοποιητικό από το καθορισμένο κατάστημα. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Δημιουργήστε ψηφιακή υπογραφή PDF βάσει του καθορισμένου καταστήματος X509 και του δείκτη του πιστοποιητικού. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Λαμβάνει ή ορίζει το πιστοποιητικό X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Καθορίζει το προσαρμοσμένο όνομα καταστήματος του πιστοποιητικού. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Καθορίζει τη θέση του καταστήματος του πιστοποιητικού. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Καθορίζει το όνομα του καταστήματος του πιστοποιητικού. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Λαμβάνει ή ορίζει το σχόλιο σκοπού υπογραφής. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Πληροφορίες που παρέχονται από τον υπογράφοντα για να επιτρέψουν στον παραλήπτη να επικοινωνήσει με τον υπογράφοντα για την επαλήθευση της υπογραφής, π.χ. έναν αριθμό τηλεφώνου. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία δημιουργίας της υπογραφής. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Λάβετε τη σημαία που υποδεικνύει αν αυτή η υπογραφή διαγράφηκε από το έγγραφο. Αυτή η ιδιότητα χρησιμοποιείται μόνο για καταγραφές ιστορικού εγγράφου ώστε να διατηρεί τη λίστα των διαγραμμένων υπογραφών. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Καθορίζει το ύψος της υπογραφής. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Λάβετε ή ορίστε τη σημαία για να υποδείξετε αν αυτό το στοιχείο είναι Υπογραφή ή περιεχόμενο εγγράφου. Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο Update για να ορίσει το στοιχείο ως υπογραφή (true) ή στοιχείο εγγράφου (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Παραμένει true εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Καθορίζει τη θέση αριστερά της υπογραφής. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Το όνομα κεντρικού υπολογιστή CPU ή η φυσική θέση της υπογραφής. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Καθορίζει τη σελίδα στην οποία βρέθηκε η υπογραφή. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Ο λόγος για την υπογραφή, όπως (Συμφωνώ). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Αναγκάστε την εμφάνιση/απόκρυψη των ιδιοτήτων υπογραφής. Σε περίπτωση που το ShowProperties είναι true, το πεδίο υπογραφής έχει προκαθορισμένη μορφή εμφάνισης Ψηφιακά υπογεγραμμένο από {[`ContactInfo`](./contactinfo)} Ημερομηνία: {Date} Αιτία: {[`Reason`](./reason)} Τοποθεσία: {[`Location`](./location)} Το ShowProperties είναι true εξ ορισμού. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Μοναδικό αναγνωριστικό υπογραφής για τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων Update ή Delete. Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search. Εάν αυτή η ιδιότητα είχε αποθηκευτεί προηγουμένως, μπορεί να οριστεί χειροκίνητα για να χειριστεί την υπογραφή. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Καθορίζει τον τύπο της υπογραφής. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Λαμβάνει ή ορίζει την ώρα που υπογράφηκε το έγγραφο. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Λαμβάνει το αποτύπωμα ενός πιστοποιητικού. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Χρονοσφραγίδα για ψηφιακή υπογραφή PDF. Η προεπιλεγμένη τιμή είναι null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Καθορίζει τη θέση πάνω της υπογραφής. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Τύπος ψηφιακής υπογραφής PDF. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Καθορίζει το πλάτος της υπογραφής. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Τύπος XAdES [`XAdESType`](../digitalsignature/xadestype). Η προεπιλεγμένη τιμή είναι None (το XAdES είναι απενεργοποιημένο). Αυτή τη στιγμή ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα Spreadsheet. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Κλωνοποιήστε το αντίγραφο της υπογραφής Barcode. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων υπογραφής. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Αντικαθιστά τη μέθοδο GetHashCode. |

### Δείτε επίσης

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
