---
title: "TextSignOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής κειμένου."
type: docs
weight: 18
url: /el/nodejs-java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Αντιπροσωπεύει τις επιλογές υπογραφής κειμένου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextSignOptions()](#TextSignOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SignTextOptions με προεπιλεγμένες τιμές. |
| [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SignTextOptions με κείμενο. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLeft()](#getLeft--) | Αριστερή θέση X της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα LocationMeasureType). |
| [setLeft(int value)](#setLeft-int-) | Αριστερή θέση X της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα LocationMeasureType). |
| [getTop()](#getTop--) | Άνω θέση Y της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα LocationMeasureType). |
| [setTop(int value)](#setTop-int-) | Άνω θέση Y της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα LocationMeasureType). |
| [getWidth()](#getWidth--) | Πλάτος της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα SizeMeasureType). |
| [setWidth(int value)](#setWidth-int-) | Πλάτος της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα SizeMeasureType). |
| [getHeight()](#getHeight--) | Ύψος της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα SizeMeasureType). |
| [setHeight(int value)](#setHeight-int-) | Ύψος της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα SizeMeasureType). |
| [getLocationMeasureType()](#getLocationMeasureType--) | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Left και Top. |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Left και Top. |
| [getSizeMeasureType()](#getSizeMeasureType--) | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
| [getStretch()](#getStretch--) | Λειτουργία τέντωσης στη σελίδα εγγράφου. |
| [setStretch(int value)](#setStretch-int-) | Λειτουργία τέντωσης στη σελίδα εγγράφου. |
| [getRotationAngle()](#getRotationAngle--) | Γωνία περιστροφής της υπογραφής στη σελίδα εγγράφου (δεξιόστροφα). |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Γωνία περιστροφής της υπογραφής στη σελίδα εγγράφου (δεξιόστροφα). |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Οριζόντια στοίχιση της υπογραφής στη σελίδα εγγράφου. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Οριζόντια στοίχιση της υπογραφής στη σελίδα εγγράφου. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Κάθετη στοίχιση της υπογραφής στη σελίδα εγγράφου. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Κάθετη στοίχιση της υπογραφής στη σελίδα εγγράφου. |
| [getMargin()](#getMargin--) | Λαμβάνει ή ορίζει το διάστημα μεταξύ του Sign και των άκρων του Document. |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Λαμβάνει ή ορίζει το διάστημα μεταξύ του Sign και των άκρων του Document. |
| [getMarginMeasureType()](#getMarginMeasureType--) | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixels, percents ή millimeters) για το Margin. |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixels, percents ή millimeters) για το Margin. |
| [getTransparency()](#getTransparency--) | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0.0 (αδιαφανής) έως 1.0 (διαυγής)). |
| [setTransparency(double value)](#setTransparency-double-) | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0.0 (αδιαφανής) έως 1.0 (διαυγής)). |
| [getText()](#getText--) | Λαμβάνει ή ορίζει το κείμενο της υπογραφής. |
| [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή ορίζει το κείμενο της υπογραφής. |
| [getFont()](#getFont--) | Λαμβάνει ή ορίζει τη γραμματοσειρά της υπογραφής. |
| [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Λαμβάνει ή ορίζει τη γραμματοσειρά της υπογραφής. |
| [getForeColor()](#getForeColor--) | Λαμβάνει ή ορίζει το χρώμα κειμένου της υπογραφής. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα κειμένου της υπογραφής. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Λαμβάνει ή ορίζει τον τύπο υλοποίησης κειμενικής υπογραφής. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Λαμβάνει ή ορίζει τον τύπο υλοποίησης κειμενικής υπογραφής. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Οριζόντια στοίχιση του κειμένου μέσα σε μια υπογραφή. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Οριζόντια στοίχιση του κειμένου μέσα σε μια υπογραφή. |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Κατακόρυφη στοίχιση του κειμένου μέσα σε μια υπογραφή. |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Κατακόρυφη στοίχιση του κειμένου μέσα σε μια υπογραφή. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας κειμένου για την τοποθέτηση της υπογραφής κειμένου σε αυτό. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας κειμένου για την τοποθέτηση της υπογραφής κειμένου σε αυτό. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για την τοποθέτηση της υπογραφής κειμένου σε αυτό. |
| [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για την τοποθέτηση της υπογραφής κειμένου σε αυτό. |
| [getShapeType()](#getShapeType--) | Λαμβάνει ή ορίζει τον τύπο του σχήματος για την τοποθέτηση του κειμένου. |
| [setShapeType(int value)](#setShapeType-int-) | Λαμβάνει ή ορίζει τον τύπο του σχήματος για την τοποθέτηση του κειμένου. |
| [getSignatureID()](#getSignatureID--) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό της υπογραφής. |
| [setSignatureID(int value)](#setSignatureID-int-) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό της υπογραφής. |
| [getBorder()](#getBorder--) | Καθορίστε τις ρυθμίσεις περιγράμματος |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Καθορίστε τις ρυθμίσεις περιγράμματος |
| [getBackground()](#getBackground--) | Λαμβάνει ή ορίζει τις ρυθμίσεις φόντου της υπογραφής. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Λαμβάνει ή ορίζει τις ρυθμίσεις φόντου της υπογραφής. |
| [getNative()](#getNative--) | Λαμβάνει ή ορίζει το εγγενές χαρακτηριστικό. |
| [setNative(boolean value)](#setNative-boolean-) | Λαμβάνει ή ορίζει το εγγενές χαρακτηριστικό. |
| [getShapePosition()](#getShapePosition--) | Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου. |
| [setShapePosition(int value)](#setShapePosition-int-) | Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου. |
| [validate()](#validate--) | Εσωτερική μέθοδος για την επικύρωση των παραμέτρων επιλογών. |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά. |
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SignTextOptions με προεπιλεγμένες τιμές.

### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SignTextOptions με κείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο υπογραφής. |

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η οριζόντια στοίχιση).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η οριζόντια στοίχιση).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η κατακόρυφη στοίχιση).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα LocationMeasureType). (λειτουργεί εάν δεν έχει καθοριστεί η κατακόρυφη στοίχιση).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Πλάτος της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα SizeMeasureType).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Πλάτος της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα SizeMeasureType).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ύψος της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα SizeMeasureType).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ύψος της υπογραφής στη σελίδα εγγράφου σε τιμές μέτρησης (pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) ιδιότητα SizeMeasureType).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Left και Top.

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Left και Top.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height.

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Λειτουργία τέντωσης στη σελίδα εγγράφου.

**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Λειτουργία τέντωσης στη σελίδα εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Γωνία περιστροφής της υπογραφής στη σελίδα εγγράφου (δεξιόστροφα).

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Γωνία περιστροφής της υπογραφής στη σελίδα εγγράφου (δεξιόστροφα).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Οριζόντια στοίχιση της υπογραφής στη σελίδα εγγράφου.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Οριζόντια στοίχιση της υπογραφής στη σελίδα εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Κάθετη στοίχιση της υπογραφής στη σελίδα εγγράφου.

**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Κάθετη στοίχιση της υπογραφής στη σελίδα εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ του Sign και των άκρων του Document. (λειτουργεί ΜΟΝΟ εάν έχουν οριστεί η οριζόντια ή η κάθετη στοίχιση).

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ του Sign και των άκρων του Document. (λειτουργεί ΜΟΝΟ εάν έχουν οριστεί η οριζόντια ή η κάθετη στοίχιση).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixels, percents ή millimeters) για το Margin.

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixels, percents ή millimeters) για το Margin.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0.0 (αδιαφανής) έως 1.0 (διαυγής)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανής).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0.0 (αδιαφανής) έως 1.0 (διαυγής)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανής).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getText() {#getText--}
```
public final String getText()
```


Λαμβάνει ή ορίζει το κείμενο της υπογραφής.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Λαμβάνει ή ορίζει το κείμενο της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Λαμβάνει ή ορίζει τη γραμματοσειρά της υπογραφής.

**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Λαμβάνει ή ορίζει τη γραμματοσειρά της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Λαμβάνει ή ορίζει το χρώμα κειμένου της υπογραφής.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα κειμένου της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Λαμβάνει ή ορίζει τον τύπο υλοποίησης κειμενικής υπογραφής.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Λαμβάνει ή ορίζει τον τύπο υλοποίησης κειμενικής υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Οριζόντια στοίχιση του κειμένου μέσα σε μια υπογραφή. Αυτή η δυνατότητα υποστηρίζεται μόνο για υλοποιήσεις υπογραφών Εικόνας και Σχόλιου (δείτε [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) ιδιότητα SignatureImplementation).

**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Οριζόντια στοίχιση του κειμένου μέσα σε μια υπογραφή. Αυτή η δυνατότητα υποστηρίζεται μόνο για υλοποιήσεις υπογραφών Εικόνας και Σχόλιου (δείτε [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) ιδιότητα SignatureImplementation).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Κατακόρυφη στοίχιση του κειμένου μέσα σε μια υπογραφή. Αυτή η δυνατότητα υποστηρίζεται μόνο για υλοποίηση υπογραφής Εικόνας (δείτε [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) ιδιότητα SignatureImplementation).

**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Κατακόρυφη στοίχιση του κειμένου μέσα σε μια υπογραφή. Αυτή η δυνατότητα υποστηρίζεται μόνο για υλοποίηση υπογραφής Εικόνας (δείτε [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) ιδιότητα SignatureImplementation).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας κειμένου για την τοποθέτηση της υπογραφής κειμένου σε αυτό. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Λαμβάνει ή ορίζει τον τίτλο του πεδίου φόρμας κειμένου για την τοποθέτηση της υπογραφής κειμένου σε αυτό. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για την τοποθέτηση της υπογραφής κειμένου σε αυτό. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField. Η προεπιλεγμένη τιμή είναι AllTextTypes.

**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του πεδίου φόρμας για την τοποθέτηση της υπογραφής κειμένου σε αυτό. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextToFormField. Η προεπιλεγμένη τιμή είναι AllTextTypes.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Λαμβάνει ή ορίζει τον τύπο του σχήματος για την τοποθέτηση του κειμένου. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextStamp. Η προεπιλεγμένη τιμή είναι Rectangle.

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του σχήματος για την τοποθέτηση του κειμένου. Αυτή η ιδιότητα μπορεί να χρησιμοποιηθεί μόνο με SignatureImplementation = TextStamp. Η προεπιλεγμένη τιμή είναι Rectangle.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό της υπογραφής. Μπορεί να χρησιμοποιηθεί στις επιλογές επαλήθευσης υπογραφής. Η ιδιότητα υποστηρίζεται μόνο για έγγραφα Pdf.

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό της υπογραφής. Μπορεί να χρησιμοποιηθεί στις επιλογές επαλήθευσης υπογραφής. Η ιδιότητα υποστηρίζεται μόνο για έγγραφα Pdf.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Καθορίστε τις ρυθμίσεις περιγράμματος

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Καθορίστε τις ρυθμίσεις περιγράμματος

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Λαμβάνει ή ορίζει τις ρυθμίσεις φόντου της υπογραφής.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Λαμβάνει ή ορίζει τις ρυθμίσεις φόντου της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Λαμβάνει ή ορίζει το εγγενές χαρακτηριστικό. Εάν οριστεί, μπορούν να χρησιμοποιηθούν υπογραφές ειδικές για το έγγραφο. Το εγγενές υδατογράφημα κειμένου για έγγραφα WordProcessing διαφέρει από το κανονικό, για παράδειγμα.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Λαμβάνει ή ορίζει το εγγενές χαρακτηριστικό. Εάν οριστεί, μπορούν να χρησιμοποιηθούν υπογραφές ειδικές για το έγγραφο. Το εγγενές υδατογράφημα κειμένου για έγγραφα WordProcessing διαφέρει από το κανονικό, για παράδειγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου.

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### validate() {#validate--}
```
public void validate()
```


Εσωτερική μέθοδος για την επικύρωση των παραμέτρων επιλογών.

### toString() {#toString--}
```
public String toString()
```


Παρακάμπτει τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
