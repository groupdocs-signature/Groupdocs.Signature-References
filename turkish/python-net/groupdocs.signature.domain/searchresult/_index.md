---
title: "SearchResult sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belirtilen belgede imzaları arama sonucunu temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Belirtilen belgede imzaları arama sonucunu temsil eder.

SearchResult türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Arama sonuçları üzerinde bir yineleyici döndürür. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | Hedef belge boyutu, Search yöntemi için her zaman 0'dır. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | Arama kriterlerine göre arama sürecinde başarısız olan imzaların listesi [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | Arama sürecinin milisaniye cinsinden yürütme süresi. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | Bulunan imzaların listesi [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | Kaynak belge boyutu. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | Bulunan imzaların listesi ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Arama süreci tarafından döndürülen işlenen imzaların toplam sayısı. |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
