---
title: "QrCodeSignOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "QR-Kod imza seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

QR-Kod imza seçeneklerini temsil eder.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

QrCodeSignOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Varsayılan değerlerle QRCodeSignOptions sınıfının yeni bir örneğini başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Belirtilen metinle bir QR kod imza seçenekleri örneğini başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Metinle QrCodeSignOptions sınıfının yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | Oluşturulan QR kod görüntüsündeki metnin hizalaması, varsayılan değer None'dur. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | QR-Code içeriğine serileştirilecek özel nesne. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | QR kod imza metnini veya verisini kodlamak ve çözmek için kullanılan veri şifreleme uygulaması. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | QR-Code türü. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | QR kod çubuklarının ön plan rengi; bu özelliği kullanmak doğrulama sorunlarına neden olabilir, bu yüzden dikkatli kullanın. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | Belge sayfasındaki imza alanının yüksekliği ölçü birimlerinde (piksel, yüzde veya milimetre; `MeasureType` SizeMeasureType bakınız). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | Belge sayfasındaki QR kodun yatay hizalaması. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | QR kod öğeleri ile sonuç görüntüsü kenarları arasındaki boşluk. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | Belge sayfasındaki imza alanının sol X konumu ölçü birimleri (piksel, yüzde veya milimetre) cinsinden. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | Sol ve üst özellikleri için ölçü tipi (piksel, yüzde veya milimetre). |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | QR-code logo görüntü dosya adı. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | QR-code logo görüntü akışı. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | Görüntü ve Belge kenarları arasında varsayılan olarak belirtilen boşluk (yatay veya dikey hizalama belirtilmişse çalışır). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | Kenar boşluğu ölçüm türü (piksel, yüzde veya milimetre). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | Belge sayfasına yerleştirilen bir imzanın QR-Code görüntü içeriğini almak için bayrak. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | `return_content` özelliği etkin olduğunda QR‑Code imzasının döndürülen görüntü içeriğinin dosya türü. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | Saat yönünde derece cinsinden dönüş açısı. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | Belge sayfasındaki germe modu. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | Belge sayfasındaki imza alanının üst Y konumu ölçü birimleri (piksel, yüzde veya milimetre) cinsinden. Birim, `MeasureType` türündeki `LocationMeasureType` özelliği tarafından tanımlanır. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | QR kod imzasının şeffaflığı. Değer 0.0 ile 1.0 arasında değişir, varsayılan değer 0'dır. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | Bir belge sayfasındaki görüntünün dikey hizalaması. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | Belge sayfasındaki imza alanının genişliği ölçü değerleri (piksel, yüzde veya `MeasureType` tarafından tanımlanan milimetre) cinsinden. |
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
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Metni ve QR kod türünü yapıcıya geçirin
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # QR kodu sayfanın sağ alt köşesine yerleştirin
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Modül rengi, arka plan ve içinde biraz boşluk olan noktalı kenarlık
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
`QrCodeSignOptions` kullanan görev kılavuzları:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
