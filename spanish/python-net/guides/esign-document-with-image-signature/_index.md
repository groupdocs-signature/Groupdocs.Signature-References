---
title: "Documento eSign con firma de imagen"
linkTitle: "Image Signature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Este artículo muestra cómo agregar una imagen de firma en la página del documento con GroupDocs.Signature para Python a través de .NET."
type: docs
url: /es/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

Una **image** como firma es una forma alternativa de presentar cualquier dato en forma visual. Este tipo de firma electrónica permite crear imágenes personalizadas con el logotipo de la empresa, las iniciales del remitente, nombres, etc.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Estos son los pasos para crear una firma de imagen en la página de un documento:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Este ejemplo muestra cómo firmar un documento PDF con la firma de imagen usando Python:

{{< tabs \"sign_with_image_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Crear opciones de firma de imagen con el archivo de imagen
        options = ImageSignOptions("signature.jpg")

        # Establecer la posición y el tamaño de la firma
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # Firma el documento y guarda el resultado
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) para descargarlo.

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

Puede personalizar aún más la firma de imagen con opciones adicionales: alineación y márgenes, rotación, transparencia y un borde. Cuando se establece una alineación, reemplaza la coordenada `left` o `top`, y el `margin` desplaza la firma desde el borde de la página.

{{< tabs \"sign_with_image_signature_advanced\" >}}
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

        # Coloque la firma en la esquina inferior derecha de la página
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Gire la imagen y hágala 20 % transparente
        options.rotation_angle = 10
        options.transparency = 0.2

        # Dibuje un borde discontinuo alrededor de la imagen
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

`sample.pdf` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) para descargarlo.

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

También puede cargar la imagen de la firma desde un flujo. Mantenga el flujo abierto hasta que `sign` devuelva:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # Cargar la imagen de la firma desde un flujo
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

`sample.pdf` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) para descargarlo.

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Esta guía muestra cómo usar [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) para agregar firmas basadas en imágenes a los documentos. Cubre la carga de un documento, la configuración de las propiedades de la firma de imagen (como el tamaño, la posición y la transparencia) y el guardado del documento firmado. También se discuten opciones avanzadas de personalización, como ajustar la apariencia de la imagen y alinear la firma. Para obtener más información, explore los recursos relacionados con la firma de documentos.

## More Resources

### GitHub Examples

Puede ejecutar fácilmente el código anterior y ver la función en acción en nuestros ejemplos de GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Junto con la biblioteca Python completa, ofrecemos aplicaciones en línea gratuitas, simples pero potentes.

Para generar firmas de imagen y/o firmar sus archivos con ellas de forma gratuita, puede usar la aplicación en línea [Generate Image](https://products.groupdocs.app/signature/generate/image).

Para firmar PDF, Word, Excel, PowerPoint y otros documentos, puede usar las demás aplicaciones en línea de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
