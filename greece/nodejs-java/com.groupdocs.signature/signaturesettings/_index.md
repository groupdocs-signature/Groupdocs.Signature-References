---
title: "SignatureSettings"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του [Signature](../../com.groupdocs.signature/signature).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SignatureSettings()](#SignatureSettings--) | Δημιουργεί προεπιλεγμένη παρουσία του SignatureSettings με προεπιλεγμένες τιμές. |
| [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Δημιουργεί προεπιλεγμένη παρουσία του SignatureSettings με την υλοποίηση του Logger. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDefaultCulture()](#getDefaultCulture--) | Λαμβάνει ή ορίζει την προεπιλεγμένη πολιτισμική ρύθμιση που θα χρησιμοποιηθεί κατά την επεξεργασία εγγράφων. |
| [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Λαμβάνει ή ορίζει την προεπιλεγμένη πολιτισμική ρύθμιση που θα χρησιμοποιηθεί κατά την επεξεργασία εγγράφων. |
| [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Λαμβάνει ή ορίζει τη σημαία που περιλαμβάνει διαγραμμένες υπογραφές στο αποτέλεσμα Πληροφοριών Εγγράφου. |
| [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Λαμβάνει ή ορίζει τη σημαία που περιλαμβάνει διαγραμμένες υπογραφές στο αποτέλεσμα Πληροφοριών Εγγράφου. |
| [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Λαμβάνει ή ορίζει τη σημαία για επαναποθήκευση του πηγαίου εγγράφου όταν η μέθοδος Update δεν έχει υπογραφές για ενημέρωση. |
| [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Λαμβάνει ή ορίζει τη σημαία για επαναποθήκευση του πηγαίου εγγράφου όταν η μέθοδος Update δεν έχει υπογραφές για ενημέρωση. |
| [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Λαμβάνει ή ορίζει τη σημαία για επαναποθήκευση του πηγαίου εγγράφου όταν η μέθοδος Delete δεν έχει επηρεασμένες υπογραφές για αφαίρεση. |
| [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Λαμβάνει ή ορίζει τη σημαία για επαναποθήκευση του πηγαίου εγγράφου όταν η μέθοδος Delete δεν έχει επηρεασμένες υπογραφές για αφαίρεση. |
| [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Λαμβάνει ή ορίζει τη σημαία για να συμπεριληφθούν στη Λίστα Μεταδεδομένων οι ενσωματωμένες τυπικές υπογραφές μεταδεδομένων εγγράφου όπως Συγγραφέας, Ιδιοκτήτης, ημερομηνία δημιουργίας εγγράφου, ημερομηνία τροποποίησης κ.λπ. |
| [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Λαμβάνει ή ορίζει τη σημαία για να συμπεριληφθούν στη Λίστα Μεταδεδομένων οι ενσωματωμένες τυπικές υπογραφές μεταδεδομένων εγγράφου όπως Συγγραφέας, Ιδιοκτήτης, ημερομηνία δημιουργίας εγγράφου, ημερομηνία τροποποίησης κ.λπ. |
| [getLogger()](#getLogger--) | Η υλοποίηση του logger που χρησιμοποιείται για την καταγραφή (Σφάλματα, Προειδοποιήσεις, Ανιχνεύσεις). |
| [getLogLevel()](#getLogLevel--) | Το επίπεδο της καταγραφής για περιορισμό των μηνυμάτων (Όλα, Ανιχνεύσεις, Προειδοποιήσεις, Σφάλματα). |
| [setLogLevel(int value)](#setLogLevel-int-) | Το επίπεδο της καταγραφής για περιορισμό των μηνυμάτων (Όλα, Ανιχνεύσεις, Προειδοποιήσεις, Σφάλματα). |
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Δημιουργεί προεπιλεγμένη παρουσία του SignatureSettings με προεπιλεγμένες τιμές.

### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Δημιουργεί προεπιλεγμένη παρουσία του SignatureSettings με την υλοποίηση του Logger.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Λαμβάνει ή ορίζει την προεπιλεγμένη πολιτιστική ρύθμιση που θα χρησιμοποιείται κατά την επεξεργασία εγγράφων. Η προεπιλεγμένη τιμή είναι "en-US".

**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Λαμβάνει ή ορίζει την προεπιλεγμένη πολιτιστική ρύθμιση που θα χρησιμοποιείται κατά την επεξεργασία εγγράφων. Η προεπιλεγμένη τιμή είναι "en-US".

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Λαμβάνει ή ορίζει τη σημαία που περιλαμβάνει διαγραμμένες υπογραφές στο αποτέλεσμα Πληροφοριών Εγγράφου. Κάθε Υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) έχει τη σημαία Deleted  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) για να εντοπίσει αν έχει διαγραφεί.

**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία που περιλαμβάνει διαγραμμένες υπογραφές στο αποτέλεσμα Πληροφοριών Εγγράφου. Κάθε Υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) έχει τη σημαία Deleted  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) για να εντοπίσει αν έχει διαγραφεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Λαμβάνει ή ορίζει τη σημαία για επαναποθήκευση του αρχικού εγγράφου όταν η μέθοδος Update δεν έχει υπογραφές για ενημέρωση. Εάν αυτή η σημαία οριστεί σε true (προεπιλογή), το έγγραφο θα αποθηκεύεται με το αντίστοιχο ιστορικό καταγραφής διαδικασίας (ημερομηνία και τύπος λειτουργίας) ακόμη και αν η μέθοδος Update δεν έχει υπογραφές για ενημέρωση. Όταν αυτή η σημαία οριστεί σε false, το αρχικό έγγραφο δεν θα τροποποιηθεί καθόλου.

**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για επαναποθήκευση του αρχικού εγγράφου όταν η μέθοδος Update δεν έχει υπογραφές για ενημέρωση. Εάν αυτή η σημαία οριστεί σε true (προεπιλογή), το έγγραφο θα αποθηκεύεται με το αντίστοιχο ιστορικό καταγραφής διαδικασίας (ημερομηνία και τύπος λειτουργίας) ακόμη και αν η μέθοδος Update δεν έχει υπογραφές για ενημέρωση. Όταν αυτή η σημαία οριστεί σε false, το αρχικό έγγραφο δεν θα τροποποιηθεί καθόλου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Λαμβάνει ή ορίζει τη σημαία για επαναποθήκευση του αρχικού εγγράφου όταν η μέθοδος Delete δεν έχει επηρεασμένες υπογραφές για αφαίρεση. Εάν αυτή η σημαία οριστεί σε true (προεπιλογή), το έγγραφο θα αποθηκεύεται με το αντίστοιχο ιστορικό καταγραφής διαδικασίας (ημερομηνία και τύπος λειτουργίας) ακόμη και αν η μέθοδος Delete δεν έχει υπογραφές για αφαίρεση. Όταν αυτή η σημαία οριστεί σε false, το αρχικό έγγραφο δεν θα τροποποιηθεί καθόλου.

**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για επαναποθήκευση του αρχικού εγγράφου όταν η μέθοδος Delete δεν έχει επηρεασμένες υπογραφές για αφαίρεση. Εάν αυτή η σημαία οριστεί σε true (προεπιλογή), το έγγραφο θα αποθηκεύεται με το αντίστοιχο ιστορικό καταγραφής διαδικασίας (ημερομηνία και τύπος λειτουργίας) ακόμη και αν η μέθοδος Delete δεν έχει υπογραφές για αφαίρεση. Όταν αυτή η σημαία οριστεί σε false, το αρχικό έγγραφο δεν θα τροποποιηθεί καθόλου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Λαμβάνει ή ορίζει τη σημαία για συμπερίληψη στη Λίστα Μεταδεδομένων των ενσωματωμένων τυπικών μεταδεδομένων υπογραφών εγγράφου όπως Συγγραφέας, Ιδιοκτήτης, ημερομηνία δημιουργίας εγγράφου, ημερομηνία τροποποίησης κ.λπ. Εάν αυτή η σημαία οριστεί σε false (προεπιλογή), η μέθοδος GetDocumentInfo δεν θα συμπεριλάβει αυτές τις υπογραφές μεταδεδομένων. Όταν αυτή η σημαία οριστεί σε true, οι πληροφορίες του εγγράφου θα περιλαμβάνουν αυτές τις τυπικές υπογραφές μεταδεδομένων.

**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για συμπερίληψη στη Λίστα Μεταδεδομένων των ενσωματωμένων τυπικών μεταδεδομένων υπογραφών εγγράφου όπως Συγγραφέας, Ιδιοκτήτης, ημερομηνία δημιουργίας εγγράφου, ημερομηνία τροποποίησης κ.λπ. Εάν αυτή η σημαία οριστεί σε false (προεπιλογή), η μέθοδος GetDocumentInfo δεν θα συμπεριλάβει αυτές τις υπογραφές μεταδεδομένων. Όταν αυτή η σημαία οριστεί σε true, οι πληροφορίες του εγγράφου θα περιλαμβάνουν αυτές τις τυπικές υπογραφές μεταδεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Η υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Σφάλματα, Προειδοποιήσεις, Ιχνηλάσεις). [ILogger](../../com.groupdocs.signature.logging/ilogger).

**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Το επίπεδο της καταγραφής για περιορισμό των μηνυμάτων (All, Traces, Warnings, Errors). LogLevel. Από προεπιλογή, έχει οριστεί το επίπεδο All.

**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Το επίπεδο της καταγραφής για περιορισμό των μηνυμάτων (All, Traces, Warnings, Errors). LogLevel. Από προεπιλογή, έχει οριστεί το επίπεδο All.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

