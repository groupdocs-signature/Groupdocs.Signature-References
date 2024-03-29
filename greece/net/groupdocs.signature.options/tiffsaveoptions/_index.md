---
title: TiffSaveOptions
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Tiff Επιλογές αποθήκευσης για έγγραφα εικόνας.
type: docs
weight: 1760
url: /el/net/groupdocs.signature.options/tiffsaveoptions/
---
## TiffSaveOptions class

Tiff Επιλογές αποθήκευσης για έγγραφα εικόνας.

```csharp
public sealed class TiffSaveOptions : ImageSaveOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [TiffSaveOptions](tiffsaveoptions)() | Δημιουργεί TiffSaveOptions με προεπιλεγμένες τιμές. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Λαμβάνει ή ορίζει τη σημαία για αυτόματη προσθήκη επέκτασης όταν έλειπε στο αρχείο εξόδου path Η προεπιλεγμένη τιμή είναι false. |
| [ExpectedTiffFormat](../../groupdocs.signature.options/tiffsaveoptions/expectedtiffformat) { get; set; } | Λαμβάνει ή ρυθμίζει τη μορφή TIFF του υπογεγραμμένου εγγράφου. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Λαμβάνει ή ορίζει εάν θα αντικατασταθεί το υπάρχον αρχείο με νέο αρχείο εξόδου. Διαφορετικά θα δημιουργηθεί νέο αρχείο με τον αριθμό ως επίθημα. Από προεπιλογή αυτή η τιμή έχει οριστεί σε true που σημαίνει ότι το αρχείο θα αντικατασταθεί. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Λαμβάνει ή ορίζει κωδικό πρόσβασης για την αποθήκευση υπογεγραμμένου εγγράφου με προστασία κωδικού πρόσβασης. Αυτή η ιδιότητα δεν υποστηρίζεται για έγγραφα εικόνας. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Λαμβάνει ή ρυθμίζει εάν θα χρησιμοποιείται κωδικός πρόσβασης από το LoadOptions για να αποθηκεύεται το υπογεγραμμένο έγγραφο ως προστατευμένο. Η προεπιλεγμένη τιμή είναι true. Αυτή η ιδιότητα δεν υποστηρίζεται για έγγραφα εικόνας. |

### Δείτε επίσης

* class [ImageSaveOptions](../imagesaveoptions)
* χώρος ονομάτων [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
