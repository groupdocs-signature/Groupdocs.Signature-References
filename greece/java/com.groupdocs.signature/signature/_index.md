---
title: "Υπογραφή"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία υπογραφής εγγράφων."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία υπογραφής εγγράφων.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής και επιλογές φόρτωσης |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής και [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής, επιλογές φόρτωσης |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) και ρυθμίσεις [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου. |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου, |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) και [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή. |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου. |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Επαληθεύει τις υπογραφές του εγγράφου με τα δεδομένα VerifyOptions που δόθηκαν. |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Επαληθεύει τις υπογραφές του εγγράφου με λίστα δεδομένων VerifyOptions. |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας τις παρεχόμενες επιλογές επαλήθευσης και φίλτρα |
τα επιτυχημένα αποτελέσματα με το καθορισμένο κατηγόρημα.
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας μια λίστα επιλογών επαλήθευσης και φιλτράρει το |
επιτυχημένα αποτελέσματα με το καθορισμένο κατηγόρημα.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Λαμβάνει πληροφορίες σχετικά με τις σελίδες του εγγράφου: τα μεγέθη τους, |
μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος.
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Δημιουργεί προεπισκόπηση σελίδων εγγράφου. |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Αναζητά υπογραφές σε ένα έγγραφο με λίστα [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Αναζητά υπογραφές με λίστα επιλογών και φιλτράρει το αποτέλεσμα με ένα κατηγόρημα. |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Αναζητά υπογραφές σε ένα έγγραφο με επιλογές [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | Αναζητά υπογραφές του καθορισμένου τύπου στο έγγραφο, προαιρετικά φιλτραρισμένες με ένα κατηγόρημα. |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Αναζητά ακριβή τύπο υπογραφών στο έγγραφο με τιμή [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
|
|  | [search(int[] signatureTypes)](#search-int...-) | Αναζητά καθορισμένους τύπους υπογραφών στο έγγραφο με τιμή [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Ενημερώνει την περασμένη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο. |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Ενημερώνει τις περασμένες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο. |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Ενημερώνει τις περασμένες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο. |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Ενημερώνει τις περασμένες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο. |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Διαγράφει την περασμένη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Διαγράφει τη λίστα των περασμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Διαγράφει την περασμένη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Διαγράφει τη λίστα των περασμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Διαγράφει υπογραφές συγκεκριμένου τύπου [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Διαγράφει τις υπογραφές της λίστας συγκεκριμένων τύπων [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Διαγράφει υπογραφές συγκεκριμένου τύπου [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Διαγράφει τις υπογραφές της λίστας συγκεκριμένων τύπων [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | Διαγράφει την υπογραφή με το συγκεκριμένο αναγνωριστικό υπογραφής από το έγγραφο. |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Διαγράφει τη λίστα των περασμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Δημιουργεί προεπισκόπηση της υπογραφής βάσει των δοσμένων επιλογών SignOptions. |
|
|  | [dispose()](#dispose--) | Εφαρμόστε τη διεπαφή IDisposable για να καθαρίσετε τους εσωτερικούς πόρους |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή περιεχομένου του εγγράφου. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής και επιλογές φόρτωσης
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή περιεχομένου του εγγράφου. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής και [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή περιεχομένου του εγγράφου. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Οι ρυθμίσεις υπογραφής. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής, επιλογές φόρτωσης
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) και ρυθμίσεις [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή περιεχομένου του εγγράφου. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Οι ρυθμίσεις υπογραφής. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Απόλυτη ή σχετική διαδρομή αρχείου. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Απόλυτη ή σχετική διαδρομή αρχείου. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Απόλυτη ή σχετική διαδρομή αρχείου. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Οι ρυθμίσεις υπογραφής. |

<br />

*** ** * ** ***

 **Learn more** 

* 
* 

<br />

|

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


Αρχικοποιεί νέα παρουσία της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου,
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) και [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Απόλυτη ή σχετική διαδρομή αρχείου. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Οι ρυθμίσεις υπογραφής. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Οι επιλογές αποθήκευσης. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Η λίστα των επιλογών υπογραφής. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Η λίστα των επιλογών υπογραφής. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Οι επιλογές αποθήκευσης. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Οι επιλογές αποθήκευσης. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Η λίστα των επιλογών υπογραφής. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Η λίστα των επιλογών υπογραφής. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Οι επιλογές αποθήκευσης. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


Επαληθεύει τις υπογραφές του εγγράφου με τα δεδομένα VerifyOptions που δόθηκαν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Οι επιλογές επαλήθευσης υπογραφής. |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


Επαληθεύει τις υπογραφές του εγγράφου με λίστα δεδομένων VerifyOptions.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | Η συλλογή επιλογών επαλήθευσης υπογραφής. Παράδειγμα του [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)
```


Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας τις παρεχόμενες επιλογές επαλήθευσης και φίλτρα
τα επιτυχημένα αποτελέσματα με το καθορισμένο κατηγόρημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | Οι επιλογές επαλήθευσης υπογραφής. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Καθοριστής φίλτρου που εφαρμόζεται στη λίστα των επαληθευμένων υπογραφών. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Λίστα υπογραφών που πέρασαν την επαλήθευση και ικανοποίησαν τον καθοριστή.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας μια λίστα επιλογών επαλήθευσης και φιλτράρει το
επιτυχημένα αποτελέσματα με το καθορισμένο κατηγόρημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | Η λίστα επιλογών επαλήθευσης υπογραφής. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Καθοριστής φίλτρου που εφαρμόζεται στη λίστα των επαληθευμένων υπογραφών. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Λίστα υπογραφών που πέρασαν την επαλήθευση και ικανοποίησαν τον καθοριστή.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Λαμβάνει πληροφορίες σχετικά με τις σελίδες του εγγράφου: τα μεγέθη τους,
μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος.


**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

<br />

*** ** * ** ***

**Learn more**

* Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java](../https://docs.groupdocs.com/signature/java/get-document-information/)

<br />


### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Δημιουργεί προεπισκόπηση σελίδων εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Οι επιλογές προεπισκόπησης. |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/generate-document-pages-preview/)

<br />

|

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Αναζητά υπογραφές σε ένα έγγραφο με λίστα [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Η συλλογή επιλογών αναζήτησης. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.

### search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)
```


Αναζητά υπογραφές με λίστα επιλογών και φιλτράρει το αποτέλεσμα με ένα κατηγόρημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Η λίστα επιλογών αναζήτησης. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Καθοριστής που χρησιμοποιείται για το φιλτράρισμα των προκύπτων υπογραφών. |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Αναζητά υπογραφές σε ένα έγγραφο με επιλογές [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Οι επιλογές αναζήτησης. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Επιστρέφει τη λίστα των υπογραφών που βρέθηκαν.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


Αναζητά υπογραφές του καθορισμένου τύπου στο έγγραφο, προαιρετικά φιλτραρισμένες με ένα κατηγόρημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | Γενική παράμετρος τύπου του [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Επιλογές για την αναζήτηση υπογραφών. |
|
|  | predicate | java.util.function.Predicate<T> | Προαιρετικό φίλτρο καθοριστή που εφαρμόζεται μετά την αναζήτηση. Μπορεί να είναι null. |
|

**Returns:**
java.util.List<T> - Λίστα των βρεθεισών υπογραφών, προαιρετικά φιλτραρισμένων από τον καθοριστή.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Αναζητά ακριβή τύπο υπογραφών στο έγγραφο με τιμή [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Ο τύπος των υπογραφών για αναζήτηση. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Επιστρέφει τη λίστα των βρεθεισών υπογραφών με ακριβή τύπο.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Αναζητά καθορισμένους τύπους υπογραφών στο έγγραφο με τιμή [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatureTypes | int[] | Ένας ή πολλοί τύποι υπογραφών για εύρεση. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.

### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


Ενημερώνει την περασμένη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Αντικείμενο υπογραφής που θα ενημερωθεί στο έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Ενημερώνει τις περασμένες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | υπογραφές | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Λίστα υπογραφών για ενημέρωση στο έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


Ενημερώνει τις περασμένες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | υπογραφές | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Λίστα υπογραφών για ενημέρωση στο έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


Ενημερώνει τις περασμένες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Αντικείμενο υπογραφής που θα ενημερωθεί στο έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Επιστρέφει UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) με λίστα των υπογραφών που ενημερώθηκαν επιτυχώς και των αποτυχημένων.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Διαγράφει την περασμένη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Αντικείμενο Signature για αφαίρεση από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Διαγράφει τη λίστα των περασμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | υπογραφές | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Λίστα υπογραφών για αφαίρεση από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


Διαγράφει την περασμένη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Αντικείμενο Signature για αφαίρεση από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Διαγράφει τη λίστα των περασμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | υπογραφές | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Λίστα υπογραφών για αφαίρεση από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


Διαγράφει υπογραφές συγκεκριμένου τύπου [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο.
Μόνο υπογραφές που προστέθηκαν με τη μέθοδο Sign και σημειώθηκαν ως Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) θα αφαιρεθεί.
Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | signatureType | int | Ο τύπος των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


Διαγράφει τις υπογραφές της λίστας συγκεκριμένων τύπων [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο.
Μόνο υπογραφές που προστέθηκαν με τη μέθοδο Sign και σημειώθηκαν ως Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) θα αφαιρεθεί.
Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | Η λίστα των τύπων υπογραφών που θα αφαιρεθούν από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


Διαγράφει υπογραφές συγκεκριμένου τύπου [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο.
Μόνο υπογραφές που προστέθηκαν με τη μέθοδο Sign και σημειώθηκαν ως Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) θα αφαιρεθεί.
Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | signatureType | int | Ο τύπος των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


Διαγράφει τις υπογραφές της λίστας συγκεκριμένων τύπων [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο.
Μόνο υπογραφές που προστέθηκαν με τη μέθοδο Sign και σημειώθηκαν ως Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) θα αφαιρεθεί.
Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή εξόδου αρχείου. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | Η λίστα των τύπων υπογραφών που θα αφαιρεθούν από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


Διαγράφει την υπογραφή με το συγκεκριμένο αναγνωριστικό υπογραφής από το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatureId | java.lang.String | Το Id της υπογραφής που θα αφαιρεθεί από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Διαγράφει τη λίστα των περασμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Λίστα των αναγνωριστικών των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

<br />

*** ** * ** ***

**Learn more** /// /// /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents) /// /// /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting) /// /// ///
|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


Δημιουργεί προεπισκόπηση Signature βάσει των δοσμένων SignOptions. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | Η προεπισκόπηση της υπογραφής με τα δοσμένα SignOptions. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


Εφαρμόστε τη διεπαφή IDisposable για να καθαρίσετε τους εσωτερικούς πόρους


