---
title: "StampSignOptions"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Αναπαριστά τις επιλογές υπογραφής Σφραγίδας."
type: docs
weight: 2000
url: /el/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Αναπαριστά τις επιλογές υπογραφής Σφραγίδας.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης StampSignOptions με προεπιλεγμένες τιμές. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης StampSignOptions με επιλογές στοίχισης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Τοποθετήστε την υπογραφή σε όλες τις σελίδες του εγγράφου. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Πρόσθετη εμφάνιση υπογραφής. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Λαμβάνει ή ορίζει το φόντο του Σφραγίδας. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο περικοπής χρώματος φόντου της υπογραφής. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο περικοπής εικόνας φόντου της υπογραφής. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Καθορίστε τις ρυθμίσεις περιγράμματος |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Λάβετε ή ορίστε τον Τύπο Εγγράφου των Επιλογών Υπογραφής [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Επεκτάσεις Υπογραφής. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Λαμβάνει ή ορίζει τον αλγόριθμο κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες. Υποστηρίζεται αποκλειστικά για ψηφιακές υπογραφές σε αρχεία PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Ύψος της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υπογραφής. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Λαμβάνει ή ορίζει τη ροή εικόνας υπογραφής. Εάν αυτή η ιδιότητα έχει καθοριστεί, χρησιμοποιείται πάντα αντί του ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Λίστα εσωτερικών γραμμών που αποδίδονται ως σύνολο ορθογωνίων. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί οριζόντια στοίχιση). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Τύπος μέτρησης (pixels, percents ή millimeters) για τις ιδιότητες Left και Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Λαμβάνει ή ορίζει το κενό μεταξύ της Υπογραφής και των άκρων του Εγγράφου. (λειτουργεί ΜΟΝΟ εάν έχουν καθοριστεί οριζόντια ή κάθετη στοίχιση). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Περιθώριο. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Λίστα εξωτερικών γραμμών που αποδίδονται ως συνεφαπτόμενοι κύκλοι. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. Η ελάχιστη και προεπιλεγμένη τιμή είναι 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Ορθογώνιο της περιοχής για τοποθέτηση της εικόνας στο έγγραφο. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Γωνία περιστροφής της υπογραφής στη σελίδα του εγγράφου (δεξιόστροφα). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Αποκτήστε τον Τύπο Υπογραφής [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Τύπος μέτρησης (pixels, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο σφραγίδας. Η προεπιλεγμένη τιμή είναι Στρογγυλή. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Λειτουργία τέντωσης στο Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί κάθετη στοίχιση). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0,0 (αδιαφανής) έως 1,0 (διαυγής)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανής). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Κάθετη στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Πλάτος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Λαμβάνει ή ορίζει τη θέση Z-order της υπογραφής κειμένου. Καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Καθαρίζει τους εσωτερικούς πόρους |

### Παρατηρήσεις

**Learn more**

* Basic usage of creating Stamp electronic signature by GroupDocs.Signature: [How to eSign document with Stamp signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Stamp signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Δείτε επίσης

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
