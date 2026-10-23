---
title: "eSign Έγγραφο με Υπογραφή QR Code"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αυτό το άρθρο εξηγεί πώς να υπογράψετε έγγραφα με ηλεκτρονική υπογραφή ως QR code στη σελίδα του εγγράφου χρησιμοποιώντας το GroupDocs.Signature για Python μέσω .NET API."
type: docs
url: /el/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

Το QR code (ή Quick Response code) είναι ένα είδος δισδιάστατου [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) που αποτελείται από μαύρα τετράγωνα διατεταγμένα σε τετράγωνο πλέγμα πάνω σε λευκό φόντο. Τα QR codes μπορούν να διαβαστούν από κάμερες smartphone ή εξειδικευμένες συσκευές που είναι αφιερωμένες στην ανάγνωση QR - φορητά σαρωτές, φορητά τερματικά, επιτραπέζιους σαρωτές, ενσωματωμένους σαρωτές κ.λπ. Συνήθως τα QR codes περιέχουν δεδομένα που οδηγούν σε ιστοσελίδα ή εφαρμογή, email, ή αριθμούς τηλεφώνου, αναγνωριστικά προϊόντων ή ιχνηλάτες. Συνεπώς, το πεδίο εφαρμογών του QR code εκτείνεται από γενικό μάρκετινγκ και αναγνώριση αντικειμένων έως τη διαχείριση εγγράφων.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Κώδικας Aztec | Κωδικός DataMatrix | GS1 DataMatrix | GS1 QR κωδικός | QR |
| --- | --- | --- | --- | --- | --- |
| **Εφαρμογή** | * μεταφορά και έκδοση εισιτηρίων;<br> * στη βιομηχανία αεροπορίας για ηλεκτρονικές κάρτες επιβίβασης;<br> * στον σιδηρόδρομο για εισιτήρια που πωλούνται online και εκτυπώνονται από πελάτες ή εμφανίζονται σε οθόνες κινητών τηλεφώνων. Ο κωδικός σαρώνεται από φορητό σαρωτή από το προσωπικό του τρένου ή στο περβάζι για την επικύρωση του εισιτηρίου.<br> * ιατρική - βραχιόλια αναγνώρισης ασθενών και ετικέτες για φάρμακα μονάδας χρήσης κ.λπ. | * έντυπα όπως ετικέτες και γράμματα;<br> * βιομηχανικοί σκοποί μηχανικής - σήμανση εξαρτημάτων κ.λπ.;<br>  * βιομηχανία τροφίμων - για την πρόληψη λανθασμένης συσκευασίας και ημερομηνίας προϊόντων τροφίμων; | Χρησιμοποιείται σε<br> * Υγειονομική περίθαλψη;<br> * Κυβέρνηση;<br> * Βιομηχανία.<br> Κωδικοποιεί πρόσθετες πληροφορίες αντικειμένου, όπως:<br> * βάρος;<br> * ημερομηνία λήξης;<br> * αριθμός παρτίδας;<br> * ημερομηνία κατασκευής;<br> * κ.λπ. | Χρησιμοποιείται στο μάρκετινγκ για την κωδικοποίηση πρόσθετων πληροφοριών αντικειμένου στη συσκευασία | Χρησιμοποιείται εκτενώς στη βιομηχανία αυτοκινήτων και στις κινητές εφαρμογές. Χρήσιμο για την κωδικοποίηση μεγάλου όγκου χαρακτήρων δεδομένων και συγκεκριμένων URL. |
| **Μήκος** | 3067 αλφαριθμητικό,<br> 3832 αριθμητικό,<br> 1914 bytes | 2335 αλφαριθμητικό,<br> 3116 αριθμητικό | 2335 αλφαριθμητικό,<br> 3116 αριθμητικό,<br> 1556 bytes | 7089 αλφαριθμητικό,<br> 4296 αριθμητικό,<br> 2953 bytes | 4296 αλφαριθμητικό,<br> 7089 αριθμητικό,<br> 2953 bytes |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

Κατά την προσθήκη ηλεκτρονικής υπογραφής QR κωδικού σε ένα έγγραφο, οι κύριες ρυθμίσεις είναι το κείμενο που θα κωδικοποιηθεί και ο [τύπος του QR κωδικού](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) που πρέπει να καθοριστεί μέσω της κλάσης [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions).

Ακολουθούν τα βήματα για την ηλεκτρονική υπογραφή (eSign) ενός εγγράφου με την υπογραφή QR κωδικού:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

Το παρακάτω απόσπασμα κώδικα δείχνει πώς να υπογράψετε ένα PDF έγγραφο με την υπογραφή QR κωδικού χρησιμοποιώντας Python:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Δημιουργήστε επιλογές υπογραφής QR κωδικού με το κείμενο προς κωδικοποίηση
        options = QrCodeSignOptions("John Smith")

        # Ορίστε τον τύπο του QR κωδικού
        options.encode_type = QrCodeTypes.QR

        # Ορίστε τη θέση και το μέγεθος του QR κωδικού
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Υπογράψτε το έγγραφο και αποθηκεύστε το αποτέλεσμα
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_qr_code.pdf" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

Οι άλλοι τύποι QR κώδικα από τον παραπάνω πίνακα ορίζονται με τον ίδιο τρόπο, για παράδειγμα `QrCodeTypes.AZTEC` ή `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Ακολουθεί ένα παράδειγμα που δείχνει πώς να δημιουργήσετε μια πιο σύνθετη υπογραφή QR κώδικα με πρόσθετη προσαρμογή: στοίχιση και περιθώρια, χρώμα μονάδας, φόντο και περίγραμμα:

{{< tabs "sign_with_qr_code_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Περάστε το κείμενο και τον τύπο QR code στον κατασκευαστή
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Τοποθετήστε το QR code στην κάτω δεξιά γωνία της σελίδας
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Χρώμα μονάδας, φόντο και μια διακεκομμένη γραμμή περιγράμματος με κάποιο χώρο μέσα
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_qr_code_advanced.pdf" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Αυτός ο οδηγός δείχνει πώς να προσθέσετε υπογραφές QR κώδικα σε έγγραφα χρησιμοποιώντας [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Περιλαμβάνει βήματα για τη δημιουργία μιας υπογραφής QR κώδικα, τη διαμόρφωση των ιδιοτήτων της όπως το μέγεθος και η κωδικοποίηση, και την εφαρμογή της σε ένα έγγραφο. Οι υπογραφές QR κώδικα μπορούν να χρησιμοποιηθούν για γρήγορη επαλήθευση του υπογεγραμμένου εγγράφου.

## More Resources

### GitHub Examples

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματα μας στο GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python, παρέχουμε απλές αλλά ισχυρές δωρεάν διαδικτυακές εφαρμογές.

Για να δημιουργήσετε QR κώδικες και/ή να υπογράψετε τα αρχεία σας με QR κώδικες δωρεάν, μπορείτε να χρησιμοποιήσετε την online εφαρμογή [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode).

Για να υπογράψετε PDF, Word, Excel, PowerPoint και άλλα έγγραφα, μπορείτε να χρησιμοποιήσετε τις άλλες online εφαρμογές από την **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
