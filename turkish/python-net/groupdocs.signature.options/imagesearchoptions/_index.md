---
title: "ImageSearchOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Görüntü imzaları için arama seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

Görüntü imzaları için arama seçeneklerini temsil eder.

Daha fazla bilgi:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

ImageSearchOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | ImageSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | Arama kriteri için görüntülerin maksimum boyutu, bayt cinsinden. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | Arama sırasında dikkate alınacak görüntü verisinin minimum boyutu, bayt cinsinden. Sıfır olmayan bir değer minimum boyutu belirtir; varsayılan değer sıfırdır ve arama sonucunu etkilemez. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | İmzanın görüntü içeriğinin döndürülüp döndürülmeyeceğini belirleyen bayrak. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | `return_content` özelliği etkinleştirildiğinde döndürülen görüntü içeriğinin dosya türü. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Her belge sayfasında arama yapılıp yapılmayacağını belirten bayrak. Varsayılan olarak bu değer True'tır. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Arama için belge sayfa numarası (isteğe bağlı). (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | İmza araması için sayfaları belirtmek üzere seçenekler. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Belge düzeninde şekil konumunun döndürülüp döndürülmeyeceğini belirten bayrak. Yalnızca Word belgeleri için kullanılabilir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | `IsSignature` olarak işaretlenmiş yalnızca imzaları döndürmek için bayrak. Varsayılan değer `False` olup, belirtilen kriterlere uyan tüm imzaların döndürüleceğini gösterir. (şuradan devralınmıştır [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
