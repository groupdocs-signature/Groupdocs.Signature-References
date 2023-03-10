---
title: ProcessProgressEventArgs
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Παρέχει δεδομένα για το συμβάν OnProgress διαδικασιών υπογραφής επαλήθευσης και αναζήτησης.
type: docs
weight: 1840
url: /el/net/groupdocs.signature/processprogresseventargs/
---
## ProcessProgressEventArgs class

Παρέχει δεδομένα για το συμβάν OnProgress διαδικασιών υπογραφής, επαλήθευσης και αναζήτησης.

```csharp
public class ProcessProgressEventArgs : ProcessEventArgs
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ProcessProgressEventArgs](processprogresseventargs)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Cancel](../../groupdocs.signature/processprogresseventargs/cancel) { get; set; } | Υποδεικνύει εάν η διαδικασία πρέπει να ακυρωθεί. |
| [ProcessedSignatures](../../groupdocs.signature/processprogresseventargs/processedsignatures) { get; set; } | Αντιπροσωπεύει την ποσότητα των επεξεργασμένων υπογραφών. |
| [Progress](../../groupdocs.signature/processprogresseventargs/progress) { get; set; } | Αντιπροσωπεύει την πρόοδο σε ποσοστά. Το εύρος τιμών είναι από 0 έως 100. |
| [Status](../../groupdocs.signature/processeventargs/status) { get; set; } | Υποδεικνύει την τρέχουσα κατάσταση διαδικασίας. |
| [Ticks](../../groupdocs.signature/processprogresseventargs/ticks) { get; set; } | Αντιπροσωπεύει το χρόνο που δαπανήθηκε σε χιλιοστά του δευτερολέπτου από το συμβάν Έναρξης της διαδικασίας. |

### Δείτε επίσης

* class [ProcessEventArgs](../processeventargs)
* χώρος ονομάτων [GroupDocs.Signature](../../groupdocs.signature)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->