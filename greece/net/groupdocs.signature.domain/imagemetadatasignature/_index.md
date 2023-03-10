---
title: ImageMetadataSignature
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Περιέχει ιδιότητες υπογραφής μεταδεδομένων εικόνας.
type: docs
weight: 570
url: /el/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Περιέχει ιδιότητες υπογραφής μεταδεδομένων εικόνας.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Δημιουργεί υπογραφή μεταδεδομένων εικόνας με αναγνωριστικό και τιμή |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία δημιουργίας υπογραφής. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Λαμβάνει ή ορίζει την υλοποίηση του[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) διεπαφή για την κωδικοποίηση και την αποκωδικοποίηση της υπογραφής Ιδιότητες τιμής. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Λάβετε τη σημαία που υποδεικνύει εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο. Αυτή η ιδιότητα χρησιμοποιείται μόνο για εγγραφές καταγραφής ιστορικού εγγράφων για τη διατήρηση της λίστας των διαγραμμένων υπογραφών. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Τιμή μόνο για ανάγνωση για λήψη περιγραφής για τυπική υπογραφή Μεταδεδομένων εικόνας |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Καθορίζει το ύψος της υπογραφής. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Το αναγνωριστικό της υπογραφής Μεταδεδομένων Εικόνας. Βλ.ImageMetadataSignatures κλάση που περιέχει τυπική υπογραφή με προκαθορισμένη τιμή αναγνωριστικού. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Λάβετε ή ορίστε σημαία για να υποδείξετε εάν αυτό το στοιχείο είναι περιεχόμενο υπογραφής ή εγγράφου. Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο ενημέρωσης για να ορίσετε το στοιχείο ως υπογραφή (true) ή ως στοιχείο εγγράφου (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Καθορίζει την αριστερή θέση της υπογραφής. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Καθορίζει το μοναδικό όνομα μεταδεδομένων. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Καθορίζει την υπογραφή της σελίδας που βρέθηκε. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Μοναδικό αναγνωριστικό υπογραφής για την τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων ενημέρωσης ή διαγραφής. Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search. Εάν αυτή η ιδιότητα αποθηκεύτηκε προτού μπορέσει να οριστεί χειροκίνητα για χειρισμό της υπογραφής. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Καθορίζει τον τύπο της υπογραφής. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Τιμή μόνο για ανάγνωση για να λάβετε το μέγεθος της τιμής μεταδεδομένων |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Καθορίζει την επάνω θέση της υπογραφής. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Καθορίζει τον τύπο τιμής μεταδεδομένων. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Καθορίζει αντικείμενο μεταδεδομένων. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Καθορίζει το πλάτος της υπογραφής. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Περίπτωση υπογραφής μεταδεδομένων κλωνοποίησης. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Κλωνοποίηση στιγμιότυπο υπογραφής μεταδεδομένων εικόνας με δεδομένη τιμή. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων υπογραφής |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Λήψη αντικειμένου από την τιμή υπογραφής μεταδεδομένων έναντι της αποσειροποίησης. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Λήψη αντικειμένου από Κείμενο υπογραφής μεταδεδομένων μέσω αποσειροποίησης. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Αντικαθιστά τη μέθοδο GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Μετατρέπεται σε boolean. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Μετατρέπεται σε DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Μετατρέπεται σε DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Μετατρέπεται σε δεκαδικό. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Μετατρέπεται σε δεκαδικό. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Μετατρέπεται σε διπλό. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Μετατρέπεται σε διπλό. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Μετατρέπει σε ακέραιο. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Μετατρέπεται σε long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Μετατρέπεται σε float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Μετατρέπεται σε float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Μετατρέπεται σε συμβολοσειρά με μέθοδο παράκαμψης ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Μετατρέπεται σε συμβολοσειρά με καθορισμένη μορφή |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Μετατρέπεται σε συμβολοσειρά με καθορισμένη μορφή |

### Δείτε επίσης

* class [MetadataSignature](../metadatasignature)
* χώρος ονομάτων [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
