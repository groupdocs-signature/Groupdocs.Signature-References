---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Περιέχει ιδιότητες υπογραφής μεταδεδομένων εικόνας."
type: docs
weight: 740
url: /el/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Περιέχει ιδιότητες υπογραφής μεταδεδομένων εικόνας.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Δημιουργεί Image Metadata Signature με Id και τιμή |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία δημιουργίας της υπογραφής. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Λάβετε ή ορίστε την υλοποίηση του interface [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων Value της υπογραφής. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Λάβετε τη σημαία που υποδεικνύει αν αυτή η υπογραφή διαγράφηκε από το έγγραφο. Αυτή η ιδιότητα χρησιμοποιείται μόνο για καταγραφές ιστορικού εγγράφου ώστε να διατηρεί τη λίστα των διαγραμμένων υπογραφών. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Τιμή μόνο για ανάγνωση για λήψη περιγραφής του τυπικού Image Metadata signature |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Καθορίζει το ύψος της υπογραφής. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Το αναγνωριστικό της υπογραφής Image Metadata. Δείτε την κλάση ImageMetadataSignatures που περιέχει την τυπική Signature με προεπιλεγμένη τιμή Id. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Λάβετε ή ορίστε τη σημαία για να υποδείξετε αν αυτό το στοιχείο είναι Υπογραφή ή περιεχόμενο εγγράφου. Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο Update για να ορίσει το στοιχείο ως υπογραφή (true) ή στοιχείο εγγράφου (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Καθορίζει τη θέση αριστερά της υπογραφής. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Καθορίζει το μοναδικό όνομα μεταδεδομένων. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Καθορίζει τη σελίδα στην οποία βρέθηκε η υπογραφή. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Μοναδικό αναγνωριστικό υπογραφής για τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων Update ή Delete. Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search. Εάν αυτή η ιδιότητα είχε αποθηκευτεί προηγουμένως, μπορεί να οριστεί χειροκίνητα για να χειριστεί την υπογραφή. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Καθορίζει τον τύπο της υπογραφής. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής Metadata |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Καθορίζει τη θέση πάνω της υπογραφής. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Καθορίζει τον τύπο τιμής μεταδεδομένων. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Καθορίζει το αντικείμενο μεταδεδομένων. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Καθορίζει το πλάτος της υπογραφής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Κλωνοποιεί την παρουσία Metadata Signature. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Κλωνοποιήστε το αντικείμενο Image Metadata Signature με την δεδομένη τιμή. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων υπογραφής. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Αποκτά το αντικείμενο από την τιμή Metadata Signature μέσω αποσυσκευασίας. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Αποκτά το αντικείμενο από το κείμενο Metadata Signature μέσω αποσυσκευασίας. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Αντικαθιστά τη μέθοδο GetHashCode. |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Μετατρέπει σε boolean. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Μετατρέπει σε DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Μετατρέπει σε DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Μετατρέπει σε Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Μετατρέπει σε Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Μετατρέπει σε Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Μετατρέπει σε Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Μετατρέπει σε integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Μετατρέπει σε long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Μετατρέπει σε float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Μετατρέπει σε float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Μετατρέπει σε String με μέθοδο παράκαμψης ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Μετατρέπει σε String με καθορισμένη μορφή |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Μετατρέπει σε String με καθορισμένη μορφή |

### Δείτε επίσης

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
