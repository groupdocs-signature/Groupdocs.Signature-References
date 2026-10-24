---
title: "VerificationResult класс"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет экземпляр, сохраняющий результаты процесса проверки."
type: docs
url: /ru/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Представляет экземпляр, сохраняющий результаты процесса проверки.

Тип VerificationResult раскрывает следующие члены:

### Свойства
| Свойство | Описание |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | Размер целевого документа. Для проверки эта переменная всегда содержит ноль. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | Список подписей, которые не прошли процесс проверки. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Результат проверки; True, если процесс проверки был успешным, иначе False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | Время выполнения процесса в миллисекундах. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | Размер исходного документа в байтах. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | Список успешно проверенных подписей [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | Общее количество обработанных подписей. |

### Пример

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

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
