---
title: "StampSignOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Damga imza seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Damga imza seçeneklerini temsil eder.

Daha fazla bilgi:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

StampSignOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Varsayılan değerlerle StampSignOptions sınıfının yeni bir örneğini başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Hizalama seçenekleriyle StampSignOptions sınıfının yeni bir örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Dahili kaynakları temizler. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Base64 dizesinden önceden tanımlı bir görüntüyle yeni bir ImageSignOptions örneği oluşturur. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | Mührün arka planı. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | İmzanın arka plan rengi kırpma türü. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | İmzanın arka plan resmi kırpma türü. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | Belge sayfasındaki imza alanının yüksekliği ölçü birimleriyle (piksel, yüzde veya milimetre) ifade edilir. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | Bir belge sayfasındaki görüntünün yatay hizalaması. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | İç hatların bir dizi dikdörtgen olarak işlenmiş listesi. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | Belge sayfasındaki imza alanının sol X konumu ölçü birimleriyle (piksel, yüzde veya milimetre). `MeasureType` `LocationMeasureType` bakınız. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | Sol ve üst özellikleri için ölçü tipi (piksel, yüzde veya milimetre). |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | Görsel ile belge kenarları arasında varsayılan olarak belirtilen boşluk (yatay veya dikey hizalama belirtilmişse çalışır). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | Kenar boşluğu ölçüm türü (piksel, yüzde veya milimetre). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | Dış hatların iç içe daireler olarak işlenmiş listesi. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | Saat yönünde döndürme açısı. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | Mühür türü. Varsayılan `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | Belge sayfasındaki germe modu. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | Belge sayfasındaki imza alanının üst Y konumu ölçü birimleriyle (piksel, yüzde veya milimetre). `MeasureType` `LocationMeasureType` bakınız. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | Mühür imzasının şeffaflığı. Değer 0.0 ile 1.0 arasında değişir, varsayılan 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | Belge sayfasındaki mührün dikey hizalaması. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | Belge sayfasındaki imza alanının genişliği ölçüm değerleri (piksel, yüzde veya milimetre) cinsindendir. Ölçüm birimi `MeasureType` SizeMeasureType tarafından tanımlanır. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | İmza tüm belge sayfalarına yerleştirilecektir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Ek imza görünümü. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Görsel imza için kenar ayarları. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır). |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | İmza seçeneklerinin belge tipi (`DocumentType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | İmza uzantıları. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Kriptografik işlemler için kullanılacak hash algoritması. Yalnızca PDF dosyalarındaki dijital imzalar için desteklenir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | İmza görselinin dosya yolu, yalnızca `image_stream` belirtilmemişse kullanılır. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır). |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | İmza görsel akışı. Belirtilirse, her zaman ImageFilePath yerine kullanılır. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır). |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | İmzalama için belge sayfa numarası. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | İmzalanacak sayfaları belirtmek için seçenekler. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Görselin belgeye yerleştirileceği alanın dikdörtgeni. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Şekil konumu, şeklin belge düzeninde nerede gösterileceğini tanımlar. Yalnızca Word belgeleri için kullanılabilir. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır). |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | İmza tipi (`SignatureType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Metin imzasının Z-sırası konumu, üst üste gelen imzaların görüntülenme sırasını belirler. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # gerektiği gibi ek damga seçeneklerini yapılandırın
    signature.sign(options)
```

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
