---
title: "eSign-document met teksthandtekening"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Dit artikel legt uit hoe je een document ondertekent met een teksthandtekening met behulp van GroupDocs.Signature for Python via .NET API. Leer hoe je een digitale handtekening programmatisch toevoegt aan een PDF in Python."
type: docs
url: /nl/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

Een **Text** elektronische handtekening is een willekeurige tekst die aan een document wordt toegevoegd op een native manier, afhankelijk van het type document. GroupDocs.Signature biedt de teksthandtekeningfunctie en maakt het mogelijk om een breed scala aan tekstopstellingen aan te passen – van lettertype, grootte en kleur tot uitlijning, randen, schaduweffecten enz. Zo kan een teksthandtekening eruitzien:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Laten we proberen een teksthandtekening toe te voegen aan een PDF programmatisch met Python.

Om teksthandtekeningen programmatisch te manipuleren biedt [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) de klasse [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) en verloopt de volledige workflow als volgt:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Dit voorbeeld toont hoe je een teksthandtekening toevoegt aan een document met Python:

{{< tabs "sign_with_text_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Maak teksthandtekeningopties
        options = TextSignOptions("John Smith")

        # Stel handtekeningpositie en -grootte in
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Stel tekstkleur en lettertype in
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Onderteken het document en sla het resultaat op
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Je kunt de teksthandtekening verder aanpassen met extra opties: uitlijning en marges, lettertype, achtergrond, rand, rotatie en transparantie. Wanneer een uitlijning is ingesteld, vervangt deze de `left` of `top` coördinaat, en de `margin` verschuift de handtekening vanaf de paginarand.

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

        # Plaats de handtekening in de rechteronderhoek van de pagina
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Lettertype en tekstkleur
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Achtergrond, rand, rotatie en transparantie
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

        # Render de tekst als een afbeelding, die ook de rand op PDF-pagina's tekent
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signed_text_advanced.pdf" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Deze gids legt uit hoe u tekstgebaseerde handtekeningen aan documenten kunt toevoegen met [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Het behandelt het configureren van teksteigenschappen zoals lettertype, kleur, grootte en positie, en het toepassen van de tekstehandsignature op een document. Het ondertekende document wordt vervolgens opgeslagen met de toegevoegde tekstehandsignature.

## More Resources

### GitHub Examples

U kunt de bovenstaande code eenvoudig uitvoeren en de functie in actie zien in onze GitHub-voorbeelden:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Naast de volledig uitgeruste Python-bibliotheek bieden we eenvoudige maar krachtige gratis online apps.

Om PDF, Word, Excel, PowerPoint en andere documenten te ondertekenen, kun je de online apps van de **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** gebruiken.
