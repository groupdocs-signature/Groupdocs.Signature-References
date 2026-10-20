---
title: "Υπογραφή"
second_title: "GroupDocs.Signature για .NET αναφορά API"
description: "Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία υπογραφής εγγράφου."
type: docs
weight: 2170
url: /el/net/groupdocs.signature/signature/
---
## Signature class

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία υπογραφής εγγράφου.

```csharp
public class Signature : IDisposable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Αρχικοποιεί νέα παρουσία της κλάσης [`Signature`](../signature) με έγγραφο που παρέχεται μέσω ροής. |
| [Signature](signature#constructor_4)(string) | Αρχικοποιεί νέα παρουσία της κλάσης [`Signature`](../signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Αρχικοποιεί νέα παρουσία της κλάσης [`Signature`](../signature) με έγγραφο που παρέχεται μέσω ροής και επιλογές φόρτωσης LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Signature`](../signature) με έγγραφο που παρέχεται μέσω ροής και [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Αρχικοποιεί νέα παρουσία της κλάσης [`Signature`](../signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Signature`](../signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου και [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Signature`](../signature) με έγγραφο που παρέχεται μέσω ροής, επιλογές φόρτωσης LoadOptions και ρυθμίσεις [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Signature`](../signature) με έγγραφο που παρέχεται μέσω διαδρομής αρχείου, LoadOptions και [`SignatureSettings`](../signaturesettings). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Διαγράφει την παρεχόμενη υπογραφή [`BaseSignature`](../../groupdocs.signature.domain/basesignature) από το έγγραφο. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Διαγράφει τη δοθείσα λίστα υπογραφών [`BaseSignature`](../../groupdocs.signature.domain/basesignature) από το έγγραφο. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Διαγράφει τις υπογραφές των συγκεκριμένων τύπων λίστας [`SignatureType`](../../groupdocs.signature.domain/signaturetype) από το έγγραφο. Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο Sign και σημειώθηκαν ως Υπογραφές [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) θα αφαιρεθούν. Υποστηρίζονται οι ακόλουθοι τύποι υπογραφών: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Διαγράφει τη δοθείσα λίστα υπογραφών [`BaseSignature`](../../groupdocs.signature.domain/basesignature) από το έγγραφο. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Διαγράφει τις υπογραφές του συγκεκριμένου τύπου [`SignatureType`](../../groupdocs.signature.domain/signaturetype) από το έγγραφο. Μόνο οι υπογραφές που προστέθηκαν με τη μέθοδο Sign και σημειώθηκαν ως Υπογραφές [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) θα αφαιρεθούν. Υποστηρίζονται οι ακόλουθοι τύποι υπογραφών: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Διαγράφει την υπογραφή με το συγκεκριμένο αναγνωριστικό υπογραφής από το έγγραφο. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Υλοποιήστε τη διεπαφή IDisposable για τον καθαρισμό των εσωτερικών πόρων |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Δημιουργεί προεπισκόπηση των σελίδων του εγγράφου. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Λαμβάνει πληροφορίες σχετικά με τις σελίδες του εγγράφου: τα μεγέθη τους, το μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Αναζητά υπογραφές στο έγγραφο χρησιμοποιώντας όλες τις διαθέσιμες επιλογές αναζήτησης και φιλτράρει τα αποτελέσματα βάσει του καθορισμένου προδιαγραφέα. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Αναζητά υπογραφές σε ένα έγγραφο με λίστα [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Αναζητά καθορισμένους τύπους υπογραφών στο έγγραφο με την τιμή του [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Αναζητά υπογραφές στο έγγραφο χρησιμοποιώντας τις παρεχόμενες επιλογές αναζήτησης και φιλτράρει τα αποτελέσματα βάσει της καθορισμένης συνθήκης. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Αναζητά υπογραφές σε ένα έγγραφο με τις επιλογές [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Αναζητά ακριβή τύπο υπογραφών στο έγγραφο με την τιμή του [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Υπογράφει το έγγραφο με μια συλλογή από [`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Υπογράφει το έγγραφο με [`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Υπογράφει το έγγραφο με μια συλλογή από [`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα στη συγκεκριμένη διαδρομή αρχείου. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Υπογράφει το έγγραφο με [`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα στη συγκεκριμένη διαδρομή αρχείου. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Υπογράφει το έγγραφο με μια συλλογή από [`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή με προκαθορισμένες [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Υπογράφει το έγγραφο με [`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε ροή με προκαθορισμένες [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Υπογράφει το έγγραφο με μια συλλογή από [`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα στη συγκεκριμένη διαδρομή αρχείου με προκαθορισμένες [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Υπογράφει το έγγραφο με [`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα στη συγκεκριμένη διαδρομή αρχείου με προκαθορισμένες [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Ενημερώνει την παρεχόμενη υπογραφή [`BaseSignature`](../../groupdocs.signature.domain/basesignature) στο έγγραφο. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Ενημερώνει τις παρεχόμενες υπογραφές [`BaseSignature`](../../groupdocs.signature.domain/basesignature) στο έγγραφο. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Επαληθεύει τις υπογραφές του εγγράφου με λίστα δεδομένων VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Επαληθεύει τις υπογραφές του εγγράφου με τα δεδομένα VerifyOptions που δόθηκαν. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας όλες τις διαθέσιμες επιλογές επαλήθευσης και φιλτράρει τα αποτελέσματα βάσει της καθορισμένης συνθήκης. Αυτή η μέθοδος πρώτα αναζητά υπογραφές που ταιριάζουν με τις επιλογές επαλήθευσης, τις φιλτράρει με τη συνθήκη και στη συνέχεια επαληθεύει μόνο τις φιλτραρισμένες υπογραφές. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Επαληθεύει τις υπογραφές του εγγράφου χρησιμοποιώντας τις παρεχόμενες επιλογές επαλήθευσης και φιλτράρει τα αποτελέσματα βάσει της καθορισμένης συνθήκης. Αυτή η μέθοδος πρώτα αναζητά υπογραφές που ταιριάζουν με τις επιλογές επαλήθευσης, τις φιλτράρει με τη συνθήκη και στη συνέχεια επαληθεύει μόνο τις φιλτραρισμένες υπογραφές. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Δημιουργεί προεπισκόπηση υπογραφής βάσει των δεδομένων SignOptions. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Συμβάντα

| Όνομα | Περιγραφή |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Συμβαίνει όταν η διαδικασία αναζήτησης υπογραφών ολοκληρωθεί. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Συμβαίνει όταν η πρόοδος της διαδικασίας αναζήτησης υπογραφών αλλάξει. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Συμβαίνει όταν η διαδικασία αναζήτησης υπογραφών ξεκινήσει. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Συμβαίνει όταν η διαδικασία υπογραφής εγγράφου ολοκληρωθεί. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Συμβαίνει όταν η πρόοδος της διαδικασίας υπογραφής εγγράφου αλλάζει. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Συμβαίνει όταν η διαδικασία υπογραφής εγγράφου ξεκινά. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Συμβαίνει όταν η διαδικασία επαλήθευσης υπογραφής ολοκληρώνεται. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Συμβαίνει όταν η πρόοδος της διαδικασίας επαλήθευσης υπογραφής αλλάζει. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Συμβαίνει όταν η διαδικασία επαλήθευσης υπογραφής ξεκινά. |

### Παρατηρήσεις

**Learn more**

Περισσότερα σχετικά με τις δυνατότητες του GroupDocs.Signature: [GroupDocs.Signature Οδηγός Προγραμματιστή](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Δείτε επίσης

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
