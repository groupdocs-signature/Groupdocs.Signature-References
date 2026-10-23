---
title: "SearchResult Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt das Ergebnis der Suche nach Unterschriften in einem angegebenen Dokument dar."
type: docs
url: /de/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Stellt das Ergebnis der Suche nach Unterschriften in einem angegebenen Dokument dar.

Der SearchResult-Typ stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Gibt einen Iterator über die Suchergebnisse zurück. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | Die Ziel‑Dokumentgröße, die für die Search‑Methode immer 0 ist. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | Die Liste der Signaturen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/), die den Suchvorgang nach Suchkriterien nicht bestanden haben. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | Die Ausführungszeit des Suchvorgangs in Millisekunden. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | Die Liste der gefundenen Signaturen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | Die Größe des Quelldokuments. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | Die Liste der gefundenen Signaturen ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Die Gesamtzahl der verarbeiteten Signaturen, die vom Suchvorgang zurückgegeben werden. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
