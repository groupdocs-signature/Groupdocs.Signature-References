---
title: "eSign-dokument med bildsignatur"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Denna artikel visar hur man lägger till en signaturbild på dokumentsidan med GroupDocs.Signature för Python via .NET."
type: docs
url: /sv/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

En **image** som signatur är ett alternativt sätt att presentera data i visuell form. Denna elektroniska signaturtyp möjliggör skapandet av anpassade bilder med företagets logotyp, avsändarens initialer, namn och så vidare.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Här är stegen för att skapa en bildsignatur på en dokumentsida:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Det här exemplet visar hur man signerar ett PDF-dokument med bildsignaturen med Python:

{{< tabs "sign_with_image_signature" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Skapa bildsignaturalternativ med bildfilen
        options = ImageSignOptions("signature.jpg")

        # Ange signaturens position och storlek
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # Signera dokumentet och spara resultatet
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) för att ladda ner den.

{{< /tab >}}
{{< tab "signed_image.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

Du kan anpassa bildsignaturen ytterligare med extra alternativ: justering och marginaler, rotation, transparens och en ram. När en justering är inställd ersätter den `left`‑ eller `top`‑koordinaten, och `margin` förskjuter signaturen från sidans kant.

{{< tabs "sign_with_image_signature_advanced" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # Placera signaturen i nedre högra hörnet på sidan
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Rotera bilden och gör den 20 % transparent
        options.rotation_angle = 10
        options.transparency = 0.2

        # Rita en streckad ram runt bilden
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) för att ladda ner den.

{{< /tab >}}
{{< tab "signed_image_advanced.pdf" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

Du kan också läsa in signaturbilden från en ström. Håll strömmen öppen tills `sign` returnerar:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # Läs in signaturbilden från en ström
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) för att ladda ner den.

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Denna guide visar hur du använder [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) för att lägga till bildbaserade signaturer i dokument. Den täcker inläsning av ett dokument, konfiguration av bildsignaturens egenskaper (såsom storlek, position och transparens) samt sparande av det signerade dokumentet. Avancerade anpassningsalternativ, som att justera bildens utseende och justera signaturen, diskuteras också. För ytterligare insikter, utforska relaterade resurser för dokumentsignering.

## More Resources

### GitHub Examples

Du kan enkelt köra koden ovan och se funktionen i praktiken i våra GitHub-exempel:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tillsammans med det fullständiga Python-biblioteket erbjuder vi enkla men kraftfulla gratis online‑appar.

För att generera bildsignaturer och/eller signera dina filer med dem gratis, kan du använda den online‑appen [Generate Image](https://products.groupdocs.app/signature/generate/image).

För att signera PDF, Word, Excel, PowerPoint och andra dokument kan du använda de andra online‑apparna från **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
