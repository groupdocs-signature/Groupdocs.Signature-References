---
title: "метод clone"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Клонировать экземпляр подписи."
type: docs
url: /ru/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Клонировать экземпляр подписи.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Пример

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Клонировать метаданные подписи с новым значением
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### См. также
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
