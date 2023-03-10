---
title: ImageSearchOptions
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Αντιπροσωπεύει επιλογές αναζήτησης για υπογραφές εικόνας.
type: docs
weight: 1410
url: /el/net/groupdocs.signature.options/imagesearchoptions/
---
## ImageSearchOptions class

Αντιπροσωπεύει επιλογές αναζήτησης για υπογραφές εικόνας.

```csharp
public class ImageSearchOptions : SearchOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ImageSearchOptions](imagesearchoptions)() | Αρχικοποιεί μια νέα παρουσία της κλάσης ImageSearchOptions με προεπιλεγμένες τιμές. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Επισήμανση για αναζήτηση σε κάθε σελίδα Εγγράφου. Από προεπιλογή αυτή η τιμή έχει οριστεί σε true. |
| [MaxContentSize](../../groupdocs.signature.options/imagesearchoptions/maxcontentsize) { get; set; } | Για μη μηδενική τιμή αυτή η σημαία καθορίζει το μέγιστο μέγεθος των εικόνων για κριτήρια αναζήτησης. Από προεπιλογή αυτή η σημαία έχει οριστεί στο μηδέν και δεν επηρεάζει το αποτέλεσμα αναζήτησης. |
| [MinContentSize](../../groupdocs.signature.options/imagesearchoptions/mincontentsize) { get; set; } | Για μη μηδενική τιμή αυτή η σημαία καθορίζει το ελάχιστο μέγεθος εικόνων για κριτήρια αναζήτησης. Από προεπιλογή αυτή η σημαία έχει οριστεί στο μηδέν και δεν επηρεάζει το αποτέλεσμα αναζήτησης. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για αναζήτηση. Η τιμή είναι προαιρετική. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Επιλογές για τον καθορισμό σελίδων για αναζήτηση υπογραφής. |
| [ReturnContent](../../groupdocs.signature.options/imagesearchoptions/returncontent) { get; set; } | Λαμβάνει ή ορίζει τη σημαία για να συλλάβει το περιεχόμενο εικόνας της υπογραφής στη σελίδα εγγράφου. Εάν αυτή η σημαία οριστεί true, το περιεχόμενο υπογραφής εικόνας θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας σύμφωνα με την απαιτούμενη μορφή[`ReturnContentType`](./returncontenttype) . Από προεπιλογή αυτή η επιλογή είναι απενεργοποιημένη. |
| [ReturnContentType](../../groupdocs.signature.options/imagesearchoptions/returncontenttype) { get; set; } | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου της υπογραφής εικόνας όταν είναι ενεργοποιημένη η ιδιότητα ReturnContent. Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει να επιστρέψετε το περιεχόμενο εικόνας στην αρχική μορφή. Αυτή η μορφή εικόνας καθορίζεται στο[`Format`](../../groupdocs.signature.domain/imagesignature/format) Οι πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP. Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, θα επιστραφεί το περιεχόμενο εικόνας στην αρχική μορφή. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Επισημάνετε για να επιστρέψετε μόνο υπογραφές που επισημαίνονται ως IsSignature. Από προεπιλογή η τιμή είναι false που υποδεικνύει την επιστροφή όλων των υπογραφών που ταιριάζουν με καθορισμένα κριτήρια. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Βασική χρήση αναζήτησης για την ηλεκτρονική υπογραφή εικόνας από το GroupDocs.Υπογραφή: [ Πώς να κάνετε eSearch υπογραφές εικόνας σε ένα έγγραφο](https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures)
* Προηγμένη χρήση των ρυθμίσεων αναζήτησης για την ηλεκτρονική υπογραφή εικόνας με GroupDocs.Υπογραφή: [Προηγμένη χρήση των υπογραφών εικόνων eSearch σε ένα έγγραφο και πρόσθετες ρυθμίσεις](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures)

### Δείτε επίσης

* class [SearchOptions](../searchoptions)
* χώρος ονομάτων [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->