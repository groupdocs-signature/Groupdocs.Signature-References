---
title: "LoadOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "LoadOptions sınıfı, bir belgeyi imzalamak için açarken ek seçenekler (örneğin şifre) belirtmeye olanak tanır."
type: docs
url: /tr/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

LoadOptions sınıfı, bir belgeyi imzalamak için açarken ek seçenekler (örneğin şifre) belirtmeye olanak tanır.

Dosya şifreli ise `password` özniteliğini belge şifresi olarak ayarlayın.

LoadOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | LoadOptions sınıfının yeni bir örneğini başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Belirtilen dosya türüyle [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) sınıfının yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Yükleme seçenekleriyle ilişkili dosya türü, varsayılan olarak [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/) olur. |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | Belgenin harici kaynakları yükleyip yüklemeyeceğini belirleyen bayrak. Bu özellik artık kullanılmamaktadır; bunun yerine ters anlam taşıyan [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) kullanın. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | Korunan bir belgeyi açmak ve imzalı belgeyi korumalı olarak kaydetmek için kullanılan şifre. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | PDF belge izinleri, örneğin yazdırma, değiştirme ve veri çıkarma. Yalnızca PDF belgeleri için. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | Belgenin harici kaynakları yüklemesini durduran bayrak. Varsayılan değer True'dır; harici kaynaklar, [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) ile eşleşenler dışındaki kaynaklar yüklenmez. |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | Harici kaynakların, [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) true olduğunda bile yüklenecek adres parçacıklarının listesi. Varsayılan değer boş bir listedir. |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
