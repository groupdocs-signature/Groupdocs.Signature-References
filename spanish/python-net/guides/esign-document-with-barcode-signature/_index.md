---
title: "Firma electrónica de documento con firma de código de barras"
linkTitle: "Barcode Signature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Este artículo explica cómo agregar una firma de código de barras en la página del documento con varias opciones como tipo de código de barras, texto del código de barras, posicionamiento, alineación y otras configuraciones visuales con GroupDocs.Signature para Python a través de .NET"
type: docs
url: /es/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

Un **barcode** o **bar code** es una forma de presentar datos en una forma visual y legible por máquinas. En términos generales, el código de barras es una imagen de forma rectangular que consiste en líneas negras paralelas y espacios blancos de diferentes anchuras.
Los códigos de barras se utilizan en diversas áreas donde es necesaria una identificación rápida, como parte del proceso de compra en tiendas minoristas, en almacenes para rastrear inventario y en facturas para ayudar en la contabilidad, entre muchos otros usos.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Los códigos de barras permiten almacenar datos relacionados con el producto, como fechas de fabricación y caducidad, nombre del fabricante, país de origen y precio del producto. Hoy en día existen muchos tipos de códigos de barras porque diferentes empresas utilizan distintas combinaciones de números y barras en sus códigos según sus necesidades. Desde la perspectiva de la firma de documentos, el código de barras puede contener diferentes caracteres (letras, dígitos o símbolos) y puede tener diversas longitudes y tamaños según el tipo y la configuración para conservar información de la firma, título, asunto o datos cifrados breves.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Para especificar diferentes opciones para la firma de código de barras, GroupDocs.Signature para Python a través de .NET proporciona la clase [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). Los campos principales son:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

A continuación se presentan los pasos para firmar electrónicamente un documento con la firma de código de barras usando GroupDocs.Signature para Python a través de la API .NET:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Este ejemplo muestra cómo firmar un documento PDF con una firma de código de barras usando Python:

{{< tabs \"sign_with_barcode_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Crear opciones de firma de código de barras con el texto a codificar
        options = BarcodeSignOptions("John Smith")

        # Establecer el tipo de código de barras
        options.encode_type = BarcodeTypes.CODE128

        # Establecer la posición y el tamaño del código de barras
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Firma el documento y guarda el resultado
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo utilizado en este caso. Haz clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"signed_barcode.pdf\" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Puedes personalizar aún más la firma de código de barras con opciones adicionales: alineación y márgenes, color de la barra, posición del texto codificado, márgenes internos, fondo, borde y transparencia:

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
        # Pasar el texto y el tipo de código de barras al constructor
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Colocar el código de barras en la esquina inferior derecha de la página
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Color de la barra, texto codificado debajo de las barras, espacio dentro del borde
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Fondo, borde y transparencia
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

`sample.pdf` es el archivo de ejemplo utilizado en este caso. Haz clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"signed_barcode_advanced.pdf\" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature admite varios tipos de códigos de barras. Cada tipo acepta su propio conjunto de caracteres y longitudes, por lo que debes elegir el texto que coincida con el tipo. Este ejemplo firma un documento con cuatro códigos de barras de diferentes tipos en una sola llamada:

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

    # Un objeto de opciones de firma por código de barras, colocado uno debajo del otro
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

`sample.pdf` es el archivo de ejemplo utilizado en este caso. Haz clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Esta guía demuestra cómo usar [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) para agregar firmas basadas en códigos de barras a documentos. Cubre la creación, configuración y aplicación de firmas de códigos de barras con soporte para varios tipos de códigos de barras y opciones de personalización. Para una mayor exploración, consulte las guías relacionadas sobre información de documentos y técnicas avanzadas de firma.

## More Resources

### GitHub Examples

Puede ejecutar fácilmente el código anterior y ver la función en acción en nuestros ejemplos de GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Junto con la biblioteca Python completa, ofrecemos aplicaciones en línea gratuitas, simples pero potentes.

Para generar códigos de barras y/o firmar sus archivos con códigos de barras de forma gratuita, puede usar la aplicación en línea [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode).

Para firmar PDF, Word, Excel, PowerPoint y otros documentos, puede usar las demás aplicaciones en línea de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
