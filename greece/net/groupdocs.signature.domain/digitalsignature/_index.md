---
title: DigitalSignature
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Περιέχει ιδιότητες ψηφιακής υπογραφής.
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

| Ονομα | Περιγραφή |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Εκκίνηση ψηφιακής υπογραφής με προεπιλεγμένες παραμέτρους. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Εκκίνηση ψηφιακής υπογραφής με γνωστό SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Δημιουργία ψηφιακής υπογραφής με καθορισμένο πιστοποιητικό. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Δημιουργία ψηφιακής υπογραφής με βάση τον καθορισμένο χώρο αποθήκευσης X509. Θα χρησιμοποιηθεί το πρώτο πιστοποιητικό από το καθορισμένο κατάστημα. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Δημιουργία ψηφιακής υπογραφής με βάση το καθορισμένο X509 Store και ευρετήριο πιστοποιητικού. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Λαμβάνει ή ορίζει το πιστοποιητικό X509. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Καθορίζει τη θέση αποθήκευσης του πιστοποιητικού |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Καθορίζει το όνομα καταστήματος του πιστοποιητικού. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Λαμβάνει ή ορίζει το σχόλιο για το σκοπό υπογραφής. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία δημιουργίας υπογραφής. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Λάβετε τη σημαία που υποδεικνύει εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο. Αυτή η ιδιότητα χρησιμοποιείται μόνο για εγγραφές καταγραφής ιστορικού εγγράφων για τη διατήρηση της λίστας των διαγραμμένων υπογραφών. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Καθορίζει το ύψος της υπογραφής. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Λάβετε ή ορίστε σημαία για να υποδείξετε εάν αυτό το στοιχείο είναι περιεχόμενο υπογραφής ή εγγράφου. Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο ενημέρωσης για να ορίσετε το στοιχείο ως υπογραφή (true) ή ως στοιχείο εγγράφου (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Διατηρείται αληθές εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει παραβιαστεί. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Καθορίζει την αριστερή θέση της υπογραφής. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Καθορίζει την υπογραφή της σελίδας που βρέθηκε. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Μοναδικό αναγνωριστικό υπογραφής για την τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων ενημέρωσης ή διαγραφής. Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search. Εάν αυτή η ιδιότητα αποθηκεύτηκε προτού μπορέσει να οριστεί χειροκίνητα για χειρισμό της υπογραφής. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Καθορίζει τον τύπο της υπογραφής. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Λαμβάνει ή ορίζει την ώρα υπογραφής του εγγράφου. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Λαμβάνει το αποτύπωμα ενός πιστοποιητικού. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Καθορίζει την επάνω θέση της υπογραφής. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Καθορίζει το πλάτος της υπογραφής. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | τύπος XAdES[`XAdESType`](./xadestype) . Η προεπιλεγμένη τιμή είναι Κανένα (το XAdES είναι απενεργοποιημένο). Αυτή τη στιγμή ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα υπολογιστικού φύλλου. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Παράδειγμα υπογραφής γραμμικού κώδικα κλωνοποίησης. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων υπογραφής |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Αντικαθιστά τη μέθοδο GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Φόρτωση ψηφιακής υπογραφής από όλα τα καταστήματα πιστοποιητικών X509 του συστήματος. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Φόρτωση ψηφιακής υπογραφής από το X509 Certificates Store. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Φόρτωση ψηφιακής υπογραφής από το X509 Certificates Store. |

### Δείτε επίσης

* class [BaseSignature](../basesignature)
* χώρος ονομάτων [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
