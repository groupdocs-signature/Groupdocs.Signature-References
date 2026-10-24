---
title: "DigitalSignOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Dijital imza seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Dijital imza seçeneklerini temsil eder.

Daha fazla bilgi edinin

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

DigitalSignOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | DigitalSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Yeni bir DigitalSignOptions örneğini bir sertifika dosyasıyla başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Yeni bir DigitalSignOptions örneğini bir sertifika akışıyla başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | DigitalSignOptions sınıfının yeni bir örneğini bir sertifika dosyası ve bir görünüm görüntü dosyasıyla başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | DigitalSignOptions'ın yeni bir örneğini bir sertifika dosyası ve bir görünüm görüntü akışıyla başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | DigitalSignOptions'ın yeni bir örneğini bir sertifika akışı ve bir görünüm görüntü dosyasıyla başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Yeni bir DigitalSignOptions örneğini bir sertifika akışı ve bir görünüm görüntü akışıyla başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Dahili kaynakları temizler. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Base64 dizesinden önceden tanımlı bir görüntüyle yeni bir ImageSignOptions örneği oluşturur. ([`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/) üzerinden devralınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | Süre sonu geçmiş bir sertifika ile imzalamayı sağlayan bayrak. Varsayılan değer False'tur; süresi dolmuş bir sertifika ile imzalama `GroupDocsSignatureException` hatası oluşturur ve belge imzalanmaz. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | Henüz geçerlilik süresi başlamamış bir sertifika ile imzalamayı sağlayan bayrak. Varsayılan değer False'tur; bu tür bir sertifika ile imzalama `GroupDocsSignatureException` hatası oluşturur ve belge imzalanmaz. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Dijital sertifika dosya yolu. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | Dijital sertifika akışı. Bu özellik belirtilirse her zaman CertificateFilePath yerine kullanılır. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | İmza iletişim bilgisi. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | Belgeyi imzalamak için kullanılan özel hash imzalama işlevi, kullanıcıların kendi dijital imzalama mantığını uygulamasına olanak tanır. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | Belge sayfasındaki imza alanının yüksekliği ölçü birimlerinde (piksel, yüzde veya milimetre; `MeasureType` bakınız). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | Bir belge sayfasındaki görüntünün yatay hizalaması. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | Belge sayfasındaki imza alanının sol X konumu ölçü birimlerinde (piksel, yüzde veya `MeasureType.location_measure_type` tarafından tanımlanan milimetre). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | İmza konumu. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Sol ve üst özellikleri için ölçü tipi (piksel, yüzde veya milimetre). |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | Görsel ile belge kenarları arasındaki varsayılan boşluk (yatay veya dikey hizalama belirtildiğinde uygulanır). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Kenar boşluğu ölçüm türü (piksel, yüzde veya milimetre). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | Dijital sertifikanın parolası. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | İmzanın nedeni. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | Saat yönünde döndürme açısı. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | Belge için dijital imza özellikleri. PDF imzalama için, gelişmiş özellikler bir [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/) örneği kullanılarak ayarlanabilir. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | Belge sayfasındaki germe modu. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | Belge sayfasındaki imza alanının üst Y konumu ölçü birimlerinde (piksel, yüzde veya milimetre; `MeasureType` `LocationMeasureType` bakınız). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | Dijital imzanın saydamlığı, 0.0 ile 1.0 arasında değişir. Varsayılan değer 0'dır. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | LTV (Uzun Süreli Doğrulama) doğrulama bayrağı. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | Bir belge sayfasındaki görüntünün dikey hizalaması. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | İmzanın görünürlüğü. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | Belge sayfasındaki imza alanının genişliği ölçü değerlerinde (piksel, yüzde veya milimetre). Ölçüm birimi `MeasureType` aracılığıyla SizeMeasureType özelliği ile tanımlanır. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | XAdES tipi. Varsayılan değer None'dur (XAdES kapalı). |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Sertifikayı ve görünüm görselini yapıcıya geçirin
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # İmzayı sayfada, bu konum ve boyutta göster
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # İmzada depolanan bilgi
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
`DigitalSignOptions` kullanan görev kılavuzları:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
