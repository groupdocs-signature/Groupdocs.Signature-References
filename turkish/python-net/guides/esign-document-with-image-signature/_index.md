---
title: "Görüntü İmzası ile eSign Belgesi"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu makale, .NET üzerinden Python için GroupDocs.Signature ile belge sayfasına imza görüntüsü eklemeyi gösterir."
type: docs
url: /tr/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

**image** bir imza olarak, sunulan verileri görsel bir biçimde koymanın alternatif bir yoludur. Bu elektronik imza türü, şirket logosu, gönderenin baş harfleri, isimler vb. ile özel görüntüler oluşturulmasına olanak tanır.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Belge sayfasına bir görüntü imzası oluşturmak için adımlar şunlardır:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Bu örnek, Python kullanarak PDF belgesine görüntü imzası ile nasıl imza atılacağını gösterir:

{{< tabs "sign_with_image_signature" >}}
{{< tab "Python" >}}
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

        # Belgeyi imzalayın ve sonucu kaydedin
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) tıklayın.

{{< /tab >}}
{{< tab "signed_image.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

Görüntü imzasını ek seçeneklerle daha da özelleştirebilirsiniz: hizalama ve kenar boşlukları, döndürme, şeffaflık ve bir kenarlık. Bir hizalama ayarlandığında, `left` veya `top` koordinatını değiştirir ve `margin` imzayı sayfa kenarından uzaklaştırır.

{{< tabs "sign_with_image_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # İmzayı sayfanın sağ alt köşesine yerleştirin
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Görüntüyü döndürün ve %20 şeffaf yapın
        options.rotation_angle = 10
        options.transparency = 0.2

        # Görüntünün etrafına kesikli bir kenarlık çizin
        border = Border()
        border.color = Color.dark_green
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border

        result = signature.sign("signed_image_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) tıklayın.

{{< /tab >}}
{{< tab "signed_image_advanced.pdf" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

Ayrıca imza görüntüsünü bir akıştan da yükleyebilirsiniz. `sign` döndürülene kadar akışı açık tutun:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # İmza görüntüsünü bir akıştan yükleyin
        with open("signature.jpg", "rb") as image_stream:
            options = ImageSignOptions(image_stream)
            options.left = 100
            options.top = 400
            options.width = 120
            options.height = 100

            result = signature.sign("signed_image_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) tıklayın.

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Bu kılavuz, belgelere görüntü tabanlı imzalar eklemek için [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) nasıl kullanılacağını gösterir. Bir belgenin yüklenmesi, görüntü imzasının özelliklerinin (örneğin boyut, konum ve şeffaflık) yapılandırılması ve imzalı belgenin kaydedilmesi konularını kapsar. Görüntü görünümünü ayarlama ve imzayı hizalama gibi gelişmiş özelleştirme seçenekleri de tartışılır. Daha fazla bilgi için ilgili belge imzalama kaynaklarını keşfedin.

## More Resources

### GitHub Examples

Yukarıdaki kodu kolayca çalıştırabilir ve GitHub örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tam özellikli Python kütüphanesiyle birlikte, basit ama güçlü ücretsiz çevrimiçi uygulamalar da sunuyoruz.

Görüntü imzaları oluşturmak ve/veya dosyalarınızı ücretsiz olarak bunlarla imzalamak için [Generate Image](https://products.groupdocs.app/signature/generate/image) çevrimiçi uygulamasını kullanabilirsiniz.

PDF, Word, Excel, PowerPoint ve diğer belgeleri imzalamak için **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**'den diğer çevrimiçi uygulamaları kullanabilirsiniz.
