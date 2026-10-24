---
title: "BarcodeSignOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Barkod imza seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Barkod imza seçeneklerini temsil eder.

Daha fazla bilgi edinin

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

BarcodeSignOptions türü aşağıdaki üyeleri ortaya koyar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | BarcodeSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | BarcodeSignOptions sınıfının yeni bir örneğini metinle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | BarcodeSignOptions sınıfının yeni bir örneğini metinle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | Sonuç barcode görüntüsündeki metnin hizalaması. Varsayılan değer None'dur. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | Barcode türü. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | Barcode çubuklarının ön plan rengi; kullanımı doğrulama sorunlarına yol açabilir, bu yüzden dikkatli kullanın. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | Belge sayfasındaki imza alanının yüksekliği ölçü birimleriyle (piksel, yüzde veya milimetre) ifade edilir. Boyut ölçü tipi için `MeasureType`'a bakın. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | Bir belge sayfasındaki görüntünün yatay hizalaması. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | Barcode öğeleri ile sonuç görüntüsü kenarları arasındaki boşluk. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | Belge sayfasındaki imza alanının sol X konumu, ölçü birimleriyle (piksel, yüzde veya milimetre) ifade edilir. `MeasureType`'a bakın. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | Sol ve üst özellikleri için ölçü tipi (piksel, yüzde veya milimetre). |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | Görüntü ile belge kenarları arasındaki varsayılan olarak belirtilen boşluk (yatay veya dikey hizalama ayarlandığında uygulanır). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | Kenar boşluğu ölçüm türü (piksel, yüzde veya milimetre). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | Belge sayfasına yerleştirilen bir imzanın barcode görüntü içeriğini alıp almayacağını gösteren bayrak. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | `return_content` özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türü. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | Saat yönünde döndürme açısı. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | Belge sayfasındaki germe modu. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | Belge sayfasındaki imza alanının üst Y konumu ölçü birimleriyle (piksel, yüzde veya milimetre) ifade edilir. `MeasureType` LocationMeasureType'a bakın. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | Barcode imzasının şeffaflığı, 0.0 (tamamen opak) ile 1.0 (tamamen şeffaf) arasında değişir; varsayılan 0'dır. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | Belge sayfasındaki barcode görüntüsünün dikey hizalaması. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | `MeasureType` tarafından tanımlanan ölçü değerleriyle (piksel, yüzde veya milimetre) belge sayfasındaki imza alanının genişliği. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | İmza tüm belge sayfalarına yerleştirilecektir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Ek imza görünümü. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | İmza arka plan ayarları. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Kenarlık ayarları. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | İmza seçeneklerinin belge tipi (`DocumentType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | İmza uzantıları. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | İmzanın yazı tipi. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Metin imzasının yerleştirileceği metin form alanının başlığı. Yalnızca `signature_implementation` `TextSignatureImplementation.FORM_FIELD` olarak ayarlandığında kullanılabilir. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Metin imzasının yerleştirileceği form alanının türü. Bu özellik yalnızca `signature_implementation` `TextSignatureImplementation.FORM_FIELD` (yani TextToFormField) olarak ayarlandığında uygulanır. Varsayılan değer `FormTextFieldType.ALL_TEXT_TYPES`. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Kriptografik işlemler için kullanılacak hash algoritması. Yalnızca PDF dosyalarındaki dijital imzalar için desteklenir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Yerel öznitelik. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | İmzalama için belge sayfa numarası. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | İmzalanacak sayfaları belirtmek için seçenekler. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Şekil konumu, şeklin belge düzeninde nerede gösterileceğini tanımlar. Yalnızca Word belgeleri için kullanılabilir. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Metin yerleştirilecek şeklin türü. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | İmzanın benzersiz kimliği, doğrulama seçeneklerinde kullanılabilir ve yalnızca PDF belgeleri için desteklenir. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Metin imza uygulamasının türü. (şu sınıftan devralınmıştır [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | İmza tipi (`SignatureType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | İmzanın metni. (şu sınıftan devralınmıştır [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | İmza içindeki metnin yatay hizalaması, yalnızca Görüntü ve Açıklama imza uygulamaları için desteklenir (`TextSignatureImplementation` SignatureImplementation özelliğine bakınız). (şu sınıftan devralınmıştır [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | İmza içindeki metnin dikey hizalaması. (şu sınıftan devralınmıştır [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Metin imzasının Z-sırası konumu, üst üste gelen imzaların görüntülenme sırasını belirler. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
`BarcodeSignOptions` kullanan görev kılavuzları:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
