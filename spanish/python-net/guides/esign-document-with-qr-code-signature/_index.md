---
title: "Documento eSign con firma de código QR"
linkTitle: "QR Code Signature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Este artículo explica cómo firmar documentos con firma electrónica como código QR en la página del documento con GroupDocs.Signature para Python a través de la API .NET."
type: docs
url: /es/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

El código QR (o Quick Response code) es una especie de [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) bidimensional que consiste en cuadrados negros dispuestos en una cuadrícula cuadrada sobre un fondo blanco. Los códigos QR pueden ser leídos por cámaras de teléfonos inteligentes o dispositivos especializados dedicados a la lectura de QR: escáneres portátiles, terminales de mano, escáneres de escritorio, escáneres integrados, etc. Normalmente los códigos QR contienen datos que apuntan a un sitio web o aplicación, correos electrónicos o números de teléfono, identificadores de productos o rastreadores. Por lo tanto, el alcance de las aplicaciones del código QR se extiende desde el marketing general y la identificación de artículos hasta la gestión de documentos.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Código Aztec | DataMatrix code | GS1 DataMatrix | GS1 QR code | QR |
| --- | --- | --- | --- | --- | --- |
| **Application** | * transporte y emisión de boletos;<br> * en la industria aérea para tarjetas de embarque electrónicas;<br> * en ferrocarril para boletos vendidos en línea e impresos por los clientes o mostrados en pantallas de teléfonos móviles. El código es escaneado por un escáner de mano por el personal a bordo del tren o en el torniquete para validar el boleto.<br> * medicina - pulseras de identificación del paciente y etiquetas para medicamentos de uso unitario, etc. | * medios impresos como etiquetas y cartas;<br> * propósitos de ingeniería industrial - marcaje de componentes, etc.;<br>  * industria alimentaria - para evitar que los productos alimenticios se empaqueten y daten incorrectamente; | Usado en<br> * Salud;<br> * Gobierno;<br> * Industria.<br> Codifica información adicional del artículo, como:<br> * peso;<br> * fecha de caducidad;<br> * número de lote;<br> * fecha de fabricación;<br> * etc. | Usado en marketing para codificar información adicional del artículo en el paquete | Ampliamente usado en la industria automotriz y aplicaciones móviles. Útil para codificar una gran cantidad de caracteres de datos y URLs específicas. |
| **Length** | 3067 alfanuméricos,<br> 3832 numéricos,<br> 1914 bytes | 2335 alfanuméricos,<br> 3116 numéricos | 2335 alfanuméricos,<br> 3116 numéricos,<br> 1556 bytes | 7089 alfanuméricos,<br> 4296 numéricos,<br> 2953 bytes | 4296 alfanuméricos,<br> 7089 numéricos,<br> 2953 bytes |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

Al agregar una firma electrónica de código QR a un documento, los ajustes principales son el texto a codificar y el [tipo de código QR](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) que debe especificarse mediante la clase [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions).

Estos son los pasos para firmar electrónicamente un documento con la firma de código QR:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

El fragmento de código a continuación demuestra cómo firmar un documento PDF con la firma de código QR usando Python:

{{< tabs "sign_with_qr_code_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Crear opciones de firma de código QR con el texto a codificar
        options = QrCodeSignOptions("John Smith")

        # Establecer el tipo de código QR
        options.encode_type = QrCodeTypes.QR

        # Establecer la posición y el tamaño del código QR
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Firma el documento y guarda el resultado
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo usado en este caso. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

Los otros tipos de códigos QR de la tabla anterior se establecen de la misma manera, por ejemplo `QrCodeTypes.AZTEC` o `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Aquí hay un ejemplo que muestra cómo crear una firma de código QR más compleja con personalización adicional: alineación y márgenes, color del módulo, fondo y borde:

{{< tabs \"sign_with_qr_code_signature_advanced\" >}}
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
        # Pase el texto y el tipo de código QR al constructor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Coloque el código QR en la esquina inferior derecha de la página
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Color del módulo, fondo y un borde punteado con algo de espacio interior
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

`sample.pdf` es el archivo de ejemplo usado en este caso. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Esta guía demuestra cómo agregar firmas de códigos QR a documentos usando [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Incluye pasos para generar una firma de código QR, configurar sus propiedades como el tamaño y la codificación, y aplicarla a un documento. Las firmas de códigos QR pueden usarse para una verificación rápida del documento firmado.

## More Resources

### GitHub Examples

Puede ejecutar fácilmente el código anterior y ver la función en acción en nuestros ejemplos de GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Junto con la biblioteca Python completa, ofrecemos aplicaciones en línea gratuitas, simples pero potentes.

Para generar códigos QR y/o firmar sus archivos con códigos QR de forma gratuita, puede usar la aplicación en línea [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode).

Para firmar PDF, Word, Excel, PowerPoint y otros documentos, puede usar las demás aplicaciones en línea de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
