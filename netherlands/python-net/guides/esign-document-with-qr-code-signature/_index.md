---
title: "eSign Document met QR‑codehandtekening"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Dit artikel legt uit hoe u documenten kunt ondertekenen met een elektronische handtekening als QR‑code op een documentpagina met GroupDocs.Signature voor Python via .NET API."
type: docs
url: /nl/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR‑code (of Quick Response‑code) is een soort tweedimensionale [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) die bestaat uit zwarte vierkanten gerangschikt in een vierkant raster op een witte achtergrond. QR‑codes kunnen worden gelezen door smartphone‑camera's of gespecialiseerde apparaten die zijn bedoeld voor QR‑lezen – hand‑scanners, handige terminals, desktop‑scanners, ingebedde scanners, enzovoort. Meestal bevatten QR‑codes gegevens die verwijzen naar een website of applicatie, e‑mails, of telefoonnummers, productidentifiers, of trackers. Daarom strekt het toepassingsgebied van QR‑codes zich uit van algemene marketing en productidentificatie tot documentbeheer.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec‑code | DataMatrix-code | GS1 DataMatrix | GS1 QR-code | QR |
| --- | --- | --- | --- | --- | --- |
| **Applicatie** | * transport en ticketing;<br> * in de luchtvaartindustrie voor elektronische instapkaarten;<br> * in de spoorweg voor tickets die online worden verkocht en door klanten worden afgedrukt of weergegeven op mobiele telefoonschermen. De code wordt gescand door een handscanner door personeel in de trein of bij de slagboom om het ticket te valideren.<br> * geneeskunde - patiëntidentificatiearmbanden en labels voor eenmalig te gebruiken medicatie enz. | * gedrukte media zoals etiketten en brieven;<br> * industriële engineeringdoeleinden - componenten markeren enz.;<br>  * voedingsindustrie - om te voorkomen dat voedingsproducten onjuist verpakt en gedateerd worden; | Gebruikt in<br> * Gezondheidszorg;<br> * Overheid;<br> * Industrie.<br> Codeert aanvullende iteminformatie, zoals:<br> * gewicht;<br> * houdbaarheidsdatum;<br> * batchnummer;<br> * productiedatum;<br> * enz. | Gebruikt in marketing om aanvullende iteminformatie op de verpakking te coderen | Veelgebruikt in de auto-industrie en mobiele toepassingen. Handig voor het coderen van een grote hoeveelheid gegevenskarakters en specifieke URL's. |
| **Lengte** | 3067 alfanumeriek,<br> 3832 numeriek,<br> 1914 bytes | 2335 alfanumeriek,<br> 3116 numeriek | 2335 alfanumeriek,<br> 3116 numeriek,<br> 1556 bytes | 7089 alfanumeriek,<br> 4296 numeriek,<br> 2953 bytes | 4296 alfanumeriek,<br> 7089 numeriek,<br> 2953 bytes |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

Bij het toevoegen van een QR-code elektronische handtekening aan een document, zijn de belangrijkste instellingen de te coderen tekst en het [type van de QR-code](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) dat moet worden gespecificeerd via de [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) klasse.

Hier zijn de stappen om een document elektronisch te ondertekenen met de QR-code handtekening:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

De onderstaande codefragment toont hoe een PDF-document te ondertekenen met de QR-code handtekening met behulp van Python:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Maak QR-code handtekeningopties aan met de te coderen tekst
        options = QrCodeSignOptions("John Smith")

        # Stel het QR-code type in
        options.encode_type = QrCodeTypes.QR

        # Stel de QR-code positie en grootte in
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Onderteken het document en sla het resultaat op
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signed_qr_code.pdf" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

De andere QR‑code‑typen uit de bovenstaande tabel worden op dezelfde manier ingesteld, bijvoorbeeld `QrCodeTypes.AZTEC` of `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Hier is een voorbeeld dat laat zien hoe je een complexere QR‑code‑handtekening maakt met extra aanpassingen: uitlijning en marges, modulekleur, achtergrond en rand:

{{< tabs "sign_with_qr_code_signature_advanced" >}}
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
        # Geef de tekst en het QR code-type door aan de constructor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Plaats de QR code in de rechteronderhoek van de pagina
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Modulkleur, achtergrond en een gestippelde rand met wat ruimte binnenin
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "signed_qr_code_advanced.pdf" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Deze gids laat zien hoe je QR‑code‑handtekeningen aan documenten toevoegt met behulp van [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Het bevat stappen voor het genereren van een QR‑code‑handtekening, het configureren van de eigenschappen zoals grootte en codering, en het toepassen ervan op een document. QR‑code‑handtekeningen kunnen worden gebruikt voor snelle verificatie van het ondertekende document.

## More Resources

### GitHub Examples

U kunt de bovenstaande code eenvoudig uitvoeren en de functie in actie zien in onze GitHub-voorbeelden:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Naast de volledig uitgeruste Python-bibliotheek bieden we eenvoudige maar krachtige gratis online apps.

Om gratis QR‑codes te genereren en/of je bestanden met QR‑codes te ondertekenen, kun je de online app [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode) gebruiken.

Om PDF-, Word-, Excel-, PowerPoint- en andere documenten te ondertekenen, kunt u de andere online apps uit de **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** gebruiken.
