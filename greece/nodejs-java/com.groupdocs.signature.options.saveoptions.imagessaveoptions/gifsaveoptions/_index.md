---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Επιλογές αποθήκευσης μορφής Gif για έγγραφα εικόνας."
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Επιλογές αποθήκευσης μορφής Gif για έγγραφα εικόνας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GifSaveOptions()](#GifSaveOptions--) | Δημιουργεί GifSaveOptions με προεπιλεγμένες τιμές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF. |
| [getColorResolution()](#getColorResolution--) | Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται διόρθωση παλέτας. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται διόρθωση παλέτας. |
| [hasTrailer()](#hasTrailer--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει τρέιλερ. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει τρέιλερ. |
| [getInterlaced()](#getInterlaced--) | Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη. |
| [isPaletteSorted()](#isPaletteSorted--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις παλέτας είναι ταξινομημένες. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις παλέτας είναι ταξινομημένες. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel GIF. |
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Δημιουργεί GifSaveOptions με προεπιλεγμένες τιμές.

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF.

**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF.

--------------------

Ανάλυση χρώματος - Αριθμός bits ανά πρωτεύον χρώμα που είναι διαθέσιμα στην αρχική εικόνα, μείον 1. Αυτή η τιμή αντιπροσωπεύει το μέγεθος ολόκληρης της παλέτας από την οποία επιλέχθηκαν τα χρώματα του γραφικού, όχι τον αριθμό των χρωμάτων που χρησιμοποιήθηκαν πραγματικά στο γραφικό. Για παράδειγμα, εάν η τιμή σε αυτό το πεδίο είναι 3, τότε η παλέτα της αρχικής εικόνας είχε 4 bits ανά πρωτεύον χρώμα διαθέσιμα για τη δημιουργία της εικόνας. Αυτή η τιμή θα πρέπει να οριστεί για να υποδεικνύει τον πλούτο της αρχικής παλέτας, ακόμη και αν δεν είναι διαθέσιμο κάθε χρώμα από ολόκληρη την παλέτα στο μηχάνημα προέλευσης.

**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF.

--------------------

Ανάλυση χρώματος - Αριθμός bits ανά πρωτεύον χρώμα που είναι διαθέσιμα στην αρχική εικόνα, μείον 1. Αυτή η τιμή αντιπροσωπεύει το μέγεθος ολόκληρης της παλέτας από την οποία επιλέχθηκαν τα χρώματα του γραφικού, όχι τον αριθμό των χρωμάτων που χρησιμοποιήθηκαν πραγματικά στο γραφικό. Για παράδειγμα, εάν η τιμή σε αυτό το πεδίο είναι 3, τότε η παλέτα της αρχικής εικόνας είχε 4 bits ανά πρωτεύον χρώμα διαθέσιμα για τη δημιουργία της εικόνας. Αυτή η τιμή θα πρέπει να οριστεί για να υποδεικνύει τον πλούτο της αρχικής παλέτας, ακόμη και αν δεν είναι διαθέσιμο κάθε χρώμα από ολόκληρη την παλέτα στο μηχάνημα προέλευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται διόρθωση παλέτας.

--------------------

Η διόρθωση παλέτας σημαίνει ότι κάθε φορά που η εικόνα εξάγεται σε GIF, τα χρώματα της πηγαίας εικόνας θα αναλυθούν προκειμένου να δημιουργηθεί η καλύτερη ταιριαστή παλέτα (σε περίπτωση που η παλέτα της εικόνας δεν υπάρχει ή δεν έχει καθοριστεί στις επιλογές). Η διαδικασία ανάλυσης διαρκεί κάποιο χρόνο, ωστόσο η τελική εικόνα θα έχει την καλύτερη ταιριαστή παλέτα χρωμάτων και το αποτέλεσμα θα είναι οπτικά καλύτερο.

**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται διόρθωση παλέτας.

--------------------

Η διόρθωση παλέτας σημαίνει ότι κάθε φορά που η εικόνα εξάγεται σε GIF, τα χρώματα της πηγαίας εικόνας θα αναλυθούν προκειμένου να δημιουργηθεί η καλύτερη ταιριαστή παλέτα (σε περίπτωση που η παλέτα της εικόνας δεν υπάρχει ή δεν έχει καθοριστεί στις επιλογές). Η διαδικασία ανάλυσης διαρκεί κάποιο χρόνο, ωστόσο η τελική εικόνα θα έχει την καλύτερη ταιριαστή παλέτα χρωμάτων και το αποτέλεσμα θα είναι οπτικά καλύτερο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει τρέιλερ.

**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει τρέιλερ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις παλέτας είναι ταξινομημένες.

**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις παλέτας είναι ταξινομημένες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel GIF.

--------------------

Αναλογία διαστάσεων pixel - Παράγοντας που χρησιμοποιείται για τον υπολογισμό μιας προσέγγισης της αναλογίας διαστάσεων του pixel στην αρχική εικόνα. Εάν η τιμή του πεδίου δεν είναι 0, αυτή η προσέγγιση της αναλογίας υπολογίζεται βάσει του τύπου: Αναλογία = (Αναλογία διαστάσεων pixel + 15) / 64. Η Αναλογία διαστάσεων pixel ορίζεται ως το πηλίκο του πλάτους του pixel προς το ύψος του. Η περιοχή τιμών σε αυτό το πεδίο επιτρέπει τον καθορισμό του πιο πλατιάς pixel 4:1 έως του πιο ψηλού pixel 1:4 με βήματα 1/64. Τιμές: 0 - Δεν παρέχονται πληροφορίες αναλογίας διαστάσεων. 1..255 - Τιμή που χρησιμοποιείται στον υπολογισμό.

**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel GIF.

--------------------

Αναλογία διαστάσεων pixel - Παράγοντας που χρησιμοποιείται για τον υπολογισμό μιας προσέγγισης της αναλογίας διαστάσεων του pixel στην αρχική εικόνα. Εάν η τιμή του πεδίου δεν είναι 0, αυτή η προσέγγιση της αναλογίας υπολογίζεται βάσει του τύπου: Αναλογία = (Αναλογία διαστάσεων pixel + 15) / 64. Η Αναλογία διαστάσεων pixel ορίζεται ως το πηλίκο του πλάτους του pixel προς το ύψος του. Η περιοχή τιμών σε αυτό το πεδίο επιτρέπει τον καθορισμό του πιο πλατιάς pixel 4:1 έως του πιο ψηλού pixel 1:4 με βήματα 1/64. Τιμές: 0 - Δεν παρέχονται πληροφορίες αναλογίας διαστάσεων. 1..255 - Τιμή που χρησιμοποιείται στον υπολογισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

