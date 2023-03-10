---
title: TextSignOptions
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Αντιπροσωπεύει τις επιλογές υπογραφής κειμένου.
type: docs
weight: 1730
url: /el/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

Αντιπροσωπεύει τις επιλογές υπογραφής κειμένου.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης TextSignOptions με προεπιλεγμένες τιμές. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης TextSignOptions με κείμενο. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Βάλτε υπογραφή σε όλες τις σελίδες του εγγράφου. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Πρόσθετη εμφάνιση υπογραφής. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις φόντου υπογραφής. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Καθορίστε ρυθμίσεις περιγράμματος |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Λάβετε ή ορίστε τον Τύπο εγγράφου των Επιλογών υπογραφής[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Επεκτάσεις υπογραφής. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Λαμβάνει ή ορίζει τη γραμματοσειρά της υπογραφής. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Παίρνει ή ορίζει το πρώτο χρώμα της υπογραφής. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας κειμένου για να βάλει την υπογραφή κειμένου σε αυτό. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για να βάλει την υπογραφή κειμένου σε αυτό. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField. Η τιμή από προεπιλογή είναι AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Ύψος υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) Ιδιότητα SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Αριστερά X θέση της υπογραφής στη σελίδα εγγράφου στις τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά βλ.[`MeasureType`](../../groupdocs.signature.domain/measuretype) Ιδιότητα LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η οριζόντια στοίχιση). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για ιδιότητες Left και Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Λαμβάνει ή ορίζει το διάστημα μεταξύ των άκρων του Σήματος και του Εγγράφου. (λειτουργεί ΜΟΝΟ εάν έχει καθοριστεί οριζόντια ή κατακόρυφη στοίχιση). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Λαμβάνει ή ορίζει το εγγενές χαρακτηριστικό. Εάν έχει οριστεί, θα μπορούσαν να χρησιμοποιηθούν συγκεκριμένες υπογραφές εγγράφου. Το εγγενές υδατογράφημα κειμένου για έγγραφα επεξεργασίας κειμένου είναι διαφορετικό από το κανονικό, για παράδειγμα. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. Η ελάχιστη και η προεπιλεγμένη τιμή είναι 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Επιλογές για τον καθορισμό σελίδων προς υπογραφή. |
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

* Βασική χρήση της δημιουργίας ηλεκτρονικής υπογραφής κειμένου από το GroupDocs. Υπογραφή: [Πώς να υπογράψετε έγγραφο με υπογραφή κειμένου](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* Προηγμένη χρήση των ρυθμίσεων της ηλεκτρονικής υπογραφής κειμένου με το GroupDocs.Υπογραφή: [Προηγμένη χρήση στο έγγραφο eSign με υπογραφή κειμένου και πρόσθετες ρυθμίσεις](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### Δείτε επίσης

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* χώρος ονομάτων [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
