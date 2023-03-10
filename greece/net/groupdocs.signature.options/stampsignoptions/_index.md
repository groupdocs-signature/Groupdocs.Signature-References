---
title: StampSignOptions
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Αντιπροσωπεύει τις επιλογές υπογραφής σφραγίδας.
type: docs
weight: 1710
url: /el/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Αντιπροσωπεύει τις επιλογές υπογραφής σφραγίδας.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης StampSignOptions με προεπιλεγμένες τιμές. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης StampSignOptions με επιλογές στοίχισης. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Τοποθετήστε υπογραφή σε όλες τις σελίδες του εγγράφου. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο για μορφές εικόνας πολλαπλών καρέ (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Πρόσθετη εμφάνιση υπογραφής. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Λαμβάνει ή ορίζει το φόντο της σφραγίδας. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο υπογραφής περικοπής χρώματος φόντου. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο υπογραφής περικοπής εικόνας φόντου. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Καθορίστε ρυθμίσεις περιγράμματος |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Λάβετε ή ορίστε τον Τύπο εγγράφου των Επιλογών υπογραφής[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Επεκτάσεις υπογραφής. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Ύψος υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Λαμβάνει ή ορίζει τη διαδρομή αρχείου εικόνας υπογραφής. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Λαμβάνει ή ορίζει τη ροή εικόνας υπογραφής. Εάν αυτή η ιδιότητα έχει καθοριστεί, χρησιμοποιείται πάντα αντί για ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Λίστα εσωτερικών γραμμών που αποδίδονται ως σύνολο ορθογωνίων. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Αριστερά X θέση της υπογραφής στη σελίδα εγγράφου στις τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η οριζόντια στοίχιση). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για ιδιότητες Left και Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Λαμβάνει ή ορίζει το διάστημα μεταξύ των άκρων του Σήματος και του Εγγράφου. (λειτουργεί ΜΟΝΟ εάν έχει καθοριστεί οριζόντια ή κατακόρυφη στοίχιση). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Margin. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Λίστα εξωτερικών γραμμών που αποδίδονται ως ομόκεντροι κύκλοι. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. Η ελάχιστη και η προεπιλεγμένη τιμή είναι 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Επιλογές για τον καθορισμό σελίδων προς υπογραφή. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Ορθογώνιο περιοχής για να τοποθετήσετε την εικόνα στο έγγραφο. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Γωνία περιστροφής υπογραφής στη σελίδα του εγγράφου (δεξιόστροφα). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Λάβετε τον τύπο υπογραφής[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width and Height. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο σφραγίδας. Η τιμή από προεπιλογή είναι Round. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Λειτουργία επέκτασης στη σελίδα εγγράφου. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Επάνω Y Θέση υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η κατακόρυφη στοίχιση). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0,0 (αδιαφανή) έως 1,0 (καθαρή)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανές). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Κατακόρυφη στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Πλάτος υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Λαμβάνει ή ορίζει τη θέση της τάξης Z της υπογραφής κειμένου. Καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Διαγράφει εσωτερικούς πόρους |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Βασική χρήση δημιουργίας ηλεκτρονικής υπογραφής σφραγίδας από το GroupDocs. Υπογραφή: [Πώς να υπογράψετε έγγραφο με υπογραφή σφραγίδας](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Προηγμένη χρήση των ρυθμίσεων της ηλεκτρονικής υπογραφής σφραγίδα με GroupDocs.Υπογραφή: [Προηγμένη χρήση στο έγγραφο eSign με υπογραφή σφραγίδας και πρόσθετες ρυθμίσεις](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Δείτε επίσης

* class [ImageSignOptions](../imagesignoptions)
* χώρος ονομάτων [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
