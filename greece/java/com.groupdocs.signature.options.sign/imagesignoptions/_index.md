---
title: "ImageSignOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής Image."
type: docs
weight: 13
url: /el/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Αντιπροσωπεύει τις επιλογές υπογραφής Image.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με προεπιλεγμένες τιμές. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με αρχείο εικόνας. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με ροή εικόνας. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υπογραφής. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υπογραφής. |
|
|  | [getImageStream()](#getImageStream--) | Λαμβάνει ή ορίζει τη ροή εικόνας υπογραφής. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Λαμβάνει ή ορίζει τη ροή εικόνας υπογραφής. |
|
|  | [getLeft()](#getLeft--) | Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης |
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης |
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης |
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης |
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Πλάτος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης |
(pixel, ποσοστά ή χιλιοστά [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Πλάτος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης |
(pixel, ποσοστά ή χιλιοστά [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Ύψος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης |
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Ύψος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης |
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Left και Top. |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Left και Top. |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Τύπος μέτρησης (pixel, ποσοστά ή χιλιοστά) για τις ιδιότητες Width και Height. |
|
|  | [getStretch()](#getStretch--) | Λειτουργία τέντωσης στη Σελίδα Εγγράφου. |
|
|  | [setStretch(int value)](#setStretch-int-) | Λειτουργία τέντωσης στη Σελίδα Εγγράφου. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Γωνία περιστροφής της υπογραφής στη σελίδα εγγράφου (δεξιόστροφα). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Γωνία περιστροφής της υπογραφής στη σελίδα εγγράφου (δεξιόστροφα). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Οριζόντια στοίχιση της υπογραφής στη σελίδα εγγράφου. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Οριζόντια στοίχιση της υπογραφής στη σελίδα εγγράφου. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Κάθετη στοίχιση της υπογραφής στη σελίδα εγγράφου. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Κάθετη στοίχιση της υπογραφής στη σελίδα εγγράφου. |
|
|  | [getMargin()](#getMargin--) | Λαμβάνει ή ορίζει το διάστημα μεταξύ της Υπογραφής και των άκρων του Εγγράφου. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Λαμβάνει ή ορίζει το διάστημα μεταξύ της Υπογραφής και των άκρων του Εγγράφου. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Περιθώριο. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Περιθώριο. |
|
|  | [getTransparency()](#getTransparency--) | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0.0 (αδιαφανής) έως 1.0 (διαυγής)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0.0 (αδιαφανής) έως 1.0 (διαυγής)). |
|
|  | [getShapePosition()](#getShapePosition--) | Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου |
|
|  | [getRectangle()](#getRectangle--) | Ορθογώνιο της περιοχής για τοποθέτηση της εικόνας στο έγγραφο. |
|
|  | [getBorder()](#getBorder--) | Καθορίστε τις ρυθμίσεις του περιγράμματος |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Καθορίστε τις ρυθμίσεις του περιγράμματος |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης ImageSignOptions με προκαθορισμένη εικόνα από Base64. |
|
|  | [dispose()](#dispose--) | Καθαρίζει τους εσωτερικούς πόρους |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με προεπιλεγμένες τιμές.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με αρχείο εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Διαδρομή αρχείου εικόνας |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ImageSignOptions με ροή εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Ροή εικόνας |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υπογραφής.
Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το ImageStream.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υπογραφής.
Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το ImageStream.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Λαμβάνει ή ορίζει τη ροή εικόνας υπογραφής.
Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί για ImageGuid.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Λαμβάνει ή ορίζει τη ροή εικόνας υπογραφής.
Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί για ImageGuid.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(λειτουργεί εάν δεν έχει καθοριστεί οριζόντια στοίχιση).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Αριστερή θέση X της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(λειτουργεί εάν δεν έχει καθοριστεί οριζόντια στοίχιση).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(λειτουργεί εάν δεν έχει καθοριστεί κάθετη στοίχιση).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Άνω θέση Y της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(λειτουργεί εάν δεν έχει καθοριστεί κάθετη στοίχιση).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Πλάτος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης
(pixel, ποσοστά ή χιλιοστά [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Πλάτος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης
(pixel, ποσοστά ή χιλιοστά [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ύψος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ύψος της Υπογραφής στη Σελίδα Εγγράφου σε τιμές Μέτρησης
(pixel, ποσοστά ή χιλιοστά, δείτε [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


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


Λειτουργία τέντωσης στη Σελίδα Εγγράφου.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Λειτουργία τέντωσης στη Σελίδα Εγγράφου.


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


Λαμβάνει ή ορίζει το διάστημα μεταξύ της Υπογραφής και των άκρων του Εγγράφου.
(λειτουργεί ΜΟΝΟ εάν έχει καθοριστεί οριζόντια ή κάθετη στοίχιση).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ της Υπογραφής και των άκρων του Εγγράφου.
(λειτουργεί ΜΟΝΟ εάν έχει καθοριστεί οριζόντια ή κάθετη στοίχιση).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Περιθώριο.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Λαμβάνει ή ορίζει τον τύπο μέτρησης (pixel, ποσοστά ή χιλιοστά) για το Περιθώριο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0,0 (αδιαφανής) έως 1,0 (διαυγής)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανής).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Λαμβάνει ή ορίζει τη διαφάνεια της υπογραφής (τιμή από 0,0 (αδιαφανής) έως 1,0 (διαυγής)). Η προεπιλεγμένη τιμή είναι 0 (αδιαφανής).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Ορίζει πού πρέπει να εμφανίζεται το σχήμα στη διάταξη του εγγράφου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Ορθογώνιο της περιοχής για τοποθέτηση της εικόνας στο έγγραφο.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Καθορίστε τις ρυθμίσεις του περιγράμματος


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Καθορίστε τις ρυθμίσεις του περιγράμματος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης ImageSignOptions με προκαθορισμένη εικόνα από Base64.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | base64Content | java.lang.String | Περιεχόμενο εικόνας σε μορφή συμβολοσειράς Base64 |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Καθαρίζει τους εσωτερικούς πόρους


