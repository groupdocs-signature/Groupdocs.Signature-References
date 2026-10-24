---
title: "TextSignOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metin imza seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Metin imza seçeneklerini temsil eder.

Daha fazla bilgi edinin

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

TextSignOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | TextSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | TextSignOptions sınıfının yeni bir örneğini metinle başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | İmza arka plan ayarları. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Kenarlık ayarları. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | İmzanın yazı tipi. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | İmzanın ön renk. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Metin imzasının yerleştirileceği metin form alanının başlığı. Yalnızca `signature_implementation` `TextSignatureImplementation.FORM_FIELD` olarak ayarlandığında kullanılabilir. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Metin imzasının yerleştirileceği form alanının türü. Bu özellik yalnızca `signature_implementation` `TextSignatureImplementation.FORM_FIELD` (yani TextToFormField) olarak ayarlandığında uygulanır. Varsayılan değer `FormTextFieldType.ALL_TEXT_TYPES`dır. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | İmzanın belge sayfasındaki yüksekliği ölçü değerleri (piksel, yüzde veya milimetre) cinsindendir. Birim, `SizeMeasureType` özelliği tarafından belirlenir. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | İmzanın belge sayfasındaki yatay hizalaması. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | İmzanın belge sayfasındaki sol X konumu, ölçü değerleri (piksel, yüzde veya milimetre) cinsinden, `MeasureType` LocationMeasureType özelliği tarafından tanımlandığı gibi. Yatay hizalama belirtilmemişse çalışır. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | `left` ve `top` özellikleri için ölçü türü (piksel, yüzde veya milimetre). |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | İmza ile belge kenarları arasındaki boşluk. Yalnızca yatay veya dikey hizalama belirtildiğinde uygulanır. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Kenar boşluğu için ölçü tipi (piksel, yüzde veya milimetre). |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Yerel öznitelik. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | İmzanın belge sayfasındaki dönüş açısı (saat yönünde). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Şekil konumu, şeklin belge düzeninde nerede gösterileceğini tanımlar. Yalnızca Word belgeleri için kullanılabilir. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Metni yerleştirmek için şekil türü. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | İmzanın benzersiz kimliği, doğrulama seçeneklerinde kullanılabilir ve yalnızca PDF belgeleri için desteklenir. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Metin imza uygulamasının türü. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | Belge sayfasındaki germe modu. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | İmzanın metni. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | İmza içindeki metnin yatay hizalaması, yalnızca Image ve Annotation imza uygulamaları için desteklenir (`TextSignatureImplementation` SignatureImplementation özelliğine bakınız). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | İmza içindeki metnin dikey hizalaması. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | İmzanın belge sayfasındaki üst Y konumu, ölçü birimleri (piksel, yüzde veya milimetre) cinsinden ifade edilir. |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | İmza şeffaflığı, 0.0 (opak) ile 1.0 (şeffaf) arasında bir ondalık sayıdır. Varsayılan değer 0.0 (opak)dır. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | İmzanın belge sayfasındaki dikey hizalaması. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | İmzanın belge sayfasındaki genişliği ölçü değerleri (piksel, yüzde veya milimetre) cinsindendir; `MeasureType` `SizeMeasureType` özelliğine bakınız. |
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
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
`TextSignOptions` kullanan görev kılavuzları:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
