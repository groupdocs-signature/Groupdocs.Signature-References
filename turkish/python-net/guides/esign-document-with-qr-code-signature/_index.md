---
title: "QR Kod İmzası ile eSign Belgesi"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu makale, GroupDocs.Signature for Python aracılığıyla .NET API kullanarak belge sayfasına QR kodu şeklinde elektronik imza ile nasıl imzalanacağını açıklar."
type: docs
url: /tr/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR kod (veya Quick Response kodu), beyaz bir arka plan üzerinde kare ızgara içinde düzenlenmiş siyah karelerden oluşan iki boyutlu bir [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) türüdür. QR kodları, akıllı telefon kameraları veya QR okumaya özel cihazlar — taşınabilir tarayıcılar, el terminalleri, masaüstü tarayıcılar, gömülü tarayıcılar vb. — tarafından okunabilir. Genellikle QR kodları, bir web sitesine veya uygulamaya, e-postalara, telefon numaralarına, ürün tanımlayıcılarına veya izleyicilere yönlendiren veriler içerir. Bu nedenle, QR kodu uygulama alanı genel pazarlamadan ürün tanımlamaya, belge yönetimine kadar geniş bir yelpazeyi kapsar.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec kodu | DataMatrix kodu | GS1 DataMatrix | GS1 QR kodu | QR |
| --- | --- | --- | --- | --- | --- |
| **Uygulama** | * taşıma ve biletleme;<br> * havayolu endüstrisinde elektronik biniş kartları için;<br> * demiryolda çevrimiçi satılan ve müşteriler tarafından basılan ya da mobil telefon ekranlarında gösterilen biletler için. Kod, tren personeli tarafından elde taşınan bir tarayıcıyla veya turnikede biletin doğrulanması için taranır.<br> * tıp - hasta kimlik bileklikleri ve tek kullanımlık ilaçlar için etiketler vb. | * etiket ve mektup gibi basılı medya;<br> * endüstriyel mühendislik amaçları - bileşenlerin işaretlenmesi vb;<br>  * gıda endüstrisi - gıda ürünlerinin yanlış paketlenmesini ve tarihlendirilmesini önlemek için; | Kullanılır<br> * Sağlık;<br> * Hükümet;<br> * Endüstri.<br> Öğenin ek bilgilerini kodlar, örneğin:<br> * ağırlık;<br> * son kullanma tarihi;<br> * parti numarası;<br> * üretim tarihi;<br> * vb. | Paket üzerindeki ek öğe bilgilerini kodlamak için pazarlamada kullanılır | Otomotiv endüstrisi ve mobil uygulamalarda yaygın olarak kullanılır. Büyük miktarda veri karakteri ve belirli URL'leri kodlamak için faydalıdır. |
| **Uzunluk** | 3067 alfasayısal,<br> 3832 sayısal,<br> 1914 bayt | 2335 alfasayısal,<br> 3116 sayısal | 2335 alfasayısal,<br> 3116 sayısal,<br> 1556 bayt | 7089 alfasayısal,<br> 4296 sayısal,<br> 2953 bayt | 4296 alfasayısal,<br> 7089 sayısal,<br> 2953 bayt |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

Bir belgeye QR kodlu elektronik imza eklerken, ana ayarlar kodlanacak metin ve [QR kodunun türü](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) olup, bu [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) sınıfı aracılığıyla belirtilmelidir.

QR kod imzası ile bir belgeyi e-imzalamak için adımlar şunlardır:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

Aşağıdaki kod parçacığı, Python kullanarak QR kod imzası ile bir PDF belgesini nasıl imzalayacağınızı gösterir:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Kodlanacak metinle QR kod imza seçeneklerini oluşturun
        options = QrCodeSignOptions("John Smith")

        # QR kod türünü ayarlayın
        options.encode_type = QrCodeTypes.QR

        # QR kod konumunu ve boyutunu ayarlayın
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Belgeyi imzalayın ve sonucu kaydedin
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "signed_qr_code.pdf" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

Yukarıdaki tabloda yer alan diğer QR kod tipleri aynı şekilde ayarlanır, örneğin `QrCodeTypes.AZTEC` veya `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

İşte ek özelleştirmelerle daha karmaşık bir QR kod imzası oluşturmayı gösteren bir örnek: hizalama ve kenar boşlukları, modül rengi, arka plan ve kenarlık:

{{< tabs "sign_with_qr_code_signature_advanced" >}}
{{< tab "Python" >}}
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
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "signed_qr_code_advanced.pdf" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Bu kılavuz, belgeler üzerine QR kod imzaları eklemeyi [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) kullanarak gösterir. QR kod imzası oluşturma, boyut ve kodlama gibi özelliklerini yapılandırma ve belgeye uygulama adımlarını içerir. QR kod imzaları, imzalı belgenin hızlı doğrulanması için kullanılabilir.

## More Resources

### GitHub Examples

Yukarıdaki kodu kolayca çalıştırabilir ve GitHub örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tam özellikli Python kütüphanesiyle birlikte, basit ama güçlü ücretsiz çevrimiçi uygulamalar da sunuyoruz.

Ücretsiz olarak QR kodları oluşturmak ve/veya dosyalarınızı QR kodlarıyla imzalamak için [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode) çevrimiçi uygulamasını kullanabilirsiniz.

PDF, Word, Excel, PowerPoint ve diğer belgeleri imzalamak için **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**'den diğer çevrimiçi uygulamaları kullanabilirsiniz.
