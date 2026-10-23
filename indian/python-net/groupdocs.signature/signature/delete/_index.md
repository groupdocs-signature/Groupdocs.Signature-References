---
title: "delete मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ से निर्दिष्ट BaseSignature को हटाता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

दस्तावेज़ से निर्दिष्ट [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) को हटाता है।

और अधिक जानें:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature | `BaseSignature` | दस्तावेज़ से हटाने के लिए BaseSignature ऑब्जेक्ट। |

**Returns:** bool: True if the operation was successful, otherwise False.

### उदाहरण

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() खुले दस्तावेज़ में बदलाव सहेजता है, इसलिए एक प्रति पर काम करें
    shutil.copy("signed.docx", "text_signature_deleted.docx")
    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return
        if signature.delete(signatures[0]):
            print("Signature deleted")
```

## delete {#signatures}

दस्तावेज़ से प्रदान की गई हस्ताक्षरों की सूची को हटाता है।

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | दस्तावेज़ से हटाने के लिए हस्ताक्षरों की सूची। |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### उदाहरण

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # एक प्रति पर काम करें क्योंकि delete() खुले दस्तावेज़ में बदलाव सहेजता है
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # पहला मिला हुआ हस्ताक्षर हटाएँ
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

दस्तावेज़ से निर्दिष्ट प्रकार के हस्ताक्षर हटाता है।

केवल वे हस्ताक्षर जो `Sign` मेथड द्वारा जोड़े गए थे और हस्ताक्षर के रूप में चिह्नित हैं ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) हटाए जाएंगे। समर्थित हस्ताक्षर प्रकार हैं टेक्स्ट, इमेज, डिजिटल, बारकोड, और QR‑कोड।

```python
def delete(self, signature_type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature_type | `SignatureType` | दस्तावेज़ से हटाने के लिए हस्ताक्षरों का प्रकार। |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| उठाता है | विवरण |
| :- | :- |
| `Remarks` | - अधिक जानें: - C# में दस्तावेज़ से इलेक्ट्रॉनिक हस्ताक्षर कैसे हटाएँ, इस बारे में अधिक: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - दस्तावेज़ eSignatures को हटाने के उन्नत उपयोग मामलों के लिए: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

दस्तावेज़ से निर्दिष्ट `SignatureType` सूची के हस्ताक्षर हटाता है।

केवल वे हस्ताक्षर जो `Sign` मेथड द्वारा जोड़े गए थे और हस्ताक्षर के रूप में चिह्नित हैं ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) हटाए जाएंगे। समर्थित हस्ताक्षर प्रकार हैं टेक्स्ट, इमेज, डिजिटल, बारकोड, और QR‑कोड।

और अधिक जानें
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | दस्तावेज़ से हटाने के लिए हस्ताक्षर प्रकारों की सूची। |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

दस्तावेज़ से उसके विशिष्ट हस्ताक्षर Id द्वारा एक हस्ताक्षर हटाता है।

और अधिक जानें:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature_id | `str` | दस्तावेज़ से हटाने के लिए हस्ताक्षर की Id। |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

दस्तावेज़ से निर्दिष्ट हस्ताक्षर हटाता है।

और अधिक जानें:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature_ids | `List[str]` | दस्तावेज़ से हटाने के लिए हस्ताक्षरों के पहचानकर्ताओं की सूची। |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### उदाहरण

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # एक प्रति पर काम करें क्योंकि delete() खुले दस्तावेज़ में बदलाव सहेजता है
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return

        text_signature = signatures[0]
        result = signature.delete([text_signature.id])
        if result.successful:
            print(f"Deleted text signature '{text_signature.text}'")
        else:
            print(f"Failed to delete text signature '{text_signature.text}'")
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
