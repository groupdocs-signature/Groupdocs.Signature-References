---
title: "Δημιουργία προεπισκόπησης υπογραφών"
linkTitle: "Generate signatures preview"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αυτό το θέμα εξηγεί πώς να δημιουργήσετε προεπισκόπηση υπογραφής εγγράφου σε Python με διάφορες επιλογές από το GroupDocs.Signature for Python via .NET."
type: docs
url: /el/python-net/guides/generate-signatures-preview/
is_root: false
weight: 120
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) class to generate an image of a signature before it is placed on a document - for example, to show a user what a text, barcode or QR code signature will look like.

Ακολουθούν τα βήματα για τη δημιουργία προεπισκόπησης υπογραφής με το GroupDocs.Signature:

* Create the sign options that describe the signature, for example [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/) or [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/). No document is needed.
* Instantiate the [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) object with:
* the sign options;
* a function that creates the stream for the signature image (see [CreateSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createsignaturestream/));
* image preview format - PNG / JPEG / BMP / GIF / SVG (PNG by default),
* an optional `signature_id` that tells the functions which signature they are handling.

Η ροή που επιστρέφεται από τη συνάρτηση create κλείνει αυτόματα μόλις γραφτεί η εικόνα της υπογραφής: ένα αρχείο κλείνει και ένα `io.BytesIO` ήδη περιέχει την πλήρη εικόνα. Εάν χρειαστεί να επεξεργαστείτε την τελική εικόνα ή να καθαρίσετε τους πόρους μόνοι σας, περάστε μια συνάρτηση release ως επιπλέον όρισμα (δείτε το [ReleaseSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasesignaturestream/)).

* Call the static `generate_signature_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) to it.

## CreateSignatureStream delegate implementation

Το GroupDocs.Signature καλεί τη συνάρτηση create με το αντικείμενο [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) και γράφει την εικόνα της υπογραφής στη ροή που επιστρέφει: ένα αντικείμενο αρχείου εγγραφής, ένα `io.BytesIO`, ή μια .NET ροή.

```python
def create_signature_stream(preview_options):
    # Ονομάστε την εικόνα με βάση το signature_id που ορίζεται στις επιλογές προεπισκόπησης
    return open(f"{preview_options.signature_id}.png", "wb")
```

## ReleaseSignatureStream delegate implementation

Η συνάρτηση release λαμβάνει τις ίδιες επιλογές προεπισκόπησης και το ίδιο αντικείμενο που επέστρεψε η συνάρτηση create. Μέχρι τη στιγμή που κληθεί, η εικόνα είναι πλήρης.

```python
def release_signature_stream(preview_options, signature_stream):
    # Το signature_stream είναι το αντικείμενο που επέστρεψε η create_signature_stream
    print(f"Image file {signature_stream.name} is ready for preview")
