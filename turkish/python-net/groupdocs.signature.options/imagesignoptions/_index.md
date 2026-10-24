---
title: "ImageSignOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Görüntü imza seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Görüntü imza seçeneklerini temsil eder.

Daha fazla bilgi:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

ImageSignOptions türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | ImageSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | ImageSignOptions'ı bir görüntü dosyasıyla başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | ImageSignOptions'ın yeni bir örneğini bir görüntü akışıyla başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Dahili kaynakları temizler. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Base64 dizesinden önceden tanımlı bir görüntüyle yeni bir ImageSignOptions örneği oluşturur. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Görüntü imzası için kenar ayarları. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | İmzanın belge sayfasındaki yüksekliği ölçü değerleri (piksel, yüzde veya milimetre; `MeasureType` SizeMeasureType) olarak. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | İmzanın belge sayfasındaki yatay hizalaması. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | İmza görüntüsünün dosya yolu, yalnızca `image_stream` belirtilmemişse kullanılır. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | İmza görüntüsü akışı. Belirtilirse, her zaman ImageFilePath yerine kullanılır. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | İmzanın belge sayfasındaki sol X konumu ölçü değerleri (piksel, yüzde veya milimetre) olarak. Yatay hizalama belirtilmemişse çalışır. Konum ölçü tipi için `MeasureType` bakınız. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Sol ve üst özellikleri için ölçü tipi (piksel, yüzde veya milimetre). |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | İmza ile belge kenarları arasındaki boşluk. Yalnızca yatay veya dikey hizalama belirtilmişse çalışır. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Kenar boşluğu için ölçü tipi (piksel, yüzde veya milimetre). |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Görüntünün belgeye yerleştirileceği alanın dikdörtgeni. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | İmzanın belge sayfasındaki dönüş açısı (saat yönünde). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Şekil konumu, şeklin belge düzeninde nerede gösterileceğini tanımlar. Yalnızca Word belgeleri için kullanılabilir. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | Belge sayfasındaki germe modu. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | İmzanın belge sayfasındaki üst Y konumu, `MeasureType` LocationMeasureType tarafından tanımlanan ölçü değerleri (piksel, yüzde veya milimetre) olarak. Dikey hizalama belirtilmemişse çalışır. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | İmza şeffaflığı, 0.0 (opak) ile 1.0 (şeffaf) arasında değişir, varsayılan değer 0 (opak)dır. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | İmzanın belge sayfasındaki dikey hizalaması. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | İmzanın belge sayfasındaki genişliği ölçü değerleri (piksel, yüzde veya milimetre `MeasureType` boyut ölçü tipi) olarak. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | İmza tüm belge sayfalarına yerleştirilecektir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Ek imza görünümü. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | İmza seçeneklerinin belge tipi (`DocumentType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | İmza uzantıları. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Kriptografik işlemler için kullanılacak hash algoritması. Yalnızca PDF dosyalarındaki dijital imzalar için desteklenir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | İmzalama için belge sayfa numarası. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | İmzalanacak sayfaları belirtmek için seçenekler. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | İmza tipi (`SignatureType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Metin imzasının Z-sırası konumu, üst üste gelen imzaların görüntülenme sırasını belirler. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Görüntü dosyasıyla görüntü imza seçenekleri oluşturun
        options = ImageSignOptions("signature.jpg")
        # İmza konumunu ve boyutunu ayarlayın
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
`ImageSignOptions` kullanan görev kılavuzları:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
