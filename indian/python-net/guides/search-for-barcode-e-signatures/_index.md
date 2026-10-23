---
title: "बारकोड ई-हस्ताक्षर खोजें"
linkTitle: "Barcodes"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह लेख दस्तावेज़ पृष्ठों में बारकोड इलेक्ट्रॉनिक हस्ताक्षरों को खोजने के बारे में GroupDocs.Signature for Python के माध्यम से .NET API का उपयोग करके समझाता है।"
type: docs
url: /hi/python-net/guides/search-for-barcode-e-signatures/
is_root: false
weight: 100
---


[GroupDocs.Signature](https://products.groupdocs.com/signature/python-net) provides the ability to search for barcode signatures in documents. Barcode signatures can be used to store various types of information in a compact format.

## What is a Barcode Signature?

एक बारकोड हस्ताक्षर डेटा का एक दृश्य प्रतिनिधित्व है जिसे मशीनों द्वारा स्कैन और पढ़ा जा सकता है। यह आमतौर पर विभिन्न चौड़ाइयों वाले समानांतर काली रेखाओं और सफ़ेद स्थानों से बना होता है। बारकोड आमतौर पर उपयोग किए जाते हैं:
- Product identification
- Inventory tracking
- Document verification
- Data encoding

## How to Search for Barcode Signatures

यह [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class प्रदान करता है [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) method जो आपको दस्तावेज़ों में बारकोड हस्ताक्षरों को खोजने की अनुमति देता है। यहाँ इसका उपयोग कैसे करें:

1. नई instance बनाएं [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class की और स्रोत दस्तावेज़ पथ को पैरामीटर के रूप में पास करें।
2. आवश्यक विकल्पों के साथ [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) ऑब्जेक्ट को instantiate करें।
3. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance की [search](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/search/) method को कॉल करें और उसमें [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) की सूची पास करें।
4. खोज परिणामों को प्रोसेस करें: लौटाए गए [SearchResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/searchresult/) की `signatures` प्रॉपर्टी में पाए गए [BarcodeSignature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodesignature/) ऑब्जेक्ट्स होते हैं।

यहाँ एक उदाहरण है कि कैसे दस्तावेज़ में बारकोड हस्ताक्षरों को खोजा जाए:

{{< tabs "search_barcodes" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes():
    with Signature("signed.pdf") as signature:
        # दस्तावेज़ के सभी पृष्ठों में बारकोड हस्ताक्षरों को खोजें
        result = signature.search([BarcodeSearchOptions()])

        print(f"Found {len(result.signatures)} barcode signature(s)")
        for barcode in result.signatures:
            print(f"Page {barcode.page_number}: {barcode.encode_type.type_name} barcode '{barcode.text}' "
                  f"at ({barcode.left}, {barcode.top}), size {barcode.width}x{barcode.height}")

if __name__ == "__main__":
    search_barcodes()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab "search-barcodes.txt" >}}
```text
Found 2 barcode signature(s)
Page 1: Code128 barcode '123456789012' at (400, 375), size 170x45
Page 1: Code39 barcode 'JS-2026' at (400, 430), size 170x45
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes/search-barcodes.txt)
{{< /tab >}}
{{< /tabs >}}

## Advanced Search Options

यह [BarcodeSearchOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesearchoptions/) class खोज को संकीर्ण करने के लिए प्रॉपर्टीज़ प्रदान करती है:

- `encode_type` returns only barcodes of the given type, for example `BarcodeTypes.CODE128`;
- `text` and `match_type` return only barcodes whose text matches;
- `all_pages` and `page_number` search a single page instead of the whole document (page numbers start at 1);
- `return_content` and `return_content_type` also return the barcode image.

{{< tabs "search_barcodes_with_filters" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

def search_barcodes_with_filters():
    with Signature("signed.pdf") as signature:
        options = BarcodeSearchOptions()
        # केवल पहले पृष्ठ को खोजें
        options.all_pages = False
        options.page_number = 1
        # केवल Code 128 बारकोड लौटाएँ जिनका टेक्स्ट "1234" से शुरू होता है
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
{{< tab "signed.pdf" >}}

`signed.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/signed.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab "search-barcodes-with-filters.txt" >}}
```text
Found 1 matching barcode signature(s)
Page 1: Code128 barcode '123456789012'
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/search-for-electronic-signatures-in-document/search-for-barcode-e-signatures/search_barcodes_with_filters/search-barcodes-with-filters.txt)
{{< /tab >}}
{{< /tabs >}}

## Additional Resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे उदाहरणों में इस फीचर को कार्यरत देख सकते हैं:

* [GroupDocs.Signature for Python via .NET Examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)
* [GroupDocs.Signature for Python via .NET Plugins](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Plugins)
* [GroupDocs.Signature for Python via .NET Showcase Apps](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET-Showcase)

### Free Online Apps

पूरा Python लाइब्रेरी के साथ हम सरल लेकिन शक्तिशाली मुफ्त ऐप्स भी प्रदान करते हैं।

आप हमारे मुफ्त ऑनलाइन ऐप्स के साथ दस्तावेज़ों में बारकोड हस्ताक्षरों को खोज सकते हैं:

* [Search for Barcode Signatures Online](https://products.groupdocs.app/signature/family)
