---
title: "VerificationResult Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt eine Instanz dar, die Ergebnisse des Verifizierungsprozesses speichert."
type: docs
url: /de/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Stellt eine Instanz dar, die Ergebnisse des Verifizierungsprozesses speichert.

Der VerificationResult‑Typ stellt die folgenden Mitglieder bereit:

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | Die Ziel-Dokumentgröße. Für die Verifikation enthält diese Variable immer Null. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | Die Liste der Signaturen, die den Verifikationsvorgang nicht bestanden haben. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Das Verifikationsergebnis; True, wenn der Verifikationsvorgang erfolgreich war, sonst False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | Die Ausführungszeit des Prozesses in Millisekunden. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | Die Quell-Dokumentgröße in Bytes. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | Die Liste der erfolgreich verifizierten Signaturen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | Die Gesamtzahl der verarbeiteten Signaturen. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
