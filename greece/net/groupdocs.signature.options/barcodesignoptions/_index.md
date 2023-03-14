---
title: BarcodeSignOptions
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Αντιπροσωπεύει τις επιλογές υπογραφής Barcode.
type: docs
weight: 1260
url: /el/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Αντιπροσωπεύει τις επιλογές υπογραφής Barcode.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSignOptions με προεπιλεγμένες τιμές. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSignOptions με κείμενο. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeSignOptions με κείμενο. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Βάλτε υπογραφή σε όλες τις σελίδες του εγγράφου. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Πρόσθετη εμφάνιση υπογραφής. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις φόντου υπογραφής. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Καθορίστε ρυθμίσεις περιγράμματος |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Λαμβάνει ή ορίζει τη στοίχιση του κειμένου στην εικόνα γραμμικού κώδικα του αποτελέσματος. Η προεπιλεγμένη τιμή είναι Καμία. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Λάβετε ή ορίστε τον Τύπο εγγράφου των Επιλογών υπογραφής[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο γραμμικού κώδικα. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Επεκτάσεις υπογραφής. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Λαμβάνει ή ορίζει τη γραμματοσειρά της υπογραφής. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Λαμβάνει ή ορίζει το χρώμα Fore των γραμμών Barcode Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε το προσεκτικά. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας κειμένου για να βάλει την υπογραφή κειμένου σε αυτό. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για να βάλει την υπογραφή κειμένου σε αυτό. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField. Η τιμή από προεπιλογή είναι AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Ύψος υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) Ιδιότητα SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων Barcode και των περιγραμμάτων εικόνας του αποτελέσματος. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Αριστερά X θέση της υπογραφής στη σελίδα εγγράφου στις τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) Ιδιότητα LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η οριζόντια στοίχιση). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για ιδιότητες Left και Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Λαμβάνει ή ορίζει το διάστημα μεταξύ των άκρων του Σήματος και του Εγγράφου. (λειτουργεί ΜΟΝΟ εάν έχει καθοριστεί οριζόντια ή κατακόρυφη στοίχιση). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Λαμβάνει ή ορίζει το εγγενές χαρακτηριστικό. Εάν έχει οριστεί, θα μπορούσαν να χρησιμοποιηθούν συγκεκριμένες υπογραφές εγγράφου. Το εγγενές υδατογράφημα κειμένου για έγγραφα επεξεργασίας κειμένου είναι διαφορετικό από το κανονικό, για παράδειγμα. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. Η ελάχιστη και η προεπιλεγμένη τιμή είναι 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Επιλογές για τον καθορισμό σελίδων προς υπογραφή. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | Λαμβάνει ή ορίζει τη σημαία για τη λήψη περιεχομένου εικόνας γραμμικού κώδικα μιας υπογραφής που τοποθετήθηκε στη σελίδα εγγράφου. Εάν αυτή η σημαία οριστεί true, το περιεχόμενο εικόνας υπογραφής γραμμικού κώδικα θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας σύμφωνα με την απαιτούμενη μορφή[`ReturnContentType`](./returncontenttype) . Από προεπιλογή αυτή η επιλογή είναι απενεργοποιημένη. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής Barcode όταν είναι ενεργοποιημένη η ιδιότητα ReturnContent. Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει να επιστρέψετε το περιεχόμενο εικόνας Barcode στην αρχική μορφή. Αυτή η μορφή εικόνας καθορίζεται στο[`Format`](../../groupdocs.signature.domain/barcodesignature/format) Οι πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP. Εάν δεν υποστηρίζεται η παρεχόμενη μορφή, θα επιστραφεί περιεχόμενο εικόνας Barcode σε μορφή .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Γωνία περιστροφής υπογραφής στη σελίδα του εγγράφου (δεξιόστροφα). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο σχήματος για την τοποθέτηση κειμένου. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextStamp. Η τιμή από προεπιλογή είναι Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό της υπογραφής. Μπορεί να χρησιμοποιηθεί σε επιλογές επαλήθευσης υπογραφής. Η ιδιότητα υποστηρίζεται μόνο για έγγραφα Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Λαμβάνει ή ορίζει τον τύπο υλοποίησης της υπογραφής κειμένου. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Λάβετε τον τύπο υπογραφής[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width and Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Λειτουργία επέκτασης στη σελίδα εγγράφου. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Λαμβάνει ή ορίζει το κείμενο της υπογραφής. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Οριζόντια στοίχιση κειμένου μέσα σε μια υπογραφή. Αυτή η δυνατότητα υποστηρίζεται μόνο για εφαρμογές υπογραφής εικόνας και σχολιασμού (βλ.[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) Ιδιότητα SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Κάθετη στοίχιση κειμένου μέσα σε μια υπογραφή. Αυτή η δυνατότητα υποστηρίζεται μόνο για την υλοποίηση της υπογραφής εικόνας (βλ.[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) Ιδιότητα SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Επάνω Y Θέση υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype)Ιδιότητα LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η κατακόρυφη στοίχιση). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0,0 (αδιαφανή) έως 1,0 (καθαρή)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανές). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Κατακόρυφη στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Πλάτος υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) Ιδιότητα SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Λαμβάνει ή ορίζει τη θέση της τάξης Z της υπογραφής κειμένου. Καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Βασική χρήση της δημιουργίας ηλεκτρονικής υπογραφής Barcode από το GroupDocs. Υπογραφή: [Πώς να υπογράψετε έγγραφο με υπογραφή Barcode](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Προηγμένη χρήση των ρυθμίσεων της ηλεκτρονικής υπογραφής Barcode με GroupDocs.Υπογραφή: [Προηγμένη χρήση στο έγγραφο eSign με υπογραφή Barcode και πρόσθετες ρυθμίσεις](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### Δείτε επίσης

* class [TextSignOptions](../textsignoptions)
* χώρος ονομάτων [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
