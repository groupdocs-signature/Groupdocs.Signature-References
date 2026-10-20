---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Αναπαριστά τις επιλογές υπογραφής QRCode."
type: docs
weight: 1920
url: /el/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Αναπαριστά τις επιλογές υπογραφής QR-Code.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSignOptions με προεπιλεγμένες τιμές. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSignOptions με κείμενο. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BarcodeSignOptions με κείμενο. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Τοποθετήστε την υπογραφή σε όλες τις σελίδες του εγγράφου. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Πρόσθετη εμφάνιση υπογραφής. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις φόντου της υπογραφής. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Καθορίστε τις ρυθμίσεις περιγράμματος |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Αποκτά ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα QR-code. Η προεπιλεγμένη τιμή είναι None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Αποκτά ή ορίζει προσαρμοσμένο αντικείμενο για σειριοποίηση στο περιεχόμενο QR-Code. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Λάβετε ή ορίστε τον Τύπο Εγγράφου των Επιλογών Υπογραφής [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο QR-Code. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Επεκτάσεις Υπογραφής. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Λαμβάνει ή ορίζει τη γραμματοσειρά της υπογραφής. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Λαμβάνει ή ορίζει το χρώμα Fore των μπαρών QR-Code. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε το προσεκτικά. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Λαμβάνει ή ορίζει τον τίτλο του πεδίου κειμένου φόρμας για την τοποθέτηση της υπογραφής κειμένου. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για την τοποθέτηση της υπογραφής κειμένου. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField. Η προεπιλεγμένη τιμή είναι AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Λαμβάνει ή ορίζει τον αλγόριθμο κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες. Υποστηρίζεται αποκλειστικά για ψηφιακές υπογραφές σε αρχεία PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Ύψος της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixels, percents or millimeters, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) ιδιότητα SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων QR-Code και των ορίων της τελικής εικόνας. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) ιδιότητα LocationMeasureType). (λειτουργεί εάν η οριζόντια στοίχιση δεν έχει καθοριστεί). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Τύπος μέτρησης (pixels, percents ή millimeters) για τις ιδιότητες Left και Top. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Λαμβάνει ή ορίζει το όνομα αρχείου εικόνας λογότυπου QR-code. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το LogoStream. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε το προσεκτικά. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Λαμβάνει ή ορίζει τη ροή εικόνας λογότυπου QR-code. Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί του LogoFilePath. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε το προσεκτικά. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Λαμβάνει ή ορίζει το κενό μεταξύ της Υπογραφής και των άκρων του Εγγράφου. (λειτουργεί ΜΟΝΟ εάν έχουν καθοριστεί οριζόντια ή κάθετη στοίχιση). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Περιθώριο. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Λαμβάνει ή ορίζει το εγγενές χαρακτηριστικό. Εάν έχει οριστεί, μπορούν να χρησιμοποιηθούν υπογραφές ειδικές για το έγγραφο. Το εγγενές υδατογράφημα κειμένου για έγγραφα WordProcessing είναι διαφορετικό από το κανονικό, για παράδειγμα. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. Η ελάχιστη και προεπιλεγμένη τιμή είναι 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας υπογραφής QR-Code θα διατηρεί τα ακατέργαστα δεδομένα εικόνας με τη ζητούμενη μορφή [`ReturnContentType`](./returncontenttype). Από προεπιλογή αυτή η επιλογή είναι απενεργοποιημένη. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι θα επιστρέφεται το περιεχόμενο εικόνας QR-Code στην αρχική μορφή. Αυτή η μορφή εικόνας καθορίζεται στο [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). Οι πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP. Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο εικόνας QR-Code θα επιστραφεί σε μορφή .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Γωνία περιστροφής της υπογραφής στη σελίδα του εγγράφου (δεξιόστροφα). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο σχήματος για τοποθέτηση κειμένου. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextStamp. Η προεπιλεγμένη τιμή είναι Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Λαμβάνει ή ορίζει το μοναδικό ID της υπογραφής. Μπορεί να χρησιμοποιηθεί στις επιλογές επαλήθευσης υπογραφής. Η ιδιότητα υποστηρίζεται μόνο για έγγραφα Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Λαμβάνει ή ορίζει τον τύπο υλοποίησης κειμενικής υπογραφής. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Αποκτήστε τον Τύπο Υπογραφής [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Τύπος μέτρησης (pixels, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Λειτουργία τέντωσης στο Document Page. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Λαμβάνει ή ορίζει το κείμενο της υπογραφής. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Οριζόντια στοίχιση του κειμένου μέσα σε μια υπογραφή. Αυτή η δυνατότητα υποστηρίζεται μόνο για υλοποιήσεις υπογραφής Image και Annotation (δείτε [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) ιδιότητα SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Κάθετη στοίχιση του κειμένου μέσα σε μια υπογραφή. Αυτή η δυνατότητα υποστηρίζεται μόνο για υλοποίηση υπογραφής Image (δείτε [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) ιδιότητα SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) ιδιότητα LocationMeasureType). (λειτουργεί εάν η κάθετη στοίχιση δεν έχει καθοριστεί). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0,0 (αδιαφανής) έως 1,0 (διαυγής)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανής). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Κάθετη στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Πλάτος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) ιδιότητα SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Λαμβάνει ή ορίζει τη θέση Z-order της υπογραφής κειμένου. Καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. |

### Παρατηρήσεις

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Δείτε επίσης

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
