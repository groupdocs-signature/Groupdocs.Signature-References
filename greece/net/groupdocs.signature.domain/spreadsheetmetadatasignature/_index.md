---
title: "SpreadsheetMetadataSignature"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Περιέχει τις ιδιότητες υπογραφής μεταδεδομένων λογιστικού φύλλου."
type: docs
weight: 1060
url: /el/net/groupdocs.signature.domain/spreadsheetmetadatasignature/
---
## SpreadsheetMetadataSignature class

Περιέχει τις ιδιότητες υπογραφής μεταδεδομένων λογιστικού φύλλου.

```csharp
public sealed class SpreadsheetMetadataSignature : MetadataSignature
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor)(string) | Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένο όνομα και κενή τιμή. |
| [SpreadsheetMetadataSignature](spreadsheetmetadatasignature#constructor_1)(string, object) | Δημιουργεί Spreadsheet Metadata Signature με προκαθορισμένες τιμές. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία δημιουργίας της υπογραφής. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Λάβετε ή ορίστε την υλοποίηση του interface [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων Value της υπογραφής. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Λάβετε τη σημαία που υποδεικνύει αν αυτή η υπογραφή διαγράφηκε από το έγγραφο. Αυτή η ιδιότητα χρησιμοποιείται μόνο για καταγραφές ιστορικού εγγράφου ώστε να διατηρεί τη λίστα των διαγραμμένων υπογραφών. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Καθορίζει το ύψος της υπογραφής. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Λάβετε ή ορίστε τη σημαία για να υποδείξετε αν αυτό το στοιχείο είναι Υπογραφή ή περιεχόμενο εγγράφου. Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο Update για να ορίσει το στοιχείο ως υπογραφή (true) ή στοιχείο εγγράφου (false). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Καθορίζει τη θέση αριστερά της υπογραφής. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Καθορίζει το μοναδικό όνομα μεταδεδομένων. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Καθορίζει τη σελίδα στην οποία βρέθηκε η υπογραφή. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Μοναδικό αναγνωριστικό υπογραφής για τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων Update ή Delete. Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search. Εάν αυτή η ιδιότητα είχε αποθηκευτεί προηγουμένως, μπορεί να οριστεί χειροκίνητα για να χειριστεί την υπογραφή. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Καθορίζει τον τύπο της υπογραφής. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Καθορίζει τη θέση πάνω της υπογραφής. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Καθορίζει τον τύπο τιμής μεταδεδομένων. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Καθορίζει το αντικείμενο μεταδεδομένων. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Καθορίζει το πλάτος της υπογραφής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone_1)() | Κλωνοποιεί την παρουσία Metadata Signature. |
| override [Clone](../../groupdocs.signature.domain/spreadsheetmetadatasignature/clone#clone)(object) | Κλωνοποιεί το στιγμιότυπο Spreadsheet Metadata Signature με τη δοθείσα τιμή. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων υπογραφής. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Αποκτά το αντικείμενο από την τιμή Metadata Signature μέσω αποσυσκευασίας. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Αποκτά το αντικείμενο από το κείμενο Metadata Signature μέσω αποσυσκευασίας. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | Αντικαθιστά τη μέθοδο GetHashCode. |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Μετατρέπει σε boolean. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Μετατρέπει σε DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Μετατρέπει σε DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Μετατρέπει σε Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Μετατρέπει σε Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Μετατρέπει σε Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Μετατρέπει σε Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Μετατρέπει σε integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Μετατρέπει σε float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Μετατρέπει σε float. |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring)() | Μετατρέπει σε String με μέθοδο παράκαμψης ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Μετατρέπει σε String με καθορισμένη μορφή |
| override [ToString](../../groupdocs.signature.domain/spreadsheetmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Μετατρέπει σε String με καθορισμένη μορφή |

### Δείτε επίσης

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
