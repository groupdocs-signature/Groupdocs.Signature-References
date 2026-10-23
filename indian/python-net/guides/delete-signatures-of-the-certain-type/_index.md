---
title: "निश्चित प्रकार के हस्ताक्षर हटाएँ"
linkTitle: "Certain Type"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह लेख समझाता है कि कैसे GroupDocs.Signature API के साथ निश्चित प्रकार के इलेक्ट्रॉनिक हस्ताक्षर हटाएँ।"
type: docs
url: /hi/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
कृपया ध्यान दें कि [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) मेथड उसी दस्तावेज़ को संशोधित करता है जो [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) क्लास के कंस्ट्रक्टर को पास किया गया था, इसलिए नीचे दिया गया उदाहरण पहले साइन किए गए दस्तावेज़ की एक प्रति बनाता है और फिर उस प्रति से हस्ताक्षर हटाता है।

## How to delete signatures of the certain type from the document
GroupDocs.Signature के साथ दस्तावेज़ से निश्चित प्रकार के हस्ताक्षर हटाने के चरण यहाँ हैं:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

यह उदाहरण दिखाता है कि कैसे दस्तावेज़ से सभी टेक्स्ट हस्ताक्षर हटाएँ। केवल वे हस्ताक्षर हटाए जाते हैं जो GroupDocs.Signature ने जोड़े थे; दस्तावेज़ का अपना टेक्स्ट जैसा का वैसा रहता है।

{{< tabs \"delete_signatures_by_type\" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # delete() खुले दस्तावेज़ में बदलाव सहेजता है, इसलिए एक प्रति पर काम करें
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # दस्तावेज़ में सभी टेक्स्ट हस्ताक्षर हटाएँ
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab \"signed.docx\" >}}

`signed.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) पर क्लिक करें।

{{< /tab >}}
{{< tab \"all_text_signatures_deleted.docx\" >}}
```text
Binary file (DOCX, 147 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/delete_signatures_by_type/all_text_signatures_deleted.docx)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

आप ऊपर दिया गया कोड आसानी से चला सकते हैं और हमारे GitHub उदाहरणों में इस सुविधा को कार्य में देख सकते हैं:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

पूरी तरह से फीचरयुक्त Python लाइब्रेरी के साथ, हम सरल लेकिन शक्तिशाली मुफ्त ऑनलाइन ऐप्स भी प्रदान करते हैं।

PDF, Word, Excel, PowerPoint, और अन्य दस्तावेज़ों पर हस्ताक्षर करने के लिए आप ऑनलाइन ऐप्स **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** से उपयोग कर सकते हैं।