```

## Generate signature preview to an image file

{{< tabs "generate_signature_preview_to_file" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.pydrawing import Color
from groupdocs.signature.domain import SignatureFont
from groupdocs.signature.options import PreviewSignatureOptions, TextSignOptions

def create_signature_stream(preview_options):
    # Ονομάστε την εικόνα με βάση το signature_id που ορίζεται παρακάτω
    return open(f"{preview_options.signature_id}.png", "wb")

def release_signature_stream(preview_options, signature_stream):
    print(f"Image file {signature_stream.name} is ready for preview")

def generate_signature_preview_to_file():
    # Περιγράψτε την υπογραφή ακριβώς όπως θα κάνατε για την υπογραφή
    sign_options = TextSignOptions("John Smith")
    sign_options.width = 200
    sign_options.height = 50
    sign_options.fore_color = Color.dark_blue
    font = SignatureFont()
    font.family_name = "Arial"
    font.size = 24
    sign_options.font = font

    # Δημιουργήστε το αντικείμενο επιλογών προεπισκόπησης
    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream, release_signature_stream)
    preview_options.signature_id = "text_signature"
    preview_options.preview_format = PreviewSignatureOptions.PreviewFormats.PNG

    # Δημιουργήστε προεπισκόπηση· δεν εμπλέκεται κανένα έγγραφο
    Signature.generate_signature_preview(preview_options)

if __name__ == "__main__":
    generate_signature_preview_to_file()
```
{{< /tab >}}
{{< tab "text_signature.png" >}}
```text
Binary file (PNG, 983 bytes)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_preview_to_file/text_signature.png)
{{< /tab >}}
{{< /tabs >}}

## Generate signature preview to a memory stream

Η συνάρτηση create μπορεί να επιστρέψει ένα `io.BytesIO`. Όταν η `generate_signature_preview` επιστρέψει, η μνήμη buffer περιέχει ολόκληρη την εικόνα, έτοιμη να αποθηκευτεί ή να σταλεί αλλού.

{{< tabs "generate_signature_preview_to_memory" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Γράψτε την εικόνα στο buffer αντί για αρχείο
        return image

    sign_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
    sign_options.width = 120
    sign_options.height = 120

    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream)
    Signature.generate_signature_preview(preview_options)

    data = image.getvalue()
    is_png = data.startswith(b"\x89PNG")
    print(f"QR code preview: {len(data)} bytes, PNG image: {is_png}")

if __name__ == "__main__":
    generate_signature_preview_to_memory()
```
{{< /tab >}}
{{< tab "generate-signature-preview-to-memory.txt" >}}
```text
QR code preview: 918 bytes, PNG image: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_preview_to_memory/generate-signature-preview-to-memory.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate previews of several signatures in different formats

Ένα ζεύγος συναρτήσεων μπορεί να εξυπηρετήσει οποιονδήποτε αριθμό προεπισκοπήσεων: το `signature_id` τους λέει ποια υπογραφή διαχειρίζονται, και το `preview_format` επιλέγει τον τύπο εικόνας. Χωρίς άδεια, η μορφή SVG είναι διαθέσιμη μόνο για barcode Code39.

{{< tabs "generate_signature_previews_in_different_formats" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, QrCodeTypes
from groupdocs.signature.options import BarcodeSignOptions, PreviewSignatureOptions, QrCodeSignOptions

FORMATS = PreviewSignatureOptions.PreviewFormats

def create_signature_stream(preview_options):
    extension = preview_options.preview_format.name.lower()
    return open(f"{preview_options.signature_id}.{extension}", "wb")

def release_signature_stream(preview_options, signature_stream):
    print(f"{preview_options.signature_id}: {signature_stream.name}")

def generate_signature_previews_in_different_formats():
    signatures = [
        ("barcode", BarcodeSignOptions("123456789012", BarcodeTypes.CODE128), FORMATS.JPEG),
        ("qr_code", QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR), FORMATS.GIF),
        ("barcode_vector", BarcodeSignOptions("GROUPDOCS", BarcodeTypes.CODE39), FORMATS.SVG),
    ]
    for signature_id, sign_options, preview_format in signatures:
        preview_options = PreviewSignatureOptions(sign_options, create_signature_stream, release_signature_stream)
        preview_options.signature_id = signature_id
        preview_options.preview_format = preview_format
        Signature.generate_signature_preview(preview_options)

if __name__ == "__main__":
    generate_signature_previews_in_different_formats()
```
{{< /tab >}}
{{< tab "generate-signature-previews-in-different-formats-outputs.zip" >}}
```text
barcode.jpeg (8 KB)
barcode_vector.svg (3 KB)
qr_code.gif (4 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_previews_in_different_formats/generate-signature-previews-in-different-formats-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματα μας στο GitHub:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python, παρέχουμε απλές αλλά ισχυρές δωρεάν διαδικτυακές εφαρμογές.

Για να υπογράψετε PDF, Word, Excel, PowerPoint και άλλα έγγραφα, μπορείτε να χρησιμοποιήσετε τις διαδικτυακές εφαρμογές από την **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
