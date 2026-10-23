---
title: "فئة SearchResult"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل نتيجة البحث عن التوقيعات في مستند محدد."
type: docs
url: /ar/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

يمثل نتيجة البحث عن التوقيعات في مستند محدد.

يعرض نوع SearchResult الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | يعيد مكرّرًا على نتائج البحث. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | حجم المستند الوجهة، والذي يكون دائمًا 0 لطريقة Search. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | قائمة التوقيعات [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) التي فشلت في عملية البحث وفقًا لمعايير البحث. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | وقت تنفيذ عملية البحث بالمللي ثانية. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | قائمة التوقيعات التي تم العثور عليها [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | حجم المستند المصدر. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | قائمة التوقيعات التي تم العثور عليها ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | إجمالي عدد التوقيعات المعالجة التي أرجعتها عملية البحث. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
