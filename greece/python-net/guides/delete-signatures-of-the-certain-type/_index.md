---
title: "Διαγραφή υπογραφών συγκεκριμένου τύπου"
linkTitle: "Certain Type"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αυτό το άρθρο εξηγεί πώς να διαγράψετε ηλεκτρονικές υπογραφές συγκεκριμένου τύπου με το GroupDocs.Signature API."
type: docs
url: /el/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
Παρακαλούμε λάβετε υπόψη ότι η μέθοδος [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) τροποποιεί το ίδιο έγγραφο που περάστηκε στον κατασκευαστή της κλάσης [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature), επομένως το παρακάτω παράδειγμα αντιγράφει πρώτα το υπογεγραμμένο έγγραφο και διαγράφει τις υπογραφές από το αντίγραφο.

## How to delete signatures of the certain type from the document
Ακολουθούν τα βήματα για τη διαγραφή υπογραφών συγκεκριμένου τύπου από το έγγραφο με το GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

Αυτό το παράδειγμα δείχνει πώς να διαγράψετε όλες τις υπογραφές κειμένου από το έγγραφο. Διαγράφονται μόνο οι υπογραφές που πρόσθεσε το GroupDocs.Signature· το δικό κείμενο του εγγράφου παραμένει όπως είναι.

{{< tabs \"delete_signatures_by_type\" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # Η μέθοδος delete() αποθηκεύει τις αλλαγές στο ανοιχτό έγγραφο, γι' αυτό δουλέψτε σε ένα αντίγραφο
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # Διαγραφή κάθε υπογραφής κειμένου στο έγγραφο
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab \"signed.docx\" >}}

`signed.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) για να το κατεβάσετε.

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

Μπορείτε εύκολα να εκτελέσετε τον παραπάνω κώδικα και να δείτε τη λειτουργία σε δράση στα παραδείγματα μας στο GitHub:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Μαζί με τη πλήρη βιβλιοθήκη Python, παρέχουμε απλές αλλά ισχυρές δωρεάν διαδικτυακές εφαρμογές.

Για να υπογράψετε PDF, Word, Excel, PowerPoint και άλλα έγγραφα, μπορείτε να χρησιμοποιήσετε τις διαδικτυακές εφαρμογές από την **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
