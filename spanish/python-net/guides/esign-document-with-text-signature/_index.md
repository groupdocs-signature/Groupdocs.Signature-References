---
title: "Documento eSign con firma de texto"
linkTitle: "Text Signature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Este artículo explica cómo firmar un documento con una firma de Texto usando la API de GroupDocs.Signature for Python via .NET. Aprenda cómo agregar una firma digital a un PDF programáticamente en Python."
type: docs
url: /es/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

Una firma electrónica **Text** es un texto arbitrario que se agrega a un documento de forma nativa según el tipo de documento. GroupDocs.Signature ofrece la función de firma de texto y permite personalizar una amplia gama de configuraciones de texto, desde el nombre, tamaño y color de la fuente hasta la alineación, bordes, efectos de sombra, etc. Así puede verse una firma de texto:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Intentemos agregar una firma de texto a un PDF programáticamente usando Python.

Para manipular firmas de texto programáticamente, [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) proporciona la clase [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) y todo el flujo de trabajo es tan sencillo como sigue:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Este ejemplo muestra cómo agregar una firma de texto a un documento usando Python:

{{< tabs "sign_with_text_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Crear opciones de firma de texto
        options = TextSignOptions("John Smith")

        # Establecer la posición y el tamaño de la firma
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Establecer color y fuente del texto
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Firma el documento y guarda el resultado
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Puede personalizar la firma de texto aún más con opciones adicionales: alineación y márgenes, estilo de fuente, fondo, borde, rotación y transparencia. Cuando se establece una alineación, reemplaza la coordenada `left` o `top`, y el `margin` desplaza la firma desde el borde de la página.

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

        # Coloque la firma en la esquina inferior derecha de la página
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Estilo de fuente y color de texto
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Fondo, borde, rotación y transparencia
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

        # Renderizar el texto como una imagen, lo que también dibuja el borde en las páginas PDF
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab "signed_text_advanced.pdf" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Esta guía explica cómo agregar firmas basadas en texto a documentos con [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Cubre la configuración de propiedades de texto como fuente, color, tamaño y posición, y la aplicación de la firma de texto a un documento. El documento firmado se guarda luego con la firma de texto añadida.

## More Resources

### GitHub Examples

Puede ejecutar fácilmente el código anterior y ver la función en acción en nuestros ejemplos de GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Junto con la biblioteca Python completa, ofrecemos aplicaciones en línea gratuitas, simples pero potentes.

Para firmar PDF, Word, Excel, PowerPoint y otros documentos, puedes usar las aplicaciones en línea de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
