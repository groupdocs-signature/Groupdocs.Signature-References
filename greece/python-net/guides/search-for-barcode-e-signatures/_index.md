---
title: "Αναζήτηση για Barcode e-Υπογραφές"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αυτό το άρθρο εξηγεί πώς να αναζητήσετε ηλεκτρονικές υπογραφές barcode μέσα στις σελίδες εγγράφων χρησιμοποιώντας το GroupDocs.Signature για Python μέσω .NET API"
type: docs
url: /el/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

Μια υπογραφή barcode είναι μια οπτική αναπαράσταση δεδομένων που μπορεί να σαρωθεί και να διαβαστεί από μηχανές. Συνήθως αποτελείται από παράλληλες μαύρες γραμμές και λευκά κενά διαφορετικού πλάτους. Τα barcode χρησιμοποιούνται συνήθως για:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

Η κλάση [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) παρέχει τη μέθοδο [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) που σας επιτρέπει να αναζητήσετε υπογραφές barcode σε έγγραφα. Να πώς να τη χρησιμοποιήσετε:

1. Δημιουργήστε μια νέα παρουσία της κλάσης [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) και περάστε τη διαδρομή του πηγαίου εγγράφου ως παράμετρο.
2. Δημιουργήστε το αντικείμενο [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) με τις απαιτούμενες επιλογές.
3. Καλέστε τη μέθοδο [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) της παρουσίας της κλάσης [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) και περάστε μια λίστα με τα [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) σε αυτήν.
4. Επεξεργαστείτε τα αποτελέσματα της αναζήτησης: η ιδιότητα `signatures` του επιστρεφόμενου [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) περιέχει τα αντικείμενα [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) που βρέθηκαν.

Ακολουθεί ένα παράδειγμα για το πώς να αναζητήσετε υπογραφές barcode σε ένα έγγραφο:

{{< tabs \"search_barcodes\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # Αναζήτηση σε όλες τις σελίδες του εγγράφου για υπογραφές barcode
        result = signature.search([BarcodeSearchOptions()])

        print(f"Found {len(result.signatures)} barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}' "
                  f"at ({barcode.left}, {barcode.top}), size {barcode.width}x{barcode.height}")

if __name__ == "__main__":
    search_barcodes()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"search-barcodes.txt\" >}}
```text
Found 2 barcode signature(s)
Page 1: Code128 barcode '123456789012' at (400, 375), size 170x45
Page 1: Code39 barcode 'JS-2026' at (400, 430), size 170x45
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes/search-barcodes.txt)
{{< /tab >}}
{{< /tabs >}}

## Advanced Search Options

Η κλάση [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) παρέχει ιδιότητες για να περιορίσετε την αναζήτηση:

- `encode_type` returns only barcodes of the given type, for example `BarcodeTypes.CODE128`;
- `text` and `match_type` return only barcodes whose text matches;
- `all_pages` and `page_number` search a single page instead of the whole document (page numbers start at 1);
- `return_content` and `return_content_type` also return the barcode image.

{{< tabs \"search_barcodes_with_filters\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes_with_filters():
    with Signature("signed.pdf") as signature:
        options = BarcodeSearchOptions()
        # Αναζήτηση μόνο στην πρώτη σελίδα
        options.all_pages = False
        options.page_number = 1
        # Επιστροφή μόνο των barcode Code 128 των οποίων το κείμενο αρχίζει με \"1234\"
        options.encode_type = BarcodeTypes.CODE128
        options.text = "1234"
        options.match_type = TextMatchType.STARTS_WITH

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}'")

if __name__ == "__main__":
    search_barcodes_with_filters()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"search-barcodes-with-filters.txt\" >}}
```text
Found 1 matching barcode signature(s)
Page 1: Code128 barcode '123456789012'
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes_with_filters/search-barcodes-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## Additional Resources

### GitHub Examples

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματά μας:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python παρέχουμε απλές αλλά ισχυρές δωρεάν Εφαρμογές.

Καλώς ήρθατε να αναζητήσετε υπογραφές barcode σε έγγραφα με τις δωρεάν διαδικτυακές μας εφαρμογές:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
