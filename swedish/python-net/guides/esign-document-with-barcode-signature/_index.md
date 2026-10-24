---
title: "eSign-dokument med streckkodssignatur"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Den här artikeln förklarar hur du lägger till en streckkodssignatur på dokumentsidan med olika alternativ såsom streckkodstyp, streckkodstext, placering, justering och andra visuella inställningar med GroupDocs.Signature för Python via .NET."
type: docs
url: /sv/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

En **barcode** eller **bar code** är ett sätt att presentera data i en visuell, maskinläsbar form. Generellt sett är en streckkod en bild i rektangulär form som består av parallella svarta linjer och vita mellanrum med olika bredd.
Streckkoder används i olika områden där snabb identifiering är nödvändig – som en del av köpprocessen i detaljhandeln, i lager för att spåra inventarier och på fakturor för att underlätta bokföring, bland många andra användningsområden.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Streckkoder möjliggör lagring av produktrelaterad data såsom tillverknings- och utgångsdatum, tillverkarens namn, ursprungsland och produktpris. Det finns många streckkodstyper idag eftersom olika företag använder olika kombinationer av siffror och streck i sina streckkoder beroende på deras behov. Ur ett dokumentsignaturperspektiv kan Barcode innehålla olika tecken (bokstäver, siffror eller symboler) och kan ha varierande längder och storlekar beroende på typ och inställningar för att lagra signaturinformation, titel, ämne eller kort krypterad data.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
För att ange olika alternativ för Barcode‑signatur tillhandahåller GroupDocs.Signature för Python via .NET klassen [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). De viktigaste fälten är:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

Här är stegen för att eSigna ett dokument med Barcode‑signatur med hjälp av GroupDocs.Signature för Python via .NET‑API:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Det här exemplet visar hur man signerar ett PDF‑dokument med en Barcode‑signatur med Python:

{{< tabs "sign_with_barcode_signature" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Skapa alternativ för streckkodssignatur med texten som ska kodas
        options = BarcodeSignOptions("John Smith")

        # Ange streckkodstypen
        options.encode_type = BarcodeTypes.CODE128

        # Ange streckkodens position och storlek
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Signera dokumentet och spara resultatet
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Du kan anpassa streckkodssignaturen ytterligare med ytterligare alternativ: justering och marginaler, stapelfärg, positionen för den kodade texten, innermarginaler, bakgrund, ram och transparens:

{{< tabs "sign_with_barcode_signature_advanced" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Skicka texten och streckkodstypen till konstruktorn
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Placera streckkoden i nedre högra hörnet av sidan
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Stapelfärg, kodad text under staplarna, utrymme innanför ramen
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Bakgrund, ram och transparens
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature stöder olika streckkodstyper. Varje typ accepterar sin egen uppsättning tecken och längder, så välj text som matchar typen. Detta exempel signerar ett dokument med fyra streckkoder av olika typer i ett anrop:

{{< tabs "sign_with_different_barcode_types" >}}
{{< tab \"Python\" >}}
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

    # Ett signeringsalternativobjekt per streckkod, placerat ett under det andra
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Denna guide visar hur du använder [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) för att lägga till streckkodbaserade signaturer i dokument. Den täcker skapande, konfiguration och tillämpning av streckkodssignaturer med stöd för olika streckkodstyper och anpassningsalternativ. För vidare utforskning, se relaterade guider om dokumentinformation och avancerade signeringstekniker.

## More Resources

### GitHub Examples

Du kan enkelt köra koden ovan och se funktionen i praktiken i våra GitHub-exempel:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tillsammans med det fullständiga Python-biblioteket erbjuder vi enkla men kraftfulla gratis online‑appar.

För att generera streckkoder och/eller signera dina filer med streckkoder gratis, kan du använda den online‑appen [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode).

För att signera PDF, Word, Excel, PowerPoint och andra dokument kan du använda de andra online‑apparna från **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
