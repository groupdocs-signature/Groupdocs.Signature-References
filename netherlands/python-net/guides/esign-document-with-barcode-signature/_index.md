---
title: "Document e‑signen met Barcode-handtekening"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Dit artikel legt uit hoe je een Barcode-handtekening aan een documentpagina kunt toevoegen met verschillende opties, zoals barcode-type, barcode-tekst, positionering, uitlijning en andere visuele instellingen, met GroupDocs.Signature voor Python via .NET."
type: docs
url: /nl/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

Een **barcode** of **bar code** is een manier om gegevens visueel en machinaal leesbaar weer te geven. Over het algemeen is een barcode een afbeelding in rechthoekige vorm die bestaat uit parallelle zwarte strepen en witte ruimtes van verschillende breedtes.
Barcodes worden in verschillende gebieden gebruikt waar snelle identificatie noodzakelijk is – als onderdeel van het aankoopproces in winkels, in magazijnen om voorraad bij te houden, en op facturen om de boekhouding te ondersteunen, naast vele andere toepassingen.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Barcodes maken het mogelijk productgerelateerde gegevens op te slaan, zoals productiedata en vervaldatums, naam van de fabrikant, land van herkomst en productprijs. Er zijn tegenwoordig veel barcode‑typen omdat verschillende bedrijven verschillende combinaties van cijfers en strepen in hun barcodes gebruiken, afhankelijk van hun behoeften. Vanuit het perspectief van documenthandtekeningen kan een Barcode verschillende tekens (letters, cijfers of symbolen) bevatten en kan deze verschillende lengtes en groottes hebben, afhankelijk van het type en de instellingen, om handtekeninginformatie, titel, onderwerp of korte versleutelde gegevens op te slaan.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Om verschillende opties voor een Barcode-handtekening op te geven, biedt GroupDocs.Signature voor Python via .NET de klasse [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). De belangrijkste velden zijn:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

Hier zijn de stappen om een document te e‑signen met de Barcode-handtekening met behulp van de GroupDocs.Signature API voor Python via .NET:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Dit voorbeeld toont hoe je een PDF-document ondertekent met een Barcode-handtekening met Python:

{{< tabs "sign_with_barcode_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Maak barcode-handtekeningopties aan met de te coderen tekst
        options = BarcodeSignOptions("John Smith")

        # Stel het barcode-type in
        options.encode_type = BarcodeTypes.CODE128

        # Stel de positie en grootte van de barcode in
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Onderteken het document en sla het resultaat op
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Je kunt de barcode-handtekening verder aanpassen met extra opties: uitlijning en marges, kleur van de streep, de positie van de gecodeerde tekst, binnenmarges, achtergrond, rand en transparantie:

{{< tabs "sign_with_barcode_signature_advanced" >}}
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
        # Geef de tekst en het barcode-type door aan de constructor
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Plaats de barcode in de rechteronderhoek van de pagina
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Kleur van de streep, gecodeerde tekst onder de strepen, ruimte binnen de rand
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Achtergrond, rand en transparantie
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature ondersteunt verschillende barcode-typen. Elk type accepteert zijn eigen set tekens en lengtes, dus kies de tekst die bij het type past. Dit voorbeeld ondertekent een document met vier barcodes van verschillende typen in één oproep:

{{< tabs "sign_with_different_barcode_types" >}}
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

    # Eén ondertekeningsoptie‑object per barcode, onder elkaar geplaatst
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Deze gids toont hoe u [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) kunt gebruiken om barcode‑gebaseerde handtekeningen aan documenten toe te voegen. Het behandelt het maken, configureren en toepassen van barcode‑handtekeningen met ondersteuning voor verschillende barcode‑typen en aanpassingsopties. Voor verdere verkenning kunt u gerelateerde gidsen over documentinformatie en geavanceerde ondertekenings‑technieken raadplegen.

## More Resources

### GitHub Examples

U kunt de bovenstaande code eenvoudig uitvoeren en de functie in actie zien in onze GitHub-voorbeelden:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Naast de volledig uitgeruste Python-bibliotheek bieden we eenvoudige maar krachtige gratis online apps.

Om gratis barcodes te genereren en/of uw bestanden met barcodes te ondertekenen, kunt u de online app [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode) gebruiken.

Om PDF-, Word-, Excel-, PowerPoint- en andere documenten te ondertekenen, kunt u de andere online apps uit de **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** gebruiken.
