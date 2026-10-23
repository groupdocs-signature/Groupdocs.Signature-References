---
title: "μέθοδος get_document_info"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει πληροφορίες σχετικά με τις σελίδες του εγγράφου: τα μεγέθη τους, το μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος."
type: docs
url: /el/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Λαμβάνει πληροφορίες σχετικά με τις σελίδες του εγγράφου: τα μεγέθη τους, το μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος.

Μάθετε περισσότερα για το υπογεγραμμένο έγγραφο - τύπο αρχείου, αριθμό σελίδων και πολλές άλλες ιδιότητες ειδικές για τη μορφή:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Παράδειγμα

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # Το page_number είναι 0-βάση: 0 είναι η πρώτη σελίδα
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Δείτε επίσης
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
