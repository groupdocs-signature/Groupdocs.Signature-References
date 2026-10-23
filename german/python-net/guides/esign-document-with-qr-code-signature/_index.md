---
title: "Dokument mit QR-Code-Signatur eSign"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Dieser Artikel erklärt, wie man Dokumente mit einer elektronischen Signatur als QR-Code auf der Dokumentenseite mit GroupDocs.Signature für Python über die .NET-API signiert."
type: docs
url: /de/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

Der QR-Code (oder Quick‑Response‑Code) ist eine Art zweidimensionaler [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/), der aus schwarzen Quadraten besteht, die in einem quadratischen Raster auf weißem Hintergrund angeordnet sind. QR-Codes können von Smartphone‑Kameras oder spezialisierten Geräten, die für das Lesen von QR‑Codes vorgesehen sind, gelesen werden – Handscanner, mobile Terminals, Desktop‑Scanner, integrierte Scanner usw. In der Regel enthalten QR-Codes Daten, die auf eine Website oder Anwendung, E‑Mails oder Telefonnummern, Produktkennzeichnungen oder Tracker verweisen. Daher reicht das Anwendungsspektrum von QR-Codes von allgemeinem Marketing und Artikelidentifikation bis hin zum Dokumentenmanagement.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec-Code | DataMatrix-Code | GS1 DataMatrix | GS1 QR-Code | QR |
| --- | --- | --- | --- | --- | --- |
| **Anwendung** | * Transport und Ticketing;<br> * in der Luftfahrtindustrie für elektronische Bordkarten;<br> * im Schienenverkehr für online verkaufte Tickets, die von Kunden ausgedruckt oder auf Handy‑Bildschirmen angezeigt werden. Der Code wird von einem Handscanner durch das Zugpersonal oder am Drehkreuz gescannt, um das Ticket zu validieren.<br> * Medizin – Patienten‑Identifikationsarmbänder und Etiketten für Einzeldosen‑Medikamente usw. | * gedruckte Medien wie Etiketten und Briefe;<br> * industrielle Ingenieurzwecke – Kennzeichnung von Komponenten usw.;<br>  * Lebensmittelindustrie – um zu verhindern, dass Lebensmittelprodukte falsch verpackt und datiert werden; | Verwendet in<br> * Gesundheitswesen;<br> * Regierung;<br> * Industrie.<br> Kodiert zusätzliche Informationen zum Artikel, wie:<br> * Gewicht;<br> * Verfallsdatum;<br> * Chargennummer;<br> * Herstellungsdatum;<br> * usw. | Wird im Marketing eingesetzt, um zusätzliche Artikelinformationen auf der Verpackung zu kodieren | Weit verbreitet in der Automobilindustrie und mobilen Anwendungen. Nützlich zum Kodieren großer Datenmengen und spezifischer URLs. |
| **Länge** | 3067 alphanumerisch,<br> 3832 numerisch,<br> 1914 Bytes | 2335 alphanumerisch,<br> 3116 numerisch | 2335 alphanumerisch,<br> 3116 numerisch,<br> 1556 Bytes | 7089 alphanumerisch,<br> 4296 numerisch,<br> 2953 Bytes | 4296 alphanumerisch,<br> 7089 numerisch,<br> 2953 Bytes |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

Beim Hinzufügen einer QR-Code-Elektronischen Signatur zu einem Dokument sind die Haupteinstellungen der zu codierende Text und der [Typ des QR-Codes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields), der über die Klasse [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) angegeben werden sollte.

Hier sind die Schritte, um ein Dokument mit der QR-Code-Signatur elektronisch zu signieren:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

Das untenstehende Code‑Snippet zeigt, wie man ein PDF‑Dokument mit der QR-Code-Signatur mithilfe von Python signiert:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Erstelle QR-Code‑Signatur‑Optionen mit dem zu codierenden Text
        options = QrCodeSignOptions("John Smith")

        # Lege den QR-Code‑Typ fest
        options.encode_type = QrCodeTypes.QR

        # Lege die Position und Größe des QR-Codes fest
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Signiere das Dokument und speichere das Ergebnis.
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicke [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

Die anderen QR-Code‑Typen aus der obigen Tabelle werden auf dieselbe Weise festgelegt, zum Beispiel `QrCodeTypes.AZTEC` oder `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Hier ist ein Beispiel, das zeigt, wie man eine komplexere QR-Code‑Signatur mit zusätzlichen Anpassungen erstellt: Ausrichtung und Ränder, Modulfarbe, Hintergrund und Rahmen:

{{< tabs \"sign_with_qr_code_signature_advanced\" >}}
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
        # Übergeben Sie den Text und den QR-Code-Typ an den Konstruktor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Platzieren Sie den QR-Code in der unteren rechten Ecke der Seite
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Modulfarbe, Hintergrund und ein gepunkteter Rand mit etwas Abstand innen
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

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicke [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Dieses Handbuch zeigt, wie man QR-Code‑Signaturen zu Dokumenten hinzufügt, indem man [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) verwendet. Es enthält Schritte zum Erzeugen einer QR-Code‑Signatur, zum Konfigurieren ihrer Eigenschaften wie Größe und Codierung und zum Anwenden auf ein Dokument. QR-Code‑Signaturen können für die schnelle Überprüfung des signierten Dokuments verwendet werden.

## More Resources

### GitHub Examples

Sie können den obigen Code ganz einfach ausführen und die Funktion in Aktion in unseren GitHub‑Beispielen sehen:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Zusammen mit der voll ausgestatteten Python‑Bibliothek bieten wir einfache, aber leistungsstarke kostenlose Online‑Apps an.

Um kostenlos QR-Codes zu erzeugen und/oder Ihre Dateien mit QR-Codes zu signieren, können Sie die Online‑App [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode) verwenden.

Um PDF-, Word-, Excel-, PowerPoint- und andere Dokumente zu signieren, können Sie die anderen Online‑Apps aus der **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** verwenden.
