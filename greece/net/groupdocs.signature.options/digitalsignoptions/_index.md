---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Αναπαριστά τις επιλογές Ψηφιακής υπογραφής."
type: docs
weight: 1560
url: /el/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Αναπαριστά τις επιλογές Ψηφιακής υπογραφής.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με προεπιλεγμένες τιμές. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού και ροή εικόνας. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με ροή πιστοποιητικού και αρχείο εικόνας. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και ροή εικόνας. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης DigitalSignOptions με αρχείο πιστοποιητικού και αρχείο εικόνας. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Λαμβάνει ή ορίζει μια σημαία που επιτρέπει την υπογραφή με πιστοποιητικό του οποίου η περίοδος ισχύος έχει λήξει. Η προεπιλεγμένη τιμή είναι false: η υπογραφή με ληγμένο πιστοποιητικό προκαλεί εξαίρεση [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), και το έγγραφο δεν υπογράφεται. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Λαμβάνει ή ορίζει μια σημαία που επιτρέπει την υπογραφή με πιστοποιητικό του οποίου η περίοδος ισχύος δεν έχει αρχίσει ακόμη. Η προεπιλεγμένη τιμή είναι false: η υπογραφή με τέτοιο πιστοποιητικό προκαλεί εξαίρεση [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), και το έγγραφο δεν υπογράφεται. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Τοποθετήστε την υπογραφή σε όλες τις σελίδες του εγγράφου. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Πρόσθετη εμφάνιση υπογραφής. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Καθορίστε τις ρυθμίσεις περιγράμματος |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου ψηφιακού πιστοποιητικού. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει οριστεί CertificateStream. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Λαμβάνει ή ορίζει τη ροή ψηφιακού πιστοποιητικού. Εάν αυτή η ιδιότητα οριστεί, χρησιμοποιείται πάντα αντί για CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Λαμβάνει ή ορίζει την επαφή της υπογραφής. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Λαμβάνει ή ορίζει μια προσαρμοσμένη συνάρτηση υπογραφής hash, επιτρέποντας στους χρήστες να υλοποιήσουν τη δική τους λογική ψηφιακής υπογραφής. Αυτό επιτρέπει την υπογραφή με εξωτερικά πιστοποιητικά και υποστηρίζει διαφορετικούς αλγόριθμους hash. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Λάβετε ή ορίστε τον Τύπο Εγγράφου των Επιλογών Υπογραφής [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Επεκτάσεις Υπογραφής. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Λαμβάνει ή ορίζει τον αλγόριθμο κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες. Υποστηρίζεται αποκλειστικά για ψηφιακές υπογραφές σε αρχεία PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Ύψος της υπογραφής στη σελίδα του εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Οριζόντια στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υπογραφής. Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Λαμβάνει ή ορίζει τη ροή εικόνας υπογραφής. Εάν αυτή η ιδιότητα έχει καθοριστεί, χρησιμοποιείται πάντα αντί του ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί οριζόντια στοίχιση). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Λαμβάνει ή ορίζει τη θέση της υπογραφής. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Τύπος μέτρησης (pixels, percents ή millimeters) για τις ιδιότητες Left και Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Λαμβάνει ή ορίζει το κενό μεταξύ της Υπογραφής και των άκρων του Εγγράφου. (λειτουργεί ΜΟΝΟ εάν έχουν καθοριστεί οριζόντια ή κάθετη στοίχιση). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Περιθώριο. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. Η ελάχιστη και προεπιλεγμένη τιμή είναι 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης του ψηφιακού πιστοποιητικού. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Λαμβάνει ή ορίζει το λόγο της υπογραφής. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Ορθογώνιο της περιοχής για τοποθέτηση της εικόνας στο έγγραφο. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Γωνία περιστροφής της υπογραφής στη σελίδα του εγγράφου (δεξιόστροφα). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου. Διαθέσιμο μόνο για έγγραφα Word. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Λαμβάνει ή ορίζει τις ιδιότητες της ψηφιακής υπογραφής εγγράφου. Για την υπογραφή εγγράφων Pdf είναι δυνατόν να οριστούν προχωρημένες ιδιότητες χρησιμοποιώντας το παράδειγμα του [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Αποκτήστε τον Τύπο Υπογραφής [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Τύπος μέτρησης (pixels, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Λειτουργία τέντωσης στο Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί κάθετη στοίχιση). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0,0 (αδιαφανής) έως 1,0 (διαυγής)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανής). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Λαμβάνει/ορίζει τη σημαία επαλήθευσης ltv (Long Term Validation). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Κάθετη στοίχιση της υπογραφής στη σελίδα του εγγράφου. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Λαμβάνει ή ορίζει την ορατότητα της υπογραφής. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Πλάτος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | Τύπος XAdES [`XAdESType`](./xadestype). Η προεπιλεγμένη τιμή είναι None (το XAdES είναι απενεργοποιημένο). Αυτή τη στιγμή ο τύπος υπογραφής XAdES υποστηρίζεται μόνο για έγγραφα Spreadsheet. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Λαμβάνει ή ορίζει τη θέση Z-order της υπογραφής κειμένου. Καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Καθαρίζει τους εσωτερικούς πόρους |

### Παρατηρήσεις

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Δείτε επίσης

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
