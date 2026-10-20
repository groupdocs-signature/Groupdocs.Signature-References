---
title: "DigitalSignature"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Περιέχει ιδιότητες ψηφιακής υπογραφής."
type: docs
weight: 150
url: /el/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Περιέχει ιδιότητες ψηφιακής υπογραφής.

```csharp
public class DigitalSignature : BaseSignature
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Αρχικοποιεί την Ψηφιακή υπογραφή με προεπιλεγμένες παραμέτρους. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Αρχικοποιεί την Ψηφιακή υπογραφή με γνωστό SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Δημιουργεί Ψηφιακή υπογραφή με το συγκεκριμένο πιστοποιητικό. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Δημιουργεί Ψηφιακή υπογραφή βασισμένη σε συγκεκριμένο κατάστημα X509. Θα χρησιμοποιηθεί το πρώτο πιστοποιητικό από το συγκεκριμένο κατάστημα. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Δημιουργεί Ψηφιακή υπογραφή βασισμένη σε συγκεκριμένο κατάστημα X509 και δείκτη του πιστοποιητικού. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Λαμβάνει ή ορίζει το πιστοποιητικό X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Καθορίζει το προσαρμοσμένο όνομα καταστήματος του πιστοποιητικού. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Καθορίζει τη θέση του καταστήματος του πιστοποιητικού. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Καθορίζει το όνομα του καταστήματος του πιστοποιητικού. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Λαμβάνει ή ορίζει το σχόλιο σκοπού υπογραφής. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία δημιουργίας της υπογραφής. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Λάβετε τη σημαία που υποδεικνύει αν αυτή η υπογραφή διαγράφηκε από το έγγραφο. Αυτή η ιδιότητα χρησιμοποιείται μόνο για καταγραφές ιστορικού εγγράφου ώστε να διατηρεί τη λίστα των διαγραμμένων υπογραφών. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Καθορίζει το ύψος της υπογραφής. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Λάβετε ή ορίστε τη σημαία για να υποδείξετε αν αυτό το στοιχείο είναι Υπογραφή ή περιεχόμενο εγγράφου. Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο Update για να ορίσει το στοιχείο ως υπογραφή (true) ή στοιχείο εγγράφου (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Παραμένει true εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραποιηθεί. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Καθορίζει τη θέση αριστερά της υπογραφής. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Καθορίζει τη σελίδα στην οποία βρέθηκε η υπογραφή. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Μοναδικό αναγνωριστικό υπογραφής για τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων Update ή Delete. Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search. Εάν αυτή η ιδιότητα είχε αποθηκευτεί προηγουμένως, μπορεί να οριστεί χειροκίνητα για να χειριστεί την υπογραφή. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Καθορίζει τον τύπο της υπογραφής. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Λαμβάνει ή ορίζει την ώρα που υπογράφηκε το έγγραφο. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Λαμβάνει το αποτύπωμα ενός πιστοποιητικού. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Καθορίζει τη θέση πάνω της υπογραφής. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Καθορίζει το πλάτος της υπογραφής. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | Τύπος XAdES [`XAdESType`](./xadestype). Η προεπιλεγμένη τιμή είναι None (το XAdES είναι απενεργοποιημένο). Αυτή τη στιγμή ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα Spreadsheet. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Κλωνοποιήστε το αντίγραφο της υπογραφής Barcode. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων υπογραφής. |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Αντικαθιστά τη μέθοδο GetHashCode. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Φορτώνει Ψηφιακές υπογραφές από όλα τα συστήματα καταστημάτων Πιστοποιητικών X509. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Φορτώνει Ψηφιακές υπογραφές από αποθήκευση πιστοποιητικού. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Φορτώνει Ψηφιακές υπογραφές από αποθήκευση πιστοποιητικού. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Φορτώνει Ψηφιακές υπογραφές από αποθήκευση ψηφιακού πιστοποιητικού που βρίσκεται σε συγκεκριμένη θέση. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Φορτώνει Ψηφιακές υπογραφές από αποθήκευση ψηφιακού πιστοποιητικού που βρίσκεται σε συγκεκριμένη θέση. |

### Δείτε επίσης

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
