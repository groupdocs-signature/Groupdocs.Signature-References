---
title: "eSign-Dokument mit Bild‑Signatur"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Dieser Artikel zeigt, wie man ein Signatur‑Bild auf einer Dokumentenseite mit GroupDocs.Signature für Python über .NET hinzufügt."
type: docs
url: /de/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

Ein **Bild** als Signatur ist eine alternative Möglichkeit, beliebige präsentierte Daten visuell darzustellen. Dieser elektronische Signaturtyp ermöglicht die Erstellung benutzerdefinierter Bilder mit Firmenlogo, Initialen des Absenders, Namen usw.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Hier sind die Schritte, um eine Bild‑Signatur auf einer Dokumentenseite zu erstellen:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Dieses Beispiel zeigt, wie man ein PDF‑Dokument mit der Bild‑Signatur mithilfe von Python signiert:

{{< tabs \"sign_with_image_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Erstelle Bildsignatur‑Optionen mit der Bilddatei
        options = ImageSignOptions("signature.jpg")

        # Setze Signaturposition und -größe
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # Signiere das Dokument und speichere das Ergebnis.
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) zum Herunterladen.

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

Sie können die Bildsignatur weiter anpassen mit zusätzlichen Optionen: Ausrichtung und Ränder, Drehung, Transparenz und einem Rahmen. Wenn eine Ausrichtung festgelegt ist, ersetzt sie die `left`‑ oder `top`‑Koordinate, und das `margin` verschiebt die Signatur vom Seitenrand.

{{< tabs \"sign_with_image_signature_advanced\" >}}
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

        # Platzieren Sie die Signatur in der unteren rechten Ecke der Seite
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Drehen Sie das Bild und machen Sie es zu 20 % transparent
        options.rotation_angle = 10
        options.transparency = 0.2

        # Zeichnen Sie einen gestrichelten Rahmen um das Bild
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

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) zum Herunterladen.

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

Sie können das Signaturbild auch aus einem Stream laden. Halten Sie den Stream offen, bis `sign` zurückkehrt:

{{< tabs \"sign_with_image_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # Laden Sie das Signaturbild aus einem Stream
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

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) zum Herunterladen.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) zum Herunterladen.

{{< /tab >}}
{{< tab \"signed_image_stream.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Dieser Leitfaden zeigt, wie man [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) verwendet, um bildbasierte Signaturen zu Dokumenten hinzuzufügen. Er behandelt das Laden eines Dokuments, das Konfigurieren der Eigenschaften der Bildsignatur (wie Größe, Position und Transparenz) und das Speichern des signierten Dokuments. Erweiterte Anpassungsoptionen, wie das Anpassen des Bildaussehens und das Ausrichten der Signatur, werden ebenfalls behandelt. Für weiterführende Einblicke erkunden Sie verwandte Ressourcen zum Dokumentensignieren.

## More Resources

### GitHub Examples

Sie können den obigen Code ganz einfach ausführen und die Funktion in Aktion in unseren GitHub‑Beispielen sehen:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Zusammen mit der voll ausgestatteten Python‑Bibliothek bieten wir einfache, aber leistungsstarke kostenlose Online‑Apps an.

Um Bildsignaturen zu erstellen und/oder Ihre Dateien kostenlos damit zu signieren, können Sie die Online‑App [Generate Image](https://products.groupdocs.app/signature/generate/image) nutzen.

Um PDF-, Word-, Excel-, PowerPoint- und andere Dokumente zu signieren, können Sie die anderen Online‑Apps aus der **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** verwenden.
