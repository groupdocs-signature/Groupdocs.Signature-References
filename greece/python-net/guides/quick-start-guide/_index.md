---
title: "Οδηγός Γρήγορης Εκκίνησης"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Ρυθμίστε ένα εικονικό περιβάλλον, εγκαταστήστε το groupdocs-signature-net και εκτελέστε τρία ελάχιστα παραδείγματα: υπογράψτε ένα PDF με υπογραφή κειμένου, αναζητήστε υπογραφές σε αυτό και επαληθεύστε τις."
type: docs
url: /el/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Αυτός ο οδηγός παρέχει μια γρήγορη επισκόπηση του πώς να ρυθμίσετε και να αρχίσετε να χρησιμοποιείτε το GroupDocs.Signature for Python via .NET. Η βιβλιοθήκη προσθέτει, βρίσκει, επαληθεύει, ενημερώνει και αφαιρεί ηλεκτρονικές υπογραφές σε αρχεία PDF, Word, Excel, PowerPoint, OpenDocument και εικόνας με λίγες γραμμές κώδικα.

## Prerequisites

Για να προχωρήσετε, βεβαιωθείτε ότι έχετε:

1. Ένα διαμορφωμένο περιβάλλον όπως περιγράφεται στο θέμα [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Σε Linux και macOS αυτό περιλαμβάνει μερικά πακέτα συστήματος.
2. Προαιρετικά, μια [Temporary License](https://purchase.groupdocs.com/temporary-license/) για δοκιμή όλων των λειτουργιών του προϊόντος. Χωρίς άδεια η βιβλιοθήκη λειτουργεί σε λειτουργία αξιολόγησης: επεξεργάζεται έγγραφα έως δύο σελίδες και προσθέτει μια γραμμή αξιολόγησης σε κάθε σελίδα που υπογράφει. Δείτε το [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

Για τις βέλτιστες πρακτικές, χρησιμοποιήστε ένα εικονικό περιβάλλον για τη διαχείριση των εξαρτήσεων. Μάθετε περισσότερα στον οδηγό [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Δημιουργήστε ένα εικονικό περιβάλλον:

{{< tabs "create-venv">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Ενεργοποιήστε το:

{{< tabs "activate-venv">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs "install-package">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

Δείτε το [Installation](/signature/python-net/guides/installation/) για καθορισμό έκδοσης και για εγκατάσταση χωρίς πρόσβαση στο PyPI.

## Example 1: Sign a PDF with a Text Signature

Ανοίξτε ένα έγγραφο, περιγράψτε την υπογραφή με το [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), και αποθηκεύστε το υπογεγραμμένο αντίγραφο.

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Ανοίξτε το έγγραφο· το μπλοκ with απελευθερώνει το αρχείο όταν ολοκληρωθεί
    with Signature("sample.pdf") as signature:
        # Μια υπογραφή κειμένου 100 εικονοστοιχεία από τις αριστερές και άνω άκρες της πρώτης σελίδας
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Υπογράψτε και αποθηκεύστε το αποτέλεσμα σε νέο αρχείο· η πηγή παραμένει αμετάβλητη
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Βρείτε τις υπογραφές που περιέχει ήδη ένα έγγραφο. Η `search` λαμβάνει μια λίστα επιλογών αναζήτησης, μία ανά τύπο υπογραφής προς αναζήτηση, και τις επιστρέφει στο `result.signatures`.

{{< tabs "search_document_for_signatures">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Αναζητήστε υπογραφές κειμένου σε κάθε σελίδα
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Ελέγξτε ότι ένα έγγραφο περιέχει την υπογραφή που αναμένετε. Η επαλήθευση είναι επιτυχής όταν βρεθεί μια υπογραφή κειμένου με ακριβώς αυτό το κείμενο.

{{< tabs "verify_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Αποθηκεύστε κάθε παράδειγμα σε δικό του αρχείο `.py` δίπλα στα αρχεία δείγματος. Ο φάκελός σας θα πρέπει να μοιάζει με αυτόν:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Εκτελέστε ένα παράδειγμα από αυτόν το φάκελο:

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

Όταν τελειώσετε, απενεργοποιήστε το εικονικό περιβάλλον εκτελώντας `deactivate` ή κλείνοντας το τερματικό σας.

## Apply a License

Ορίστε τη μεταβλητή περιβάλλοντος `GROUPDOCS_LIC_PATH` στη πλήρη διαδρομή του αρχείου άδειας σας, και η άδεια εφαρμόζεται αυτόματα όταν εισάγεται το `groupdocs.signature`. Δεν απαιτείται κώδικας. Εναλλακτικά, εφαρμόστε την στον κώδικα μία φορά, πριν από οποιαδήποτε άλλη κλήση:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

Το θέμα [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) καλύπτει και τις δύο μεθόδους και την άδεια με μέτρηση.

## Next Steps

Αφού ολοκληρώσετε τα βασικά, εξερευνήστε πρόσθετους πόρους:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
