---
title: "eSign Έγγραφο με Υπογραφή Εικόνας"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αυτό το άρθρο δείχνει πώς να προσθέσετε εικόνα υπογραφής σε σελίδα εγγράφου με το GroupDocs.Signature για Python μέσω .NET."
type: docs
url: /el/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

Μια **image** ως υπογραφή είναι ένας εναλλακτικός τρόπος να τοποθετήσετε οποιαδήποτε παρουσιάζουσα δεδομένα σε οπτική μορφή. Αυτός ο τύπος ηλεκτρονικής υπογραφής επιτρέπει τη δημιουργία προσαρμοσμένων εικόνων με λογότυπο εταιρείας, αρχικά αποστολέα, ονόματα κ.λπ.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Ακολουθούν τα βήματα για τη δημιουργία υπογραφής εικόνας σε μια σελίδα εγγράφου:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Αυτό το παράδειγμα δείχνει πώς να υπογράψετε ένα PDF έγγραφο με την υπογραφή εικόνας χρησιμοποιώντας Python:

{{< tabs "sign_with_image_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Δημιουργήστε επιλογές υπογραφής εικόνας με το αρχείο εικόνας
        options = ImageSignOptions("signature.jpg")

        # Ορίστε τη θέση και το μέγεθος της υπογραφής
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # Υπογράψτε το έγγραφο και αποθηκεύστε το αποτέλεσμα
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_image.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

Μπορείτε να προσαρμόσετε περαιτέρω την υπογραφή εικόνας με πρόσθετες επιλογές: στοίχιση και περιθώρια, περιστροφή, διαφάνεια και ένα περίγραμμα. Όταν ορίζεται μια στοίχιση, αντικαθιστά τη συντεταγμένη `left` ή `top`, και το `margin` απομακρύνει την υπογραφή από την άκρη της σελίδας.

{{< tabs "sign_with_image_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # Τοποθετήστε την υπογραφή στην κάτω δεξιά γωνία της σελίδας
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Περιστρέψτε την εικόνα και κάντε την 20% διαφανή
        options.rotation_angle = 10
        options.transparency = 0.2

        # Σχεδιάστε ένα διακεκομμένο περίγραμμα γύρω από την εικόνα
        border = Border()
        border.color = Color.dark_green
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border

        result = signature.sign("signed_image_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_image_advanced.pdf" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

Μπορείτε επίσης να φορτώσετε την εικόνα υπογραφής από μια ροή. Κρατήστε τη ροή ανοιχτή μέχρι να επιστρέψει η `sign`:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # Φορτώστε την εικόνα υπογραφής από μια ροή
        with open("signature.jpg", "rb") as image_stream:
            options = ImageSignOptions(image_stream)
            options.left = 100
            options.top = 400
            options.width = 120
            options.height = 100

            result = signature.sign("signed_image_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Αυτός ο οδηγός δείχνει πώς να χρησιμοποιήσετε [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) για να προσθέσετε υπογραφές με εικόνα σε έγγραφα. Καλύπτει τη φόρτωση ενός εγγράφου, τη διαμόρφωση των ιδιοτήτων της υπογραφής εικόνας (όπως το μέγεθος, η θέση και η διαφάνεια), και την αποθήκευση του υπογεγραμμένου εγγράφου. Επίσης συζητούνται προχωρημένες επιλογές προσαρμογής, όπως η ρύθμιση της εμφάνισης της εικόνας και η ευθυγράμμιση της υπογραφής. Για περισσότερες πληροφορίες, εξερευνήστε σχετικούς πόρους υπογραφής εγγράφων.

## More Resources

### GitHub Examples

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματα μας στο GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python, παρέχουμε απλές αλλά ισχυρές δωρεάν διαδικτυακές εφαρμογές.

Για να δημιουργήσετε υπογραφές εικόνας και/ή να υπογράψετε τα αρχεία σας δωρεάν, μπορείτε να χρησιμοποιήσετε την online εφαρμογή [Generate Image](https://products.groupdocs.app/signature/generate/image).

Για να υπογράψετε PDF, Word, Excel, PowerPoint και άλλα έγγραφα, μπορείτε να χρησιμοποιήσετε τις άλλες online εφαρμογές από την **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
