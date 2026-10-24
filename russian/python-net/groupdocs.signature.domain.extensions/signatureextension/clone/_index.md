---
title: "метод clone"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Возвращает копию этого объекта."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Возвращает копию этого объекта.

```python
def clone(self):
    ...
```

### Пример

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Клонировать метаданные подписи с новым значением
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### См. также
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
