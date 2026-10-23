---
title: "eSign-Dokument mit Textsignatur"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Dieser Artikel erklärt, wie ein Dokument mit einer Textsignatur unter Verwendung der GroupDocs.Signature for Python via .NET API signiert wird. Erfahren Sie, wie Sie programmgesteuert in Python eine digitale Signatur zu einer PDF hinzufügen."
type: docs
url: /de/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

Eine **Text**-elektronische Signatur ist ein beliebiger Text, der je nach Dokumenttyp auf native Weise zu einem Dokument hinzugefügt wird. GroupDocs.Signature bietet die Textsignatur‑Funktion und ermöglicht die Anpassung einer breiten Palette von Texteinstellungen – von Schriftname, Größe und Farbe bis hin zu Ausrichtung, Rahmen, Schatteneffekten usw. So kann eine Textsignatur aussehen:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Versuchen wir, einer PDF programmgesteuert mit Python eine Textsignatur hinzuzufügen.

Um Textsignaturen programmgesteuert zu manipulieren, stellt [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) die Klasse [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) bereit, und der gesamte Ablauf ist so einfach:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Dieses Beispiel zeigt, wie man mit Python einer Dokument eine Textsignatur hinzufügt:

{{< tabs \"sign_with_text_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Textsignatur‑Optionen erstellen
        options = TextSignOptions("John Smith")

        # Setze Signaturposition und -größe
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Textfarbe und Schrift festlegen
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Signiere das Dokument und speichere das Ergebnis.
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab \"signed_text.pdf\" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Sie können die Textsignatur weiter mit zusätzlichen Optionen anpassen: Ausrichtung und Ränder, Schriftstil, Hintergrund, Rahmen, Drehung und Transparenz. Wenn eine Ausrichtung festgelegt ist, ersetzt sie die `left`‑ oder `top`‑Koordinate, und der `margin` verschiebt die Signatur vom Seitenrand.

{{< tabs \"sign_with_text_signature_advanced\" >}}
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

        # Platzieren Sie die Signatur in der unteren rechten Ecke der Seite
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Schriftstil und Textfarbe
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Hintergrund, Rahmen, Drehung und Transparenz
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

        # Rendern Sie den Text als Bild, das ebenfalls den Rahmen auf PDF‑Seiten zeichnet
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab \"signed_text_advanced.pdf\" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Dieser Leitfaden erklärt, wie man textbasierte Signaturen zu Dokumenten mit [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) hinzufügt. Er behandelt die Konfiguration von Texteigenschaften wie Schriftart, Farbe, Größe und Position und das Anwenden der Textsignatur auf ein Dokument. Das signierte Dokument wird dann mit der hinzugefügten Textsignatur gespeichert.

## More Resources

### GitHub Examples

Sie können den obigen Code ganz einfach ausführen und die Funktion in Aktion in unseren GitHub‑Beispielen sehen:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Zusammen mit der voll ausgestatteten Python‑Bibliothek bieten wir einfache, aber leistungsstarke kostenlose Online‑Apps an.

Um PDF-, Word-, Excel-, PowerPoint- und andere Dokumente zu signieren, können Sie die Online‑Apps der **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** verwenden.
