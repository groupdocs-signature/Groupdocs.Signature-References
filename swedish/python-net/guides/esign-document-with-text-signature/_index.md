---
title: "eSign-dokument med textsignatur"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Denna artikel förklarar hur man signerar ett dokument med textsignatur med hjälp av GroupDocs.Signature for Python via .NET API. Lär dig hur du lägger till en digital signatur i en PDF programatiskt i Python."
type: docs
url: /sv/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

En **Text**-elektronisk signatur är en godtycklig text som läggs till i ett dokument på ett naturligt sätt beroende på dokumentets typ. GroupDocs.Signature tillhandahåller funktionen för textsignatur och möjliggör anpassning av ett brett spektrum av textinställningar – från typsnittsnamn, storlek och färg till justering, ramar, skuggeffekter etc. Så här kan en textsignatur se ut:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Låt oss försöka lägga till en textsignatur i en PDF programatiskt med Python.

För att manipulera textsignaturer programatiskt [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) tillhandahåller klassen [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) och hela arbetsflödet är lika enkelt som följer:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Detta exempel visar hur man lägger till en textsignatur i ett dokument med Python:

{{< tabs \"sign_with_text_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Skapa alternativ för textsignatur
        options = TextSignOptions("John Smith")

        # Ange signaturens position och storlek
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Ange textfärg och teckensnitt
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Signera dokumentet och spara resultatet
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"signed_text.pdf\" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Du kan anpassa textsignaturen ytterligare med ytterligare alternativ: justering och marginaler, teckensnittsstil, bakgrund, ram, rotation och transparens. När en justering är inställd ersätter den `left` eller `top` koordinaten, och `margin` förskjuter signaturen från sidans kant.

{{< tabs \"sign_with_text_signature_advanced\" >}}
{{< tab \"Python\" >}}
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

        # Placera signaturen i nedre högra hörnet på sidan
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Teckensnittsstil och textfärg
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Bakgrund, ram, rotation och transparens
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

        # Rendera texten som en bild, vilket också ritar ramen på PDF-sidor
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"signed_text_advanced.pdf\" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Denna guide förklarar hur man lägger till textbaserade signaturer i dokument med [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Den täcker konfiguration av textegenskaper såsom teckensnitt, färg, storlek och position, samt applicering av textsignaturen på ett dokument. Det signerade dokumentet sparas sedan med den tillagda textsignaturen.

## More Resources

### GitHub Examples

Du kan enkelt köra koden ovan och se funktionen i praktiken i våra GitHub-exempel:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tillsammans med det fullständiga Python-biblioteket erbjuder vi enkla men kraftfulla gratis online‑appar.

För att signera PDF, Word, Excel, PowerPoint och andra dokument kan du använda de online‑apparna från **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
