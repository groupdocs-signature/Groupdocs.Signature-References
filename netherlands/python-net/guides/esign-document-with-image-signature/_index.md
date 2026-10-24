---
title: "eSign-document met afbeeldinghandtekening"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Dit artikel laat zien hoe u een handtekeningafbeelding aan een documentpagina kunt toevoegen met GroupDocs.Signature voor Python via .NET."
type: docs
url: /nl/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

Een **image** als handtekening is een alternatieve manier om welke presenteerbare gegevens dan ook visueel weer te geven. Dit type elektronische handtekening maakt het mogelijk om aangepaste afbeeldingen te maken met een bedrijfslogo, initialen van de afzender, namen enzovoort.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Hier zijn de stappen om een afbeeldinghandtekening op een documentpagina te maken:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Dit voorbeeld laat zien hoe u een PDF-document kunt ondertekenen met de afbeeldinghandtekening met behulp van Python:

{{< tabs "sign_with_image_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Maak afbeeldingshandtekeningopties met het afbeeldingsbestand
        options = ImageSignOptions("signature.jpg")

        # Stel handtekeningpositie en -grootte in
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # Onderteken het document en sla het resultaat op
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) om het te downloaden.

{{< /tab >}}
{{< tab "signed_image.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

U kunt de afbeeldinghandtekening verder aanpassen met extra opties: uitlijning en marges, rotatie, transparantie en een rand. Wanneer een uitlijning is ingesteld, vervangt deze de `left` of `top` coördinaat, en de `margin` verschuift de handtekening vanaf de paginarand.

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

        # Plaats de handtekening in de rechteronderhoek van de pagina
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Draai de afbeelding en maak deze 20% transparant
        options.rotation_angle = 10
        options.transparency = 0.2

        # Teken een gestippelde rand rond de afbeelding
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) om het te downloaden.

{{< /tab >}}
{{< tab "signed_image_advanced.pdf" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

U kunt de handtekeningafbeelding ook laden vanuit een stream. Houd de stream open totdat `sign` terugkeert:

{{< tabs \"sign_with_image_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # Laad de handtekeningafbeelding vanuit een stream
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) om het te downloaden.

{{< /tab >}}
{{< tab \"signed_image_stream.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Deze gids laat zien hoe u [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) kunt gebruiken om op afbeeldingen gebaseerde handtekeningen aan documenten toe te voegen. Het behandelt het laden van een document, het configureren van de eigenschappen van de afbeeldinghandtekening (zoals grootte, positie en transparantie), en het opslaan van het ondertekende document. Geavanceerde aanpassingsopties, zoals het aanpassen van het uiterlijk van de afbeelding en het uitlijnen van de handtekening, worden ook besproken. Voor meer inzicht kunt u gerelateerde bronnen over documentondertekening verkennen.

## More Resources

### GitHub Examples

U kunt de bovenstaande code eenvoudig uitvoeren en de functie in actie zien in onze GitHub-voorbeelden:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Naast de volledig uitgeruste Python-bibliotheek bieden we eenvoudige maar krachtige gratis online apps.

Om gratis afbeeldinghandtekeningen te genereren en/of uw bestanden ermee te ondertekenen, kunt u de online app [Generate Image](https://products.groupdocs.app/signature/generate/image) gebruiken.

Om PDF-, Word-, Excel-, PowerPoint- en andere documenten te ondertekenen, kunt u de andere online apps uit de **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** gebruiken.
