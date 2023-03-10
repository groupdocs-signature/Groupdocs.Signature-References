---
title: Signature
second_title: GroupDocs.Signature για Αναφορά API .NET
description: Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία υπογραφής εγγράφων.
type: docs
weight: 1880
url: /el/net/groupdocs.signature/signature/
---
## Signature class

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία υπογραφής εγγράφων.

```csharp
public class Signature : IDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Αρχικοποιεί νέα παρουσία του[`Signature`](../signature) τάξη με έγγραφο που παρέχεται από τη ροή. |
| [Signature](signature#constructor_4)(string) | Αρχικοποιεί νέα παρουσία του[`Signature`](../signature) παρουσία κλάσης με έγγραφο που παρέχεται από τη διαδρομή αρχείου. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Αρχικοποιεί νέα παρουσία του[`Signature`](../signature) τάξη με έγγραφο που παρέχεται από επιλογές ροής και φόρτωσηςLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Αρχικοποιεί νέα παρουσία του[`Signature`](../signature)παράδειγμα κλάσης με έγγραφο που παρέχεται από τη ροή και[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Αρχικοποιεί νέα παρουσία του[`Signature`](../signature) παράδειγμα κλάσης με έγγραφο που παρέχεται από τη διαδρομή αρχείου καιLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Αρχικοποιεί νέα παρουσία του[`Signature`](../signature) παράδειγμα κλάσης με έγγραφο που παρέχεται από τη διαδρομή αρχείου και[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Αρχικοποιεί νέα παρουσία του[`Signature`](../signature) παράδειγμα κλάσης με έγγραφο που παρέχεται από ροή, επιλογές φόρτωσηςLoadOptions και ρυθμίσεις[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Αρχικοποιεί νέα παρουσία του[`Signature`](../signature) παράδειγμα κλάσης με έγγραφο που παρέχεται από τη διαδρομή αρχείου,LoadOptions και[`SignatureSettings`](../signaturesettings) . |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Διαγράφει την υπογραφή που έχει περάσει[`BaseSignature`](../../groupdocs.signature.domain/basesignature) από το έγγραφο. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Διαγράφει τη λίστα υπογραφών που έχει περάσει[`BaseSignature`](../../groupdocs.signature.domain/basesignature) από το έγγραφο. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Διαγράφει τις υπογραφές της λίστας ορισμένων τύπων[`SignatureType`](../../groupdocs.signature.domain/signaturetype) από το έγγραφο. Μόνο υπογραφές που προστέθηκαν με τη μέθοδο Sign και επισημάνθηκαν ως υπογραφές[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) θα αφαιρεθεί. Υποστηρίζονται οι ακόλουθοι τύποι υπογραφών: Κείμενο, Εικόνα, Ψηφιακός, Γραμμωτός κώδικας, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Διαγράφει τη λίστα υπογραφών που έχει περάσει[`BaseSignature`](../../groupdocs.signature.domain/basesignature) από το έγγραφο. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Διαγράφει υπογραφές συγκεκριμένου τύπου[`SignatureType`](../../groupdocs.signature.domain/signaturetype) από το έγγραφο. Μόνο υπογραφές που προστέθηκαν με τη μέθοδο Sign και επισημάνθηκαν ως υπογραφές[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) θα αφαιρεθεί. Υποστηρίζονται οι ακόλουθοι τύποι υπογραφών: Κείμενο, Εικόνα, Ψηφιακός, Γραμμωτός κώδικας, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Διαγράφει την υπογραφή με το αναγνωριστικό της συγκεκριμένης υπογραφής από το έγγραφο. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Εφαρμογή διεπαφής IDisposable για εκκαθάριση εσωτερικών πόρων |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Δημιουργεί προεπισκόπηση σελίδων εγγράφου. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Λαμβάνει πληροφορίες σχετικά με τις σελίδες εγγράφων: τα μεγέθη τους, μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Αναζητά υπογραφές σε ένα έγγραφο από[`SearchOptions`](../../groupdocs.signature.options/searchoptions) λίστα. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Αναζητά συγκεκριμένους τύπους υπογραφών στο έγγραφο από[`SignatureType`](../../groupdocs.signature.domain/signaturetype) τιμή. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Αναζητά υπογραφές σε ένα έγγραφο από[`SearchOptions`](../../groupdocs.signature.options/searchoptions) επιλογές. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Αναζητά τον ακριβή τύπο υπογραφών στο έγγραφο από[`SignatureType`](../../groupdocs.signature.domain/signaturetype) τιμή. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Υπογράφει έγγραφο με συλλογή από[`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Υπογράφει έγγραφο με[`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε μια ροή. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Υπογράφει έγγραφο με συλλογή από[`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε καθορισμένη διαδρομή αρχείου. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Υπογράφει έγγραφο με[`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε καθορισμένη διαδρομή αρχείου. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Υπογράφει έγγραφο με συλλογή από[`SignOptions`](../../groupdocs.signature.options/signoptions)και αποθηκεύει το αποτέλεσμα σε μια ροή με προκαθορισμένα[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Υπογράφει έγγραφο με[`SignOptions`](../../groupdocs.signature.options/signoptions)και αποθηκεύει το αποτέλεσμα σε μια ροή με προκαθορισμένα[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Υπογράφει έγγραφο με συλλογή από[`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε καθορισμένη διαδρομή αρχείου με προκαθορισμένη[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Υπογράφει έγγραφο με[`SignOptions`](../../groupdocs.signature.options/signoptions) και αποθηκεύει το αποτέλεσμα σε καθορισμένη διαδρομή αρχείου με προκαθορισμένη[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Ενημερώνει την υπογραφή που πέρασε[`BaseSignature`](../../groupdocs.signature.domain/basesignature) στο έγγραφο. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Ενημερώνει τις περασμένες υπογραφές[`BaseSignature`](../../groupdocs.signature.domain/basesignature) στο έγγραφο. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Επαληθεύει τις υπογραφές εγγράφων με λίστα δεδομένων VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Επαληθεύει τις υπογραφές εγγράφων με δεδομένα VerifyOptions. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Δημιουργεί προεπισκόπηση υπογραφής με βάση δεδομένες SignOptions.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Εκδηλώσεις

| Ονομα | Περιγραφή |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Εμφανίζεται όταν ολοκληρωθεί η διαδικασία αναζήτησης υπογραφών. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Εμφανίζεται όταν άλλαξε η πρόοδος της διαδικασίας αναζήτησης υπογραφών. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Εμφανίζεται όταν ξεκίνησε η διαδικασία αναζήτησης υπογραφών. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Εμφανίζεται όταν ολοκληρωθεί η διαδικασία υπογραφής εγγράφων. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Εμφανίζεται όταν άλλαξε η πρόοδος της διαδικασίας υπογραφής εγγράφων. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Εμφανίζεται όταν ξεκίνησε η διαδικασία υπογραφής εγγράφων. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Εμφανίζεται όταν ολοκληρωθεί η διαδικασία επαλήθευσης υπογραφής. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Εμφανίζεται όταν άλλαξε η πρόοδος της διαδικασίας επαλήθευσης υπογραφής. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Εμφανίζεται όταν ξεκίνησε η διαδικασία επαλήθευσης υπογραφής. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα για το GroupDocs.Δυνατότητες υπογραφής: [GroupDocs.Signature Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Signature](../../groupdocs.signature)
* συνέλευση [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
