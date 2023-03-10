---
title: WordProcessingMetadataSignature
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Περιέχει ιδιότητες υπογραφής μεταδεδομένων επεξεργασίας κειμένου.
type: docs
weight: 1070
url: /el/net/groupdocs.signature.domain/wordprocessingmetadatasignature/
---
## WordProcessingMetadataSignature class

Περιέχει ιδιότητες υπογραφής μεταδεδομένων επεξεργασίας κειμένου.

```csharp
public sealed class WordProcessingMetadataSignature : MetadataSignature
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor)(string) | Δημιουργεί υπογραφή μεταδεδομένων επεξεργασίας κειμένου με προκαθορισμένο όνομα και κενή τιμή. |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor_1)(string, object) | Δημιουργεί υπογραφή μεταδεδομένων επεξεργασίας κειμένου με προκαθορισμένες τιμές. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία δημιουργίας υπογραφής. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Λαμβάνει ή ορίζει την υλοποίηση του[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) διεπαφή για την κωδικοποίηση και την αποκωδικοποίηση της υπογραφής Ιδιότητες τιμής. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Λάβετε τη σημαία που υποδεικνύει εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο. Αυτή η ιδιότητα χρησιμοποιείται μόνο για εγγραφές καταγραφής ιστορικού εγγράφων για τη διατήρηση της λίστας των διαγραμμένων υπογραφών. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Καθορίζει το ύψος της υπογραφής. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Λάβετε ή ορίστε σημαία για να υποδείξετε εάν αυτό το στοιχείο είναι περιεχόμενο υπογραφής ή εγγράφου. Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο ενημέρωσης για να ορίσετε το στοιχείο ως υπογραφή (true) ή ως στοιχείο εγγράφου (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Καθορίζει την αριστερή θέση της υπογραφής. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Καθορίζει το μοναδικό όνομα μεταδεδομένων. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Καθορίζει την υπογραφή της σελίδας που βρέθηκε. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Μοναδικό αναγνωριστικό υπογραφής για την τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων ενημέρωσης ή διαγραφής. Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search. Εάν αυτή η ιδιότητα αποθηκεύτηκε προτού μπορέσει να οριστεί χειροκίνητα για χειρισμό της υπογραφής. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Καθορίζει τον τύπο της υπογραφής. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Καθορίζει την επάνω θέση της υπογραφής. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Καθορίζει τον τύπο τιμής μεταδεδομένων. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Καθορίζει αντικείμενο μεταδεδομένων. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Καθορίζει το πλάτος της υπογραφής. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone_1)() | Περίπτωση υπογραφής μεταδεδομένων κλωνοποίησης. |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone)(object) | Κλωνοποίηση μεταδεδομένων λέξεων Περίπτωση υπογραφής με δεδομένη τιμή. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων υπογραφής |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Λήψη αντικειμένου από την τιμή υπογραφής μεταδεδομένων έναντι της αποσειροποίησης. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Λήψη αντικειμένου από Κείμενο υπογραφής μεταδεδομένων μέσω αποσειροποίησης. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Αντικαθιστά τη μέθοδο GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Μετατρέπεται σε boolean. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Μετατρέπεται σε DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Μετατρέπεται σε DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Μετατρέπεται σε δεκαδικό. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Μετατρέπεται σε δεκαδικό. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Μετατρέπεται σε διπλό. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Μετατρέπεται σε διπλό. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Μετατρέπει σε ακέραιο. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Μετατρέπεται σε float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Μετατρέπεται σε float. |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring)() | Μετατρέπεται σε συμβολοσειρά με μέθοδο παράκαμψης ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Μετατρέπεται σε συμβολοσειρά με καθορισμένη μορφή |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Μετατρέπεται σε συμβολοσειρά με καθορισμένη μορφή |

### Δείτε επίσης

* class [MetadataSignature](../metadatasignature)
* χώρος ονομάτων [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
