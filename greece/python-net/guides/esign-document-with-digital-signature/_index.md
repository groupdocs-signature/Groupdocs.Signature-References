---
title: "Υπογράψτε Έγγραφο με Ψηφιακή Υπογραφή"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Μάθετε για τα οφέλη της χρήσης ψηφιακών υπογραφών για ασφαλή υπογραφή εγγράφων. Ανακαλύψτε πώς να προσθέσετε προγραμματιστικά ψηφιακές υπογραφές σε Python με οδηγίες βήμα προς βήμα."
type: docs
url: /el/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

Στη σύγχρονη ψηφιακή εποχή, η διασφάλιση της αυθεντικότητας και της ακεραιότητας των ηλεκτρονικών εγγράφων είναι κρίσιμη. Μία ιδιαίτερα αποτελεσματική μέθοδος για την επίτευξη αυτού είναι η χρήση ψηφιακών υπογραφών. Σε αυτόν τον οδηγό, θα εξερευνήσουμε τον κόσμο των ψηφιακών υπογραφών, εξηγώντας τι είναι, γιατί είναι απαραίτητες και πώς μπορείτε να χρησιμοποιήσετε το GroupDocs.Signature for Python via .NET για να υπογράψετε τα έγγραφά σας απρόσκοπτα.

## What is a Digital Signature?

Μια ψηφιακή υπογραφή είναι ένας κρυπτογραφικός μηχανισμός για την επαλήθευση της αυθεντικότητας και της ακεραιότητας των ηλεκτρονικών εγγράφων. Παρέχει ισχυρή διαβεβαίωση ότι το έγγραφο προέρχεται από έναν γνωστό αποστολέα και δεν έχει παραποιηθεί από μη εξουσιοδοτημένες πηγές. Οι ψηφιακές υπογραφές συνήθως αντιπροσωπεύονται από πιστοποιητικά που περιέχουν ιδιωτικά (για υπογραφή) και δημόσια (για επαλήθευση) κλειδιά. Διάφορα πρότυπα κρυπτογραφίας δημόσιου κλειδιού, όπως η μορφή PFX, χρησιμοποιούνται συνήθως για αυτόν τον σκοπό.
Η παρακάτω εικόνα δείχνει πώς φαίνεται μια ψηφιακή υπογραφή σε μια σελίδα εγγράφου PDF από προεπιλογή.

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

Τα ληγμένα και ακόμη μη έγκυρα πιστοποιητικά απορρίπτονται: `sign` προκαλεί το [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) με μήνυμα όπως "The signing certificate expired on ...". Για να υπογράψετε με τέτοιο πιστοποιητικό ούτως ή άλλως, ορίστε `allow_expired` ή `allow_not_yet_valid` σε `True`.

### Follow these steps to sign your documents with a digital signature

1. Εγκαταστήστε το πακέτο GroupDocs.Signature χρησιμοποιώντας pip:
```bash
pip install groupdocs-signature-net
```

2. Δημιουργήστε μια νέα παρουσία της κλάσης [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) και περάστε τη διαδρομή του πηγαίου εγγράφου ως παράμετρο κατασκευής.
3. Δημιουργήστε το αντικείμενο [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) με το απαιτούμενο πιστοποιητικό και τον κωδικό του.
4. Καλέστε τη μέθοδο [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) της παρουσίας της κλάσης [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) και περάστε το [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) σε αυτήν.

Το παρακάτω παράδειγμα δείχνει πώς να υπογράψετε ένα PDF έγγραφο με ψηφιακή ηλεκτρονική υπογραφή χρησιμοποιώντας Python. Μπορούμε να υπογράψουμε οποιαδήποτε άλλη υποστηριζόμενη μορφή εγγράφου με τον ίδιο τρόπο.

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Δημιουργήστε επιλογές ψηφιακής υπογραφής με το αρχείο πιστοποιητικού
        options = DigitalSignOptions("certificate.pfx")

        # Ορίστε τον κωδικό του πιστοποιητικού
        options.password = "1234567890"

        # Προαιρετικό: μια εικόνα που δείχνει την υπογραφή στη σελίδα
        options.image_file_path = "signature.jpg"

        # Ορίστε τη θέση της υπογραφής
        options.left = 100
        options.top = 400

        # Υπογράψτε το έγγραφο και αποθηκεύστε το αποτέλεσμα
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` είναι το δείγμα πιστοποιητικού που χρησιμοποιείται σε αυτό το παράδειγμα (κωδικός `1234567890`). Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_digital.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Μπορείτε να προσαρμόσετε περαιτέρω την ψηφιακή υπογραφή με πρόσθετες επιλογές: το μέγεθος της υπογραφής στη σελίδα, καθώς και τα στοιχεία επικοινωνίας, ο λόγος και η τοποθεσία που αποθηκεύονται σε αυτήν:

{{< tabs "sign_with_digital_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Περάστε το πιστοποιητικό και την εικόνα εμφάνισης στον κατασκευαστή
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Εμφανίστε την υπογραφή στη σελίδα, σε αυτή τη θέση και μέγεθος
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Πληροφορίες αποθηκευμένες στην υπογραφή
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` είναι το δείγμα πιστοποιητικού που χρησιμοποιείται σε αυτό το παράδειγμα (κωδικός `1234567890`). Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_digital_advanced.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

Μπορείτε επίσης να φορτώσετε το πιστοποιητικό από ροή. Κρατήστε τη ροή ανοιχτή μέχρι να επιστρέψει η λειτουργία `sign`:

{{< tabs "sign_with_certificate_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Φορτώστε το πιστοποιητικό από ροή
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Ορίστε τη θέση και το μέγεθος της υπογραφής
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` είναι το δείγμα πιστοποιητικού που χρησιμοποιείται σε αυτό το παράδειγμα (κωδικός `1234567890`). Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_digital_stream.pdf" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Αυτός ο οδηγός δείχνει πώς να χρησιμοποιήσετε το [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) για να υπογράψετε έγγραφα με ψηφιακές υπογραφές. Εξηγεί πώς να φορτώνετε έγγραφα, να διαμορφώνετε υπογραφές βασισμένες σε πιστοποιητικό και να αποθηκεύετε τα υπογεγραμμένα αρχεία με ασφάλεια. Καλύπτονται επίσης προχωρημένες λειτουργίες, όπως η εμφάνιση της υπογραφής και οι πληροφορίες που αποθηκεύονται στην υπογραφή. Ανατρέξτε σε σχετικούς πόρους για πρόσθετες λεπτομέρειες σχετικά με τις διαδικασίες ψηφιακής υπογραφής.

## More Resources

### GitHub Examples

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματα μας στο GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python, παρέχουμε απλές αλλά ισχυρές δωρεάν διαδικτυακές εφαρμογές.

Για να υπογράψετε PDF, Word, Excel, PowerPoint και άλλα έγγραφα, μπορείτε να χρησιμοποιήσετε τις διαδικτυακές εφαρμογές από την **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
