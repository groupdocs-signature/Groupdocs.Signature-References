---
title: "FormFieldSignOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "PDF belgeleri için FormField imza seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

PDF belgeleri için FormField imza seçeneklerini temsil eder.

PDF dosyalarında form alanı imzaları oluşturmak veya güncellemek için seçenekler sağlar.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

FormFieldSignOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | PdfFormFieldSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | PdfFormFieldSignOptions sınıfının yeni bir örneğini FormField imzası ile başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | Belge sayfasındaki imza alanının yüksekliği ölçü birimlerinde (piksel, yüzde veya milimetre; `MeasureType` SizeMeasureType bakınız). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | Bir belge sayfasındaki görüntünün yatay hizalaması. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | Belge sayfasındaki imza alanının sol X konumu ölçü birimlerinde (piksel, yüzde veya milimetre). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Sol ve Üst özellikleri için ölçü tipi (piksel, yüzde veya milimetre). |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | Görüntü ile belge kenarları arasındaki varsayılan boşluk (yatay veya dikey hizalama ayarlandığında uygulanır). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | Kenar boşluğu ölçüm tipi (piksel, yüzde veya milimetre). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | Saat yönünde ölçülen döndürme açısı. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | İmzanın FormField'ı. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | Belge sayfasındaki germe modu. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | Belge sayfasındaki imza alanının üst Y konumu ölçü birimlerinde (piksel, yüzde veya milimetre) belirtilir. Konum ölçü tipi için `MeasureType`'a bakın. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | Form alanı imzasının şeffaflığı. Değer 0.0 ile 1.0 arasında değişir, varsayılan değer 0'dır. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | Bir belge sayfasındaki görüntünün dikey hizalaması. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | Belge sayfasındaki imza alanının genişliği ölçü değerlerinde (piksel, yüzde veya milimetre; `MeasureType` SizeMeasureType bakınız). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | İmza tüm belge sayfalarına yerleştirilecektir. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Ek imza görünümü. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | İmza arka plan ayarları. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Kenarlık ayarları. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | İmza seçeneklerinin belge tipi (`DocumentType`). ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | İmza uzantıları. ([`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) üzerinden miras alınmıştır) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | İmzanın yazı tipi. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | İmzanın ön rengi. ([`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/) üzerinden devralınmıştır) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
