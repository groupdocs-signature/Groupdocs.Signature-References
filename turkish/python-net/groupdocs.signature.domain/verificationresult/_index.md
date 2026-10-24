---
title: "VerificationResult sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Doğrulama sürecinin sonuçlarını tutan bir örneği temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Doğrulama sürecinin sonuçlarını tutan bir örneği temsil eder.

VerificationResult türü aşağıdaki üyeleri içerir:

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | Hedef belge boyutu. Doğrulama için bu değişken her zaman sıfır içerir. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | Doğrulama sürecinde başarısız olan imzaların listesi. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Doğrulama sonucu; doğrulama süreci başarılıysa True, aksi takdirde False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | İşlemin milisaniye cinsinden yürütme süresi. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | Kaynak belge boyutu bayt cinsinden. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | Başarıyla doğrulanan imzaların listesi [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | İşlenen imzaların toplam sayısı. |

### Örnek

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

### Ayrıca Bakınız
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
