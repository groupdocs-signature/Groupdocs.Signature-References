---
title: "Έγγραφο eSign με Υπογραφή Κειμένου"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αυτό το άρθρο εξηγεί πώς να υπογράψετε ένα έγγραφο με υπογραφή Κειμένου χρησιμοποιώντας το GroupDocs.Signature for Python via .NET API. Μάθετε πώς να προσθέσετε μια ψηφιακή υπογραφή σε ένα PDF προγραμματιστικά σε Python."
type: docs
url: /el/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

Μια ηλεκτρονική υπογραφή **Text** είναι ένα αυθαίρετο κείμενο που προστίθεται σε ένα έγγραφο με εγγενή τρόπο, ανάλογα με τον τύπο του εγγράφου. Το GroupDocs.Signature παρέχει τη λειτουργία υπογραφής κειμένου και επιτρέπει την προσαρμογή μιας ευρείας γκάμας ρυθμίσεων κειμένου - από το όνομα, το μέγεθος και το χρώμα της γραμματοσειράς έως την ευθυγράμμιση, τα πλαίσια, τα εφέ σκιάς κ.λπ. Έτσι μπορεί να φαίνεται μια υπογραφή κειμένου:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Ας προσπαθήσουμε να προσθέσουμε μια υπογραφή κειμένου σε ένα PDF προγραμματιστικά χρησιμοποιώντας Python.

Για να χειριστείτε υπογραφές κειμένου προγραμματιστικά, το [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) παρέχει την κλάση [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) και η πλήρης ροή εργασίας είναι τόσο απλή όσο φαίνεται παρακάτω:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Αυτό το παράδειγμα δείχνει πώς να προσθέσετε μια υπογραφή κειμένου σε ένα έγγραφο χρησιμοποιώντας Python:

{{< tabs "sign_with_text_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Δημιουργήστε επιλογές υπογραφής κειμένου
        options = TextSignOptions("John Smith")

        # Ορίστε τη θέση και το μέγεθος της υπογραφής
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Ορίστε το χρώμα και τη γραμματοσειρά του κειμένου
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Υπογράψτε το έγγραφο και αποθηκεύστε το αποτέλεσμα
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Μπορείτε να προσαρμόσετε περαιτέρω την υπογραφή κειμένου με πρόσθετες επιλογές: ευθυγράμμιση και περιθώρια, στυλ γραμματοσειράς, φόντο, περίγραμμα, περιστροφή και διαφάνεια. Όταν ορίζεται μια ευθυγράμμιση, αντικαθιστά τη συντεταγμένη `left` ή `top`, και το `margin` μετατοπίζει την υπογραφή από την άκρη της σελίδας.

{{< tabs "sign_with_text_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # Τοποθετήστε την υπογραφή στην κάτω δεξιά γωνία της σελίδας
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Στυλ γραμματοσειράς και χρώμα κειμένου
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Φόντο, περίγραμμα, περιστροφή και διαφάνεια
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # Αποδώστε το κείμενο ως εικόνα, η οποία επίσης σχεδιάζει το περίγραμμα στις σελίδες PDF
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"signed_text_advanced.pdf\" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Αυτός ο οδηγός εξηγεί πώς να προσθέσετε υπογραφές κειμένου σε έγγραφα με [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Καλύπτει τη διαμόρφωση των ιδιοτήτων κειμένου όπως γραμματοσειρά, χρώμα, μέγεθος και θέση, και την εφαρμογή της υπογραφής κειμένου σε ένα έγγραφο. Το υπογεγραμμένο έγγραφο αποθηκεύεται στη συνέχεια με την προστιθέμενη υπογραφή κειμένου.

## More Resources

### GitHub Examples

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματα μας στο GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python, παρέχουμε απλές αλλά ισχυρές δωρεάν διαδικτυακές εφαρμογές.

Για να υπογράψετε PDF, Word, Excel, PowerPoint και άλλα έγγραφα, μπορείτε να χρησιμοποιήσετε τις διαδικτυακές εφαρμογές από την **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
