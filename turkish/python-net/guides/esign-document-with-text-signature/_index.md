---
title: "Metin İmzası ile eSign Belgesi"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu makale, GroupDocs.Signature for Python via .NET API kullanarak bir belgeyi Metin imzası ile nasıl imzalayacağınızı açıklar. Python'da programlı olarak bir PDF'ye dijital imza eklemeyi öğrenin."
type: docs
url: /tr/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

**Text** elektronik imza, belgenin türüne bağlı olarak yerel bir şekilde belgeye eklenen rastgele bir metindir. GroupDocs.Signature, metin imza özelliğini sağlar ve yazı tipi adı, boyutu ve rengi, hizalama, kenarlıklar, gölge efektleri vb. gibi geniş bir metin ayarı yelpazesini özelleştirmenize izin verir. İşte bir metin imzasının nasıl görünebileceği:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Python kullanarak bir PDF'ye programlı olarak metin imzası eklemeyi deneyelim.

Programlı olarak metin imzalarını işlemek için [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) sınıfını sağlar ve tüm iş akışı aşağıdaki gibi basittir:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Bu örnek, Python kullanarak bir belgeye metin imzası eklemeyi gösterir:

{{< tabs "sign_with_text_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Metin imza seçeneklerini oluşturun
        options = TextSignOptions("John Smith")

        # İmza konumunu ve boyutunu ayarlayın
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Metin rengini ve yazı tipini ayarlayın
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Belgeyi imzalayın ve sonucu kaydedin
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Metin imzasını ek seçeneklerle daha da özelleştirebilirsiniz: hizalama ve kenar boşlukları, yazı tipi stili, arka plan, kenarlık, döndürme ve şeffaflık. Bir hizalama ayarlandığında, `left` veya `top` koordinatını değiştirir ve `margin` imzayı sayfa kenarından uzaklaştırır.

{{< tabs "sign_with_text_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # İmzayı sayfanın sağ alt köşesine yerleştirin
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Yazı tipi stili ve metin rengi
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Arka plan, kenarlık, döndürme ve şeffaflık
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # Metni bir görüntü olarak oluşturun, bu aynı zamanda PDF sayfalarına kenarlık çizer
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "signed_text_advanced.pdf" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Bu kılavuz, belgelerde metin tabanlı imzalar eklemeyi [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) ile nasıl yapacağınızı açıklar. Yazı tipi, renk, boyut ve konum gibi metin özelliklerini yapılandırmayı ve metin imzasını bir belgeye uygulamayı kapsar. İmzalı belge daha sonra eklenen metin imzası ile kaydedilir.

## More Resources

### GitHub Examples

Yukarıdaki kodu kolayca çalıştırabilir ve GitHub örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tam özellikli Python kütüphanesiyle birlikte, basit ama güçlü ücretsiz çevrimiçi uygulamalar da sunuyoruz.

PDF, Word, Excel, PowerPoint ve diğer belgeleri imzalamak için **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** adresindeki çevrimiçi uygulamaları kullanabilirsiniz.
