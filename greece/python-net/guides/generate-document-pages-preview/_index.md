---
title: "Δημιουργία προεπισκόπησης σελίδων εγγράφου"
linkTitle: "Generate document pages preview"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αυτό το θέμα εξηγεί πώς να λάβετε προεπισκόπηση σελίδων εγγράφου ως εικόνες με διάφορες επιλογές από το GroupDocs.Signature για Python μέσω .NET."
type: docs
url: /el/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
Ακολουθούν τα βήματα για τη δημιουργία προεπισκόπησης εγγράφου με το GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

Η ροή που επιστρέφεται από τη συνάρτηση create κλείνει αυτόματα μόλις γραφτεί η εικόνα της σελίδας: ένα αρχείο κλείνει και ένα `io.BytesIO` ήδη περιέχει την πλήρη εικόνα. Εάν χρειάζεται να επεξεργαστείτε κάθε ολοκληρωμένη εικόνα ή να καθαρίσετε τους πόρους μόνοι σας, περάστε μια συνάρτηση release ως επιπλέον όρισμα (δείτε [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

Το GroupDocs.Signature καλεί τη συνάρτηση create μία φορά για κάθε σελίδα και γράφει την εικόνα της σελίδας στη ροή που επιστρέφει: ένα αντικείμενο αρχείου εγγραφής, ένα `io.BytesIO` ή μια ροή .NET. Το όρισμα `page_data` είναι ένα αντικείμενο [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) με το `page_number`, το `file_name` του εγγράφου και το `preview_format`.

Οι αριθμοί σελίδων είναι μηδενικής βάσης: το `page_data.page_number` είναι `0` για την πρώτη σελίδα του εγγράφου.

```python
def create_page_stream(page_data):
    # Μηδενική βάση: το preview_page_0.png είναι η πρώτη σελίδα
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

Όταν προεπισκοπείτε ένα αρχείο, η συνάρτηση καλείται για τις σελίδες κάθε εγγράφου σε αυτό. Οι αριθμοί σελίδων ξεκινούν ξανά από `0` για κάθε έγγραφο, επομένως χρησιμοποιήστε επίσης το `page_data.file_name` όταν ονομάζετε τις εικόνες.

## ReleasePageStream delegate implementation

Η συνάρτηση release λαμβάνει το ίδιο `page_data` και το ίδιο αντικείμενο που επέστρεψε η συνάρτηση create. Μέχρι τη στιγμή που καλείται, η εικόνα είναι ολοκληρωμένη.

```python
def release_page_stream(page_data, page_stream):
    # Το page_stream είναι το αντικείμενο που επέστρεψε η create_page_stream
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs "generate_document_preview" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Οι αριθμοί σελίδων είναι 0‑βάση: preview_page_0.png είναι η πρώτη σελίδα
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # Δημιουργήστε αντικείμενο επιλογών προεπισκόπησης: μία εικόνα PNG ανά σελίδα
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # Δημιουργήστε προεπισκόπηση
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "generate-document-preview-outputs.zip" >}}
```text
preview_page_0.png (75 KB)
preview_page_1.png (64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview/generate-document-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Generate document preview from stream with custom stream releasing delegate

Αυτό το παράδειγμα διαβάζει το έγγραφο από μια ροή και διατηρεί τις εικόνες των σελίδων στη μνήμη: η συνάρτηση create επιστρέφει ένα `io.BytesIO`, και η συνάρτηση release το λαμβάνει γεμάτο με την πλήρη εικόνα.

{{< tabs "generate_document_preview_from_stream" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Διατηρήστε κάθε εικόνα σελίδας στη μνήμη αντί να γράψετε ένα αρχείο
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream είναι το BytesIO που επιστράφηκε παραπάνω, ήδη περιέχοντας ολόκληρη την εικόνα.
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # Δημιουργήστε αντικείμενο επιλογών προεπισκόπησης με και τις δύο συναρτήσεις
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # Δημιουργήστε προεπισκόπηση
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "generate-document-preview-from-stream.txt" >}}
```text
Page 0: 276044 bytes of JPEG
Page 1: 224194 bytes of JPEG
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_from_stream/generate-document-preview-from-stream.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate preview of particular pages

Ορίστε `page_numbers` για να προεπισκοπήσετε μόνο ορισμένες σελίδες. Οι αριθμοί είναι 0‑βάση, έτσι το `[1]` επιλέγει τη δεύτερη σελίδα.

{{< tabs "generate_document_preview_of_selected_pages" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}.png", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_of_selected_pages():
    with Signature("sample.pdf") as signature:
        preview_options = PreviewOptions(create_page_stream, release_page_stream)
        # Οι αριθμοί σελίδων είναι 0‑βάση: το [1] είναι η δεύτερη σελίδα
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "preview_page_1.png" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

Η προεπιλεγμένη ανάλυση είναι 96 DPI. Περάστε την ανάλυση ως τρίτο όρισμα του [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/), ή ορίστε την ιδιότητα `resolution`.

{{< tabs "generate_document_preview_with_resolution" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}_150dpi.jpg", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_with_resolution():
    with Signature("sample.pdf") as signature:
        resolution = 150
        # Δημιουργήστε αντικείμενο επιλογών προεπισκόπησης: 150 DPI αντί της προεπιλεγμένης 96
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # Δημιουργήστε προεπισκόπηση
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "generate-document-preview-with-resolution-outputs.zip" >}}
```text
preview_page_0_150dpi.jpg (495 KB)
preview_page_1_150dpi.jpg (425 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_with_resolution/generate-document-preview-with-resolution-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματα μας στο GitHub:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python, παρέχουμε απλές αλλά ισχυρές δωρεάν διαδικτυακές εφαρμογές.

Για να υπογράψετε PDF, Word, Excel, PowerPoint και άλλα έγγραφα, μπορείτε να χρησιμοποιήσετε τις διαδικτυακές εφαρμογές από την **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
