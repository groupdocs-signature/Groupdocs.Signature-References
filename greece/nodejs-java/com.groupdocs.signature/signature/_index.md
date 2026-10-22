---
title: "Υπογραφή"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία υπογραφής εγγράφου."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία υπογραφής εγγράφου.

--------------------

**Learn more**

 *  More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide][]


[GroupDocs.Signature Developer Guide]: https://docs.groupdocs.com/display/signaturenet/Developer+Guide
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής. |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής και επιλογές φόρτωσης LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής και [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής, επιλογές φόρτωσης LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) και ρυθμίσεις [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath)](#Signature-java.lang.String-) | Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου. |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου, LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) και [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή. |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή. |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου. |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου. |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα στην καθορισμένη διαδρομή αρχείου με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions). |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Επαληθεύει τις υπογραφές του εγγράφου με τα δεδομένα VerifyOptions που δόθηκαν. |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Επαληθεύει τις υπογραφές του εγγράφου με λίστα δεδομένων VerifyOptions. |
| [getDocumentInfo()](#getDocumentInfo--) | Λαμβάνει πληροφορίες για τις σελίδες του εγγράφου: τα μεγέθη τους, το μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Δημιουργεί προεπισκόπηση των σελίδων του εγγράφου. |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Αναζητά υπογραφές σε ένα έγγραφο με λίστα [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Αναζητά υπογραφές σε ένα έγγραφο με επιλογές [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Αναζητά ακριβή τύπο υπογραφών στο έγγραφο με την τιμή [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
| [search(int[] signatureTypes)](#search-int...-) | Αναζητά καθορισμένους τύπους υπογραφών στο έγγραφο με την τιμή [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Ενημερώνει την παρεχόμενη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο. |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Ενημερώνει τις παρεχόμενες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο. |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Ενημερώνει τις παρεχόμενες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο. |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Ενημερώνει τις παρεχόμενες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο. |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Διαγράφει την παρεχόμενη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Διαγράφει την παρεχόμενη λίστα υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Διαγράφει την παρεχόμενη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Διαγράφει την παρεχόμενη λίστα υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Διαγράφει υπογραφές ενός συγκεκριμένου τύπου [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Διαγράφει τις υπογραφές από τη λίστα συγκεκριμένων τύπων [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Διαγράφει υπογραφές ενός συγκεκριμένου τύπου [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Διαγράφει τις υπογραφές από τη λίστα συγκεκριμένων τύπων [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. |
| [delete(String signatureId)](#delete-java.lang.String-) | Διαγράφει την υπογραφή με το συγκεκριμένο αναγνωριστικό της από το έγγραφο. |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Διαγράφει την παρεχόμενη λίστα υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο. |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Δημιουργεί προεπισκόπηση υπογραφής βάσει των δεδομένων SignOptions. |
| [dispose()](#dispose--) | Υλοποιήστε τη διεπαφή IDisposable για να καθαρίσετε τους εσωτερικούς πόρους |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | έγγραφο | java.io.InputStream | Η ροή περιεχομένου του εγγράφου. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής και επιλογές φόρτωσης LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.InputStream | Η ροή περιεχομένου του εγγράφου. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής και [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.InputStream | Η ροή περιεχομένου του εγγράφου. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Οι ρυθμίσεις υπογραφής. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω ροής, επιλογές φόρτωσης LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) και ρυθμίσεις [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.InputStream | Η ροή περιεχομένου του εγγράφου. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Οι ρυθμίσεις υπογραφής. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Απόλυτη ή σχετική διαδρομή αρχείου. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Απόλυτη ή σχετική διαδρομή αρχείου. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Απόλυτη ή σχετική διαδρομή αρχείου. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Οι ρυθμίσεις υπογραφής. |

--------------------

 **Learn more** 

 *  
 *   |

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης [Signature](../../com.groupdocs.signature/signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου, LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) και [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Απόλυτη ή σχετική διαδρομή αρχείου. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | Οι ρυθμίσεις υπογραφής. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


Υπογράφει το έγγραφο με [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Οι επιλογές αποθήκευσης. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Η λίστα των επιλογών υπογραφής. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


Υπογράφει το έγγραφο με μια συλλογή από [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή με προκαθορισμένες [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Η λίστα των επιλογών υπογραφής. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Οι επιλογές αποθήκευσης. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

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
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Οι επιλογές υπογραφής. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Οι επιλογές αποθήκευσης. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Η λίστα των επιλογών υπογραφής. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

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
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | Η λίστα των επιλογών υπογραφής. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Οι επιλογές αποθήκευσης. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

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

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Λαμβάνει πληροφορίες για τις σελίδες του εγγράφου: τα μεγέθη τους, το μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος.

**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

--------------------

**Learn more**

 *  Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java][]


[How to get document properties in Java]: https://docs.groupdocs.com/signature/java/get-document-information/
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Δημιουργεί προεπισκόπηση των σελίδων του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Οι επιλογές προεπισκόπησης. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature][]


[How to generate document pages preview using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/generate-document-pages-preview/ |

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Αναζητά υπογραφές σε ένα έγγραφο με λίστα [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Η συλλογή επιλογών αναζήτησης. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.
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

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Επιστρέφει τη λίστα των υπογραφών που βρέθηκαν.
### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Αναζητά ακριβή τύπο υπογραφών στο έγγραφο με την τιμή [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Ο τύπος των υπογραφών για αναζήτηση. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Επιστρέφει τη λίστα των υπογραφών που βρέθηκαν με ακριβή τύπο.
### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Αναζητά καθορισμένους τύπους υπογραφών στο έγγραφο με την τιμή [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatureTypes | int[] | Ένας ή πολλοί τύποι υπογραφών για εύρεση. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.
### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


Ενημερώνει την παρεχόμενη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Αντικείμενο υπογραφής που θα ενημερωθεί στο έγγραφο. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.
### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Ενημερώνει τις παρεχόμενες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|  | υπογραφές | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Λίστα υπογραφών για ενημέρωση στο έγγραφο. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


Ενημερώνει τις παρεχόμενες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
|  | υπογραφές | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Λίστα υπογραφών για ενημέρωση στο έγγραφο. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


Ενημερώνει τις παρεχόμενες υπογραφές [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) στο έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Αντικείμενο υπογραφής που θα ενημερωθεί στο έγγραφο. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Επιστρέφει UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) με λίστα των υπογραφών που ενημερώθηκαν επιτυχώς και των αποτυχημένων.
### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Διαγράφει την παρεχόμενη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Αντικείμενο υπογραφής που θα αφαιρεθεί από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.
### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Διαγράφει την παρεχόμενη λίστα υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|  | υπογραφές | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Λίστα υπογραφών για αφαίρεση από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


Διαγράφει την παρεχόμενη υπογραφή [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Αντικείμενο υπογραφής που θα αφαιρεθεί από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.
### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Διαγράφει την παρεχόμενη λίστα υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
|  | υπογραφές | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Λίστα υπογραφών για αφαίρεση από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


Διαγράφει υπογραφές ενός συγκεκριμένου τύπου [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο Sign και επισημάνθηκαν ως υπογραφές  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) θα αφαιρεθούν. Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|  | signatureType | int | Ο τύπος των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


Διαγράφει τις υπογραφές μιας λίστας συγκεκριμένων τύπων [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο Sign και επισημάνθηκαν ως υπογραφές  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) θα αφαιρεθούν. Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | java.io.OutputStream | Η ροή εξόδου του εγγράφου. |
|  | signatureTypes | java.util.List<java.lang.Integer> | Η λίστα των τύπων υπογραφών που θα αφαιρεθούν από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


Διαγράφει υπογραφές ενός συγκεκριμένου τύπου [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο Sign και επισημάνθηκαν ως υπογραφές  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) θα αφαιρεθούν. Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
|  | signatureType | int | Ο τύπος των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


Διαγράφει τις υπογραφές μιας λίστας συγκεκριμένων τύπων [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) από το έγγραφο. Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο Sign και επισημάνθηκαν ως υπογραφές  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) θα αφαιρεθούν. Οι ακόλουθοι τύποι υπογραφών υποστηρίζονται: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή εξόδου του αρχείου. |
|  | signatureTypes | java.util.List<java.lang.Integer> | Η λίστα των τύπων υπογραφών που θα αφαιρεθούν από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


Διαγράφει την υπογραφή με το συγκεκριμένο αναγνωριστικό της από το έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatureId | java.lang.String | Το Id της υπογραφής που θα αφαιρεθεί από το έγγραφο. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
boolean - Επιστρέφει true εάν η λειτουργία ήταν επιτυχής.
### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Διαγράφει την παρεχόμενη λίστα υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) από το έγγραφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Λίστα των αναγνωριστικών των υπογραφών που θα αφαιρεθούν από το έγγραφο. |

--------------------

**Learn more** ///  ///  /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature][] ///  ///  /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C] ///  ///  ///


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


Δημιουργεί προεπισκόπηση υπογραφής βάσει των δοσμένων SignOptions. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | Η προεπισκόπηση υπογραφής με τα δοσμένα SignOptions. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

--------------------

**Learn more**

 *  Learn more about how to generate previews of the signatures: |

### dispose() {#dispose--}
```
public final void dispose()
```


Υλοποιήστε τη διεπαφή IDisposable για να καθαρίσετε τους εσωτερικούς πόρους

