---
title: DigitalSignOptions
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Αντιπροσωπεύει τις επιλογές ψηφιακής υπογραφής.
type: docs
weight: 1340
url: /el/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Αντιπροσωπεύει τις επιλογές ψηφιακής υπογραφής.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalSignOptions με προεπιλεγμένες τιμές. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalSignOptions με ροή πιστοποιητικού. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalSignOptions με ροή πιστοποιητικού και ροή εικόνας. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalSignOptions με ροή πιστοποιητικού και αρχείο εικόνας. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και ροή εικόνας. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Αρχικοποιεί μια νέα παρουσία της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και αρχείο εικόνας. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Τοποθετήστε υπογραφή σε όλες τις σελίδες του εγγράφου. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο για μορφές εικόνας πολλαπλών καρέ (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Πρόσθετη εμφάνιση υπογραφής. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Καθορίστε ρυθμίσεις περιγράμματος |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου ψηφιακού πιστοποιητικού. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί CertificateStream. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Λαμβάνει ή ρυθμίζει τη ροή ψηφιακού πιστοποιητικού. Εάν αυτή η ιδιότητα έχει καθοριστεί, χρησιμοποιείται πάντα στη θέση CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Λαμβάνει ή ορίζει την επαφή υπογραφής. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Λάβετε ή ορίστε τον Τύπο εγγράφου των Επιλογών υπογραφής[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Επεκτάσεις υπογραφής. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Ύψος υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Λαμβάνει ή ορίζει τη διαδρομή αρχείου εικόνας υπογραφής. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Λαμβάνει ή ορίζει τη ροή εικόνας υπογραφής. Εάν αυτή η ιδιότητα έχει καθοριστεί, χρησιμοποιείται πάντα αντί για ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Αριστερά X θέση της υπογραφής στη σελίδα εγγράφου στις τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η οριζόντια στοίχιση). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Λαμβάνει ή ορίζει τη θέση υπογραφής. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για ιδιότητες Left και Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Λαμβάνει ή ορίζει το διάστημα μεταξύ των άκρων του Σήματος και του Εγγράφου. (λειτουργεί ΜΟΝΟ εάν έχει καθοριστεί οριζόντια ή κατακόρυφη στοίχιση). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. Η ελάχιστη και η προεπιλεγμένη τιμή είναι 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Επιλογές για τον καθορισμό σελίδων προς υπογραφή. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης του ψηφιακού πιστοποιητικού. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Παίρνει ή ορίζει τον λόγο υπογραφής. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Ορθογώνιο περιοχής για να τοποθετήσετε την εικόνα στο έγγραφο. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Γωνία περιστροφής υπογραφής στη σελίδα του εγγράφου (δεξιόστροφα). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Λαμβάνει ή ορίζει ιδιότητες της ψηφιακής υπογραφής εγγράφου. Για την υπογραφή εγγράφων Pdf είναι δυνατός ο ορισμός σύνθετων ιδιοτήτων χρησιμοποιώντας το παράδειγμα του[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Λάβετε τον τύπο υπογραφής[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width and Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Λειτουργία επέκτασης στη σελίδα εγγράφου. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Επάνω Y Θέση υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η κατακόρυφη στοίχιση). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0,0 (αδιαφανή) έως 1,0 (καθαρή)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανές). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Κατακόρυφη στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Λαμβάνει ή ορίζει την ορατότητα της υπογραφής. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Πλάτος υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | τύπος XAdES[`XAdESType`](./xadestype) . Η προεπιλεγμένη τιμή είναι Κανένα (το XAdES είναι απενεργοποιημένο). Αυτή τη στιγμή ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα υπολογιστικού φύλλου. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Λαμβάνει ή ορίζει τη θέση της τάξης Z της υπογραφής κειμένου. Καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Διαγράφει εσωτερικούς πόρους |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Βασική χρήση της δημιουργίας ψηφιακής ηλεκτρονικής υπογραφής από το GroupDocs. Υπογραφή: [Πώς να υπογράψετε έγγραφο με ψηφιακή υπογραφή](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Προηγμένη χρήση ρυθμίσεων ψηφιακής ηλεκτρονικής υπογραφής με GroupDocs.Υπογραφή: [Προηγμένη χρήση στο έγγραφο eSign με ψηφιακή υπογραφή και πρόσθετες ρυθμίσεις](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Δείτε επίσης

* class [ImageSignOptions](../imagesignoptions)
* χώρος ονομάτων [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
