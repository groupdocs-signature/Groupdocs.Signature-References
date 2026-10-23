---
title: "Dokument mit Barcode‑Signatur elektronisch signieren"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Dieser Artikel erklärt, wie man einer Dokumentenseite eine Barcode‑Signatur mit verschiedenen Optionen wie Barcode‑Typ, Barcode‑Text, Positionierung, Ausrichtung und anderen visuellen Einstellungen mit GroupDocs.Signature für Python über .NET hinzufügt."
type: docs
url: /de/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

Ein **barcode** oder **bar code** ist eine Methode, Daten in einer visuellen, maschinenlesbaren Form darzustellen. Im Allgemeinen ist ein Barcode ein Bild in rechteckiger Form, das aus parallelen schwarzen Linien und weißen Zwischenräumen unterschiedlicher Breite besteht.
Barcodes werden in verschiedenen Bereichen eingesetzt, in denen eine schnelle Identifizierung erforderlich ist – als Teil des Kaufvorgangs in Einzelhandelsgeschäften, in Lagerhäusern zur Bestandsverfolgung und auf Rechnungen zur Unterstützung der Buchhaltung, neben vielen anderen Anwendungen.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Barcodes ermöglichen die Speicherung produktbezogener Daten wie Herstellungs- und Verfallsdaten, Herstellername, Herkunftsland und Produktpreis. Heutzutage gibt es zahlreiche Barcode‑Typen, da verschiedene Unternehmen je nach Bedarf unterschiedliche Kombinationen von Zahlen und Strichen in ihren Barcodes verwenden. Aus Sicht der Dokumentensignatur kann ein Barcode verschiedene Zeichen (Buchstaben, Ziffern oder Symbole) enthalten und je nach Typ und Einstellungen unterschiedliche Längen und Größen aufweisen, um Signaturinformationen, Titel, Betreff oder kurze verschlüsselte Daten zu speichern.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Um verschiedene Optionen für die Barcode‑Signatur anzugeben, stellt GroupDocs.Signature für Python über .NET die Klasse [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) bereit. Die wichtigsten Felder sind:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

Hier sind die Schritte, um ein Dokument mit der Barcode‑Signatur mithilfe der GroupDocs.Signature für Python über .NET‑API elektronisch zu signieren:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Dieses Beispiel zeigt, wie man ein PDF‑Dokument mit einer Barcode‑Signatur unter Verwendung von Python signiert:

{{< tabs \"sign_with_barcode_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Erstellen Sie Barcode‑Signaturoptionen mit dem zu codierenden Text
        options = BarcodeSignOptions("John Smith")

        # Legen Sie den Barcode‑Typ fest
        options.encode_type = BarcodeTypes.CODE128

        # Legen Sie die Barcode‑Position und -Größe fest
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Signiere das Dokument und speichere das Ergebnis.
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab \"signed_barcode.pdf\" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Sie können die Barcode‑Signatur weiter anpassen mit zusätzlichen Optionen: Ausrichtung und Ränder, Strichfarbe, Position des codierten Textes, innere Ränder, Hintergrund, Rahmen und Transparenz:

{{< tabs \"sign_with_barcode_signature_advanced\" >}}
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
        # Übergeben Sie den Text und den Barcode‑Typ an den Konstruktor
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Platzieren Sie den Barcode in der rechten unteren Ecke der Seite
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Strichfarbe, codierter Text unter den Strichen, Abstand innerhalb des Rahmens
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Hintergrund, Rand und Transparenz
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

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab \"signed_barcode_advanced.pdf\" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature unterstützt verschiedene Barcode-Typen. Jeder Typ akzeptiert seinen eigenen Zeichensatz und seine eigenen Längen, daher wählen Sie den Text passend zum Typ aus. Dieses Beispiel signiert ein Dokument mit vier Barcodes unterschiedlicher Typen in einem Aufruf:

{{< tabs \"sign_with_different_barcode_types\" >}}
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

    # Ein Signatur-Optionen-Objekt pro Barcode, untereinander angeordnet
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

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab \"signed_barcode_types.pdf\" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Dieses Handbuch zeigt, wie man [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) verwendet, um barcodebasierte Signaturen zu Dokumenten hinzuzufügen. Es behandelt das Erstellen, Konfigurieren und Anwenden von Barcode‑Signaturen mit Unterstützung verschiedener Barcode‑Typen und Anpassungsoptionen. Für weiterführende Informationen siehe die zugehörigen Handbücher zu Dokumentinformationen und fortgeschrittenen Signaturtechniken.

## More Resources

### GitHub Examples

Sie können den obigen Code ganz einfach ausführen und die Funktion in Aktion in unseren GitHub‑Beispielen sehen:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Zusammen mit der voll ausgestatteten Python‑Bibliothek bieten wir einfache, aber leistungsstarke kostenlose Online‑Apps an.

Um Barcodes zu erzeugen und/oder Ihre Dateien kostenlos mit Barcodes zu signieren, können Sie die Online‑App [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode) verwenden.

Um PDF-, Word-, Excel-, PowerPoint- und andere Dokumente zu signieren, können Sie die anderen Online‑Apps aus der **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** verwenden.
