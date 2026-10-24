---
title: "Firmar documento con firma digital"
linkTitle: "Digital Signature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Conozca los beneficios de usar firmas digitales para firmar documentos de forma segura. Descubra cómo agregar firmas digitales programáticamente en Python con instrucciones paso a paso."
type: docs
url: /es/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

En la era digital actual, garantizar la autenticidad e integridad de los documentos electrónicos es crucial. Un método muy eficaz para lograrlo es el uso de firmas digitales. En esta guía, exploraremos el mundo de las firmas digitales, explicando qué son, por qué son esenciales y cómo puede utilizar GroupDocs.Signature for Python via .NET para firmar electrónicamente sus documentos de manera fluida.

## What is a Digital Signature?

Una firma digital es un mecanismo criptográfico para verificar la autenticidad e integridad de los documentos electrónicos. Proporciona una fuerte garantía de que el documento proviene de un remitente conocido y no ha sido alterado por fuentes no autorizadas. Las firmas digitales suelen representarse mediante certificados que contienen claves privadas (para firmar) y públicas (para verificar). Diversos estándares de criptografía de clave pública, como el formato PFX, se utilizan comúnmente para este fin.
La imagen a continuación muestra cómo se ve una firma digital en una página de documento PDF de forma predeterminada.

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

Los certificados expirados y aún no válidos son rechazados: `sign` genera [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) con un mensaje como "El certificado de firma expiró el ...". Para firmar de todos modos con dicho certificado, establezca `allow_expired` o `allow_not_yet_valid` en `True`.

### Follow these steps to sign your documents with a digital signature

1. Instale el paquete GroupDocs.Signature usando pip:
```bash
pip install groupdocs-signature-net
```

2. Cree una nueva instancia de la clase [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) y pase la ruta del documento fuente como parámetro del constructor.
3. Instancie el objeto [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) con el certificado requerido y su contraseña.
4. Llame al método [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) de la instancia de la clase [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) y pase el [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) a este.

El ejemplo a continuación muestra cómo firmar un documento PDF con una firma electrónica digital usando Python. Podemos firmar cualquier otro formato de documento compatible de la misma manera.

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Crear opciones de firma digital con el archivo de certificado
        options = DigitalSignOptions("certificate.pfx")

        # Establecer la contraseña del certificado
        options.password = "1234567890"

        # Opcional: una imagen que muestra la firma en la página
        options.image_file_path = "signature.jpg"

        # Establecer la posición de la firma
        options.left = 100
        options.top = 400

        # Firma el documento y guarda el resultado
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` es el certificado de ejemplo utilizado en este ejemplo (contraseña `1234567890`). Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) para descargarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) para descargarlo.

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Puede personalizar aún más la firma digital con opciones adicionales: el tamaño de la firma en la página, y el contacto, motivo y ubicación almacenados en ella:

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Pase el certificado y la imagen de apariencia al constructor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Muestre la firma en la página, en esta posición y tamaño
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Información almacenada en la firma
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` es el certificado de ejemplo utilizado en este ejemplo (contraseña `1234567890`). Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) para descargarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` es el archivo de ejemplo utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) para descargarlo.

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

También puede cargar el certificado desde un flujo. Mantenga el flujo abierto hasta que `sign` devuelva:

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Cargue el certificado desde un flujo
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Establecer la posición y el tamaño de la firma
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` es el certificado de ejemplo utilizado en este ejemplo (contraseña `1234567890`). Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) para descargarlo.

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Esta guía muestra cómo usar [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) para firmar documentos con firmas digitales. Explica cómo cargar documentos, configurar firmas basadas en certificados y guardar los archivos firmados de forma segura. También se cubren funciones avanzadas, como la apariencia de la firma y la información almacenada en la firma. Consulte los recursos relacionados para obtener más detalles sobre los flujos de trabajo de firma digital.

## More Resources

### GitHub Examples

Puede ejecutar fácilmente el código anterior y ver la función en acción en nuestros ejemplos de GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Junto con la biblioteca Python completa, ofrecemos aplicaciones en línea gratuitas, simples pero potentes.

Para firmar PDF, Word, Excel, PowerPoint y otros documentos, puedes usar las aplicaciones en línea de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
