---
title: "Barkod İmzası ile Belge e-İmzala"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu makale, GroupDocs.Signature for Python via .NET kullanarak belge sayfasına barkod imzası eklemenin, barkod türü, barkod metni, konumlandırma, hizalama ve diğer görsel ayarlar gibi çeşitli seçeneklerle nasıl yapılacağını açıklar."
type: docs
url: /tr/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

**barcode** veya **bar code**, verileri görsel, makine tarafından okunabilir bir biçimde sunmanın bir yoludur. Genel olarak, barkod, farklı genişlikte paralel siyah çizgiler ve beyaz boşluklardan oluşan dikdörtgen biçimli bir görüntüdür.
Barkodlar, hızlı tanımlamanın gerekli olduğu çeşitli alanlarda kullanılır—perakende mağazalarında satın alma sürecinin bir parçası olarak, depolarda envanter takibi için ve faturalarda muhasebeye yardımcı olmak gibi birçok başka kullanımda.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Barkodlar, üretim ve son kullanma tarihleri, üretici adı, menşe ülke ve ürün fiyatı gibi ürünle ilgili verileri depolamayı sağlar. Günümüzde birçok barkod türü mevcuttur çünkü farklı şirketler ihtiyaçlarına göre barkodlarında farklı sayı ve çubuk kombinasyonları kullanır. Belge imzası perspektifinden bakıldığında, Barkod farklı karakterler (harfler, rakamlar veya semboller) içerebilir ve tür ve ayarlara bağlı olarak imza bilgisi, başlık, konu veya kısa şifreli veri tutmak için çeşitli uzunluk ve boyutlarda olabilir.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Barkod imzası için farklı seçenekleri belirtmek amacıyla GroupDocs.Signature for Python via .NET, [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) sınıfını sağlar. Ana alanlar şunlardır:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

GroupDocs.Signature for Python via .NET API kullanarak Barkod imzası ile bir belgeyi e-imzalamak için adımlar şunlardır:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Bu örnek, Python kullanarak bir PDF belgesine Barkod imzası eklemenin nasıl yapılacağını gösterir:

{{< tabs \"sign_with_barcode_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Kodlamak için metin içeren barkod imza seçeneklerini oluşturun
        options = BarcodeSignOptions("John Smith")

        # Barkod türünü ayarlayın
        options.encode_type = BarcodeTypes.CODE128

        # Barkod konumunu ve boyutunu ayarlayın
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Belgeyi imzalayın ve sonucu kaydedin
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab \"signed_barcode.pdf\" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Barkod imzasını ek seçeneklerle daha da özelleştirebilirsiniz: hizalama ve kenar boşlukları, çubuk rengi, kodlanmış metnin konumu, iç kenar boşlukları, arka plan, kenarlık ve şeffaflık:

{{< tabs \"sign_with_barcode_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Metni ve barkod türünü yapıcıya geçirin
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Barkodu sayfanın sağ alt köşesine yerleştirin
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Çubuk rengi, çubukların altındaki kodlanmış metin, kenarlık içindeki boşluk
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Arka plan, kenarlık ve şeffaflık
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab \"signed_barcode_advanced.pdf\" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature çeşitli barkod türlerini destekler. Her tür, kendi karakter ve uzunluk setini kabul eder, bu yüzden metni türe uygun seçin. Bu örnek, tek bir çağrıda farklı türlerde dört barkodla bir belgeyi imzalar:

{{< tabs \"sign_with_different_barcode_types\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # Her barkod için bir imza seçenekleri nesnesi, birbiri altına yerleştirilir
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Bu kılavuz, belgeler üzerine barkod tabanlı imzalar eklemek için [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) kullanımını gösterir. Çeşitli barkod türleri ve özelleştirme seçenekleri desteğiyle barkod imzaları oluşturmayı, yapılandırmayı ve uygulamayı kapsar. Daha fazla keşif için belge bilgileri ve gelişmiş imzalama teknikleriyle ilgili kılavuzlara bakın.

## More Resources

### GitHub Examples

Yukarıdaki kodu kolayca çalıştırabilir ve GitHub örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tam özellikli Python kütüphanesiyle birlikte, basit ama güçlü ücretsiz çevrimiçi uygulamalar da sunuyoruz.

Barkod oluşturmak ve/veya dosyalarınızı barkodlarla ücretsiz imzalamak için, çevrimiçi uygulama olan [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode) kullanabilirsiniz.

PDF, Word, Excel, PowerPoint ve diğer belgeleri imzalamak için **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**'den diğer çevrimiçi uygulamaları kullanabilirsiniz.
