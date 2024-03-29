---
title: ImageSaveOptions
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Αποθήκευση επιλογών για έγγραφα εικόνας.
type: docs
weight: 1400
url: /el/net/groupdocs.signature.options/imagesaveoptions/
---
## ImageSaveOptions class

Αποθήκευση επιλογών για έγγραφα εικόνας.

```csharp
public class ImageSaveOptions : SaveOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης ImagesSaveOptions με προεπιλεγμένες τιμές. |
| [ImageSaveOptions](imagesaveoptions#constructor_1)(bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης ImagesSaveOptions με σημαία αντικατάστασης. |
| [ImageSaveOptions](imagesaveoptions#constructor_2)(ImageSaveFileFormat, bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης ImagesSaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Λαμβάνει ή ορίζει τη σημαία για αυτόματη προσθήκη επέκτασης όταν έλειπε στο αρχείο εξόδου path Η προεπιλεγμένη τιμή είναι false. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Λαμβάνει ή ορίζει εάν θα αντικατασταθεί το υπάρχον αρχείο με νέο αρχείο εξόδου. Διαφορετικά θα δημιουργηθεί νέο αρχείο με τον αριθμό ως επίθημα. Από προεπιλογή αυτή η τιμή έχει οριστεί σε true που σημαίνει ότι το αρχείο θα αντικατασταθεί. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Λαμβάνει ή ορίζει κωδικό πρόσβασης για την αποθήκευση υπογεγραμμένου εγγράφου με προστασία κωδικού πρόσβασης. Αυτή η ιδιότητα δεν υποστηρίζεται για έγγραφα εικόνας. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Λαμβάνει ή ρυθμίζει εάν θα χρησιμοποιείται κωδικός πρόσβασης από το LoadOptions για να αποθηκεύεται το υπογεγραμμένο έγγραφο ως προστατευμένο. Η προεπιλεγμένη τιμή είναι true. Αυτή η ιδιότητα δεν υποστηρίζεται για έγγραφα εικόνας. |

### Δείτε επίσης

* class [SaveOptions](../saveoptions)
* χώρος ονομάτων [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
