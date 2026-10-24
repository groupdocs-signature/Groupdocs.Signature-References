---
title: "eSign-dokument med QR‑kod‑signatur"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Den här artikeln förklarar hur du signerar dokument med elektronisk signatur som QR‑kod på dokumentsidan med GroupDocs.Signature för Python via .NET API."
type: docs
url: /sv/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR‑kod (eller Quick Response‑kod) är en typ av tvådimensionell [streckkod](/signature/python-net/guides/esign-document-with-barcode-signature/) som består av svarta fyrkanter arrangerade i ett fyrkantigt rutnät på en vit bakgrund. QR‑koder kan läsas av smarttelefonkameror eller specialiserade enheter som är avsedda för QR‑läsning – handhållna skannrar, praktiska terminaler, stationära skannrar, inbyggda skannrar osv. Vanligtvis innehåller QR‑koder data som pekar på en webbplats eller applikation, e‑post, eller telefonnummer, produktidentifierare eller spårare. Därför sträcker sig QR‑kodens tillämpningsområde från allmän marknadsföring och varuidentifiering till dokumenthantering.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec‑kod | DataMatrix‑kod | GS1 DataMatrix | GS1 QR‑kod | QR |
| --- | --- | --- | --- | --- | --- |
| **Applikation** | * transport och biljettförsäljning;<br> * i flygindustrin för elektroniska boardingkort;<br> * i järnväg för biljetter som säljs online och skrivs ut av kunder eller visas på mobiltelefonens skärm. Koden skannas av en handhållen skanner av personal ombord eller vid spärren för att validera biljetten.<br> * medicin – patientidentifieringsarmband och etiketter för enhetsdosering av läkemedel osv. | * tryckt media såsom etiketter och brev;<br> * industriella ingenjörsändamål – märkning av komponenter osv;<br>  * livsmedelsindustrin – för att förhindra att livsmedelsprodukter förpackas och datumstämplas felaktigt; | Används i<br> * sjukvård;<br> * regering;<br> * industri.<br> Kodar ytterligare information om objekt, såsom:<br> * vikt;<br> * utgångsdatum;<br> * batch‑nummer;<br> * tillverkningsdatum;<br> * osv. | Används i marknadsföring för att koda ytterligare information om objekt på förpackningen | Används i stor utsträckning inom fordonsindustrin och mobila applikationer. Användbart för att koda stora mängder datatecken och specifika URL:er. |
| **Längd** | 3067 alfanumeriska,<br> 3832 numeriska,<br> 1914 byte | 2335 alfanumeriska,<br> 3116 numeriska | 2335 alfanumeriska,<br> 3116 numeriska,<br> 1556 byte | 7089 alfanumeriska,<br> 4296 numeriska,<br> 2953 byte | 4296 alfanumeriska,<br> 7089 numeriska,<br> 2953 byte |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

När du lägger till en QR‑kod elektronisk signatur i ett dokument är de viktigaste inställningarna den text som ska kodas och [typen av QR‑kod](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) som bör specificeras via klassen [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions).

Här är stegen för att e‑signera ett dokument med QR‑kodsignaturen:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

Kodsnutten nedan visar hur man signerar ett PDF‑dokument med QR‑kodsignaturen med hjälp av Python:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Skapa QR‑kod signaturalternativ med texten som ska kodas
        options = QrCodeSignOptions("John Smith")

        # Ange QR‑kodens typ
        options.encode_type = QrCodeTypes.QR

        # Ställ in QR-kodens position och storlek
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Signera dokumentet och spara resultatet
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

De andra QR-kodtyperna från tabellen ovan ställs in på samma sätt, till exempel `QrCodeTypes.AZTEC` eller `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Här är ett exempel som visar hur man skapar en mer komplex QR-kodsignatur med ytterligare anpassning: justering och marginaler, modulfärg, bakgrund och ram:

{{< tabs \"sign_with_qr_code_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Skicka texten och QR‑kod‑typen till konstruktorn
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Placera QR‑koden i nedre högra hörnet av sidan
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Modulfärg, bakgrund och en prickad ram med lite utrymme inuti
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Den här guiden visar hur man lägger till QR-kodsignaturer i dokument med hjälp av [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Den innehåller steg för att generera en QR-kodsignatur, konfigurera dess egenskaper såsom storlek och kodning, och tillämpa den på ett dokument. QR-kodsignaturer kan användas för snabb verifiering av det signerade dokumentet.

## More Resources

### GitHub Examples

Du kan enkelt köra koden ovan och se funktionen i praktiken i våra GitHub-exempel:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tillsammans med det fullständiga Python-biblioteket erbjuder vi enkla men kraftfulla gratis online‑appar.

För att generera QR-koder och/eller signera dina filer med QR-koder gratis, kan du använda den online‑appen [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode).

För att signera PDF, Word, Excel, PowerPoint och andra dokument kan du använda de andra online‑apparna från **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
