---
title: PdfDigitalSignature
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Περιέχει ιδιότητες ψηφιακής υπογραφής Pdf.
type: docs
weight: 660
url: /el/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Περιέχει ιδιότητες ψηφιακής υπογραφής Pdf.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Εκκίνηση ψηφιακής υπογραφής Pdf χωρίς πιστοποιητικό. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Δημιουργία ψηφιακής υπογραφής Pdf με καθορισμένο πιστοποιητικό. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Εκκινήστε την ψηφιακή υπογραφή Pdf με βάση τον καθορισμένο χώρο αποθήκευσης X509. Θα χρησιμοποιηθεί το πρώτο πιστοποιητικό από το καθορισμένο κατάστημα. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Δημιουργία ψηφιακής υπογραφής Pdf με βάση την καθορισμένη αποθήκευση X509 και το ευρετήριο πιστοποιητικού. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Λαμβάνει ή ορίζει το πιστοποιητικό X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Καθορίζει τη θέση αποθήκευσης του πιστοποιητικού |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Καθορίζει το όνομα καταστήματος του πιστοποιητικού. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Λαμβάνει ή ορίζει το σχόλιο για το σκοπό υπογραφής. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Πληροφορίες που παρέχονται από τον υπογράφοντα για να μπορέσει ένας παραλήπτης να επικοινωνήσει με τον υπογράφοντα για να επαληθεύσει την υπογραφή, π.χ. έναν αριθμό τηλεφώνου. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία δημιουργίας υπογραφής. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Λάβετε τη σημαία που υποδεικνύει εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο. Αυτή η ιδιότητα χρησιμοποιείται μόνο για εγγραφές καταγραφής ιστορικού εγγράφων για τη διατήρηση της λίστας των διαγραμμένων υπογραφών. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Καθορίζει το ύψος της υπογραφής. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Λάβετε ή ορίστε σημαία για να υποδείξετε εάν αυτό το στοιχείο είναι περιεχόμενο υπογραφής ή εγγράφου. Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο ενημέρωσης για να ορίσετε το στοιχείο ως υπογραφή (true) ή ως στοιχείο εγγράφου (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Διατηρείται αληθές εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραβιαστεί. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Καθορίζει την αριστερή θέση της υπογραφής. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Το όνομα κεντρικού υπολογιστή CPU ή η φυσική τοποθεσία της υπογραφής. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Καθορίζει την υπογραφή της σελίδας που βρέθηκε. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Ο λόγος της υπογραφής, όπως (συμφωνώІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Αναγκαστική εμφάνιση/απόκρυψη ιδιοτήτων υπογραφής. Σε περίπτωση που το ShowProperties είναι αληθές signature το πεδίο έχει προκαθορισμένη μορφή εμφάνισης Ψηφιακά υπογεγραμμένο από τον χρήστη {[`ContactInfo`](./contactinfo)} Ημερομηνία: {Ημερομηνία} Αιτία: {[`Reason`](./reason)} Τοποθεσία: {[`Location`](./location) Το } ShowProperties είναι αληθές από προεπιλογή. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Μοναδικό αναγνωριστικό υπογραφής για την τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων ενημέρωσης ή διαγραφής. Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search. Εάν αυτή η ιδιότητα αποθηκεύτηκε προτού μπορέσει να οριστεί χειροκίνητα για χειρισμό της υπογραφής. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Καθορίζει τον τύπο της υπογραφής. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Λαμβάνει ή ορίζει την ώρα υπογραφής του εγγράφου. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Λαμβάνει το αποτύπωμα ενός πιστοποιητικού. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Χρονική σφραγίδα για ψηφιακή υπογραφή Pdf. Η προεπιλεγμένη τιμή είναι null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Καθορίζει την επάνω θέση της υπογραφής. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Τύπος ψηφιακής υπογραφής Pdf. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Καθορίζει το πλάτος της υπογραφής. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | τύπος XAdES[`XAdESType`](../digitalsignature/xadestype) . Η προεπιλεγμένη τιμή είναι Κανένα (το XAdES είναι απενεργοποιημένο). Αυτή τη στιγμή ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα υπολογιστικού φύλλου. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Παράδειγμα υπογραφής γραμμικού κώδικα κλωνοποίησης. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων υπογραφής |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Αντικαθιστά τη μέθοδο GetHashCode |

### Δείτε επίσης

* class [DigitalSignature](../digitalsignature)
* χώρος ονομάτων [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
