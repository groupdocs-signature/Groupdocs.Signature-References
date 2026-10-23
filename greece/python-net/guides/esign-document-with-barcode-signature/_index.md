---
title: "Ηλεκτρονική υπογραφή εγγράφου με υπογραφή Barcode"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αυτό το άρθρο εξηγεί πώς να προσθέσετε υπογραφή Barcode σε σελίδα εγγράφου με διάφορες επιλογές όπως τύπος barcode, κείμενο barcode, τοποθέτηση, στοίχιση και άλλες οπτικές ρυθμίσεις με GroupDocs.Signature για Python μέσω .NET"
type: docs
url: /el/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

Ένα **barcode** ή **bar code** είναι ένας τρόπος παρουσίασης δεδομένων σε οπτική, μηχανικά αναγνώσιμη μορφή. Γενικά, το barcode είναι μια εικόνα ορθογώνιας μορφής που αποτελείται από παράλληλες μαύρες γραμμές και λευκά κενά διαφορετικού πλάτους.
Τα Barcodes χρησιμοποιούνται σε διάφορους τομείς όπου απαιτείται γρήγορη ταυτοποίηση - ως μέρος της διαδικασίας αγοράς σε καταστήματα λιανικής, σε αποθήκες για παρακολούθηση αποθεμάτων, και σε τιμολόγια για βοήθεια στη λογιστική, μεταξύ πολλών άλλων χρήσεων.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Τα Barcodes επιτρέπουν την αποθήκευση δεδομένων σχετικών με το προϊόν όπως ημερομηνίες κατασκευής και λήξης, όνομα κατασκευαστή, χώρα προέλευσης και τιμή προϊόντος. Υπάρχουν πολλές τύποι barcode σήμερα επειδή διαφορετικές εταιρείες χρησιμοποιούν διαφορετικούς συνδυασμούς αριθμών και γραμμών στα barcodes τους ανάλογα με τις ανάγκες τους. Από την προοπτική της υπογραφής εγγράφου, το Barcode μπορεί να περιέχει διαφορετικούς χαρακτήρες (γράμματα, ψηφία ή σύμβολα) και μπορεί να έχει διάφορα μήκη και μεγέθη ανάλογα με τον τύπο και τις ρυθμίσεις για τη διατήρηση πληροφοριών υπογραφής, τίτλου, θέματος ή σύντομων κρυπτογραφημένων δεδομένων.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Για να καθορίσετε διαφορετικές επιλογές για την υπογραφή Barcode, το GroupDocs.Signature για Python μέσω .NET παρέχει την κλάση [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). Τα κύρια πεδία είναι:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

Ακολουθούν τα βήματα για την ηλεκτρονική υπογραφή ενός εγγράφου με την υπογραφή Barcode χρησιμοποιώντας το GroupDocs.Signature για Python μέσω .NET API:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Αυτό το παράδειγμα δείχνει πώς να υπογράψετε ένα PDF έγγραφο με υπογραφή Barcode χρησιμοποιώντας Python:

{{< tabs "sign_with_barcode_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Δημιουργήστε επιλογές υπογραφής barcode με το κείμενο προς κωδικοποίηση
        options = BarcodeSignOptions("John Smith")

        # Ορίστε τον τύπο barcode
        options.encode_type = BarcodeTypes.CODE128

        # Ορίστε τη θέση και το μέγεθος του barcode
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Υπογράψτε το έγγραφο και αποθηκεύστε το αποτέλεσμα
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Μπορείτε να προσαρμόσετε περαιτέρω την υπογραφή barcode με πρόσθετες επιλογές: στοίχιση και περιθώρια, χρώμα γραμμής, θέση του κωδικοποιημένου κειμένου, εσωτερικά περιθώρια, φόντο, περίγραμμα και διαφάνεια:

{{< tabs "sign_with_barcode_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Περάστε το κείμενο και τον τύπο barcode στον κατασκευαστή
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Τοποθετήστε το barcode στην κάτω δεξιά γωνία της σελίδας
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Χρώμα γραμμής, κωδικοποιημένο κείμενο κάτω από τις γραμμές, χώρος μέσα στο περίγραμμα
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Φόντο, περίγραμμα και διαφάνεια
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

Το GroupDocs.Signature υποστηρίζει διάφορους τύπους barcode. Κάθε τύπος δέχεται το δικό του σύνολο χαρακτήρων και μηκών, επομένως επιλέξτε το κείμενο που ταιριάζει στον τύπο. Αυτό το παράδειγμα υπογράφει ένα έγγραφο με τέσσερα barcodes διαφορετικών τύπων σε μία κλήση:

{{< tabs "sign_with_different_barcode_types" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # Ένα αντικείμενο επιλογών υπογραφής ανά barcode, τοποθετημένο το ένα κάτω από το άλλο
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Αυτός ο οδηγός δείχνει πώς να χρησιμοποιήσετε [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) για να προσθέσετε υπογραφές με barcode σε έγγραφα. Καλύπτει τη δημιουργία, τη διαμόρφωση και την εφαρμογή υπογραφών barcode με υποστήριξη διαφόρων τύπων barcode και επιλογών προσαρμογής. Για περαιτέρω εξερεύνηση, ανατρέξτε στους σχετικούς οδηγούς σχετικά με τις πληροφορίες εγγράφων και τις προχωρημένες τεχνικές υπογραφής.

## More Resources

### GitHub Examples

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματα μας στο GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python, παρέχουμε απλές αλλά ισχυρές δωρεάν διαδικτυακές εφαρμογές.

Για να δημιουργήσετε barcode και/ή να υπογράψετε τα αρχεία σας με barcode δωρεάν, μπορείτε να χρησιμοποιήσετε την online εφαρμογή [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode).

Για να υπογράψετε PDF, Word, Excel, PowerPoint και άλλα έγγραφα, μπορείτε να χρησιμοποιήσετε τις άλλες online εφαρμογές από την **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
