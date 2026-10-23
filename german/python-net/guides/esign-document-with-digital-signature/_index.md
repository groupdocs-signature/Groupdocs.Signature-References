---
title: "Dokument mit digitaler Signatur signieren"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Erfahren Sie mehr über die Vorteile der Verwendung digitaler Signaturen, um Dokumente sicher zu signieren. Entdecken Sie, wie Sie programmatisch digitale Signaturen in Python mit Schritt‑für‑Schritt‑Anleitungen hinzufügen."
type: docs
url: /de/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

Im heutigen digitalen Zeitalter ist die Gewährleistung der Authentizität und Integrität elektronischer Dokumente von entscheidender Bedeutung. Eine besonders effektive Methode, dies zu erreichen, ist die Verwendung digitaler Signaturen. In diesem Leitfaden erkunden wir die Welt der digitalen Signaturen, erklären, was sie sind, warum sie unverzichtbar sind und wie Sie GroupDocs.Signature for Python via .NET nutzen können, um Ihre Dokumente nahtlos zu eSignieren.

## What is a Digital Signature?

Eine digitale Signatur ist ein kryptografischer Mechanismus zur Überprüfung der Authentizität und Integrität elektronischer Dokumente. Sie bietet eine starke Gewährleistung, dass das Dokument von einem bekannten Absender stammt und nicht von unbefugten Quellen manipuliert wurde. Digitale Signaturen werden typischerweise durch Zertifikate dargestellt, die private (zum Signieren) und öffentliche (zur Verifizierung) Schlüssel enthalten. Verschiedene Public-Key-Kryptografie-Standards, wie das PFX-Format, werden hierfür üblicherweise verwendet.
Das Bild unten zeigt, wie eine digitale Signatur standardmäßig auf einer PDF-Dokumentseite aussieht.

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

Abgelaufene und noch nicht gültige Zertifikate werden abgelehnt: `sign` wirft [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) mit einer Meldung wie "The signing certificate expired on ...". Um trotzdem mit einem solchen Zertifikat zu signieren, setzen Sie `allow_expired` oder `allow_not_yet_valid` auf `True`.

### Follow these steps to sign your documents with a digital signature

1. Installieren Sie das GroupDocs.Signature-Paket mit pip:
```bash
pip install groupdocs-signature-net
```

2. Erstellen Sie eine neue Instanz der [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature)-Klasse und übergeben Sie den Pfad des Quelldokuments als Konstruktorparameter.
3. Instanziieren Sie das [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/)-Objekt mit dem erforderlichen Zertifikat und dessen Passwort.
4. Rufen Sie die [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/)-Methode der [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature)-Klasseninstanz auf und übergeben Sie ihr das [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/)-Objekt.

Das folgende Beispiel zeigt, wie man ein PDF-Dokument mit einer digitalen E-Signatur unter Verwendung von Python signiert. Wir können jedes andere unterstützte Dokumentformat auf dieselbe Weise signieren.

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Digitale Signaturoptionen mit der Zertifikatsdatei erstellen
        options = DigitalSignOptions("certificate.pfx")

        # Zertifikatspasswort festlegen
        options.password = "1234567890"

        # Optional: ein Bild, das die Signatur auf der Seite zeigt
        options.image_file_path = "signature.jpg"

        # Signaturposition festlegen
        options.left = 100
        options.top = 400

        # Signiere das Dokument und speichere das Ergebnis.
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` ist das Beispielzertifikat, das in diesem Beispiel verwendet wird (Passwort `1234567890`). Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx), um es herunterzuladen.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg), um sie herunterzuladen.

{{< /tab >}}
{{< tab "signed_digital.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Sie können die digitale Signatur weiter anpassen mit zusätzlichen Optionen: die Größe der Signatur auf der Seite sowie den Kontakt, Grund und Ort, die darin gespeichert sind:

{{< tabs "sign_with_digital_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Übergeben Sie das Zertifikat und das Erscheinungsbild‑Bild an den Konstruktor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Zeigen Sie die Signatur auf der Seite an dieser Position und Größe
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # In der Signatur gespeicherte Informationen
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` ist das Beispielzertifikat, das in diesem Beispiel verwendet wird (Passwort `1234567890`). Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx), um es herunterzuladen.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg), um sie herunterzuladen.

{{< /tab >}}
{{< tab "signed_digital_advanced.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

Sie können das Zertifikat auch aus einem Stream laden. Halten Sie den Stream offen, bis `sign` zurückgibt:

{{< tabs "sign_with_certificate_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Laden Sie das Zertifikat aus einem Stream
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Setze Signaturposition und -größe
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf), um sie herunterzuladen.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` ist das Beispielzertifikat, das in diesem Beispiel verwendet wird (Passwort `1234567890`). Klicken Sie [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx), um es herunterzuladen.

{{< /tab >}}
{{< tab "signed_digital_stream.pdf" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Dieses Handbuch zeigt, wie man [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) verwendet, um Dokumente mit digitalen Signaturen zu signieren. Es erklärt, wie man Dokumente lädt, zertifikatsbasierte Signaturen konfiguriert und signierte Dateien sicher speichert. Fortgeschrittene Funktionen, wie das Aussehen der Signatur und die in der Signatur gespeicherten Informationen, werden ebenfalls behandelt. Weitere Informationen finden Sie in den zugehörigen Ressourcen für zusätzliche Details zu digitalen Signaturabläufen.

## More Resources

### GitHub Examples

Sie können den obigen Code ganz einfach ausführen und die Funktion in Aktion in unseren GitHub‑Beispielen sehen:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Zusammen mit der voll ausgestatteten Python‑Bibliothek bieten wir einfache, aber leistungsstarke kostenlose Online‑Apps an.

Um PDF-, Word-, Excel-, PowerPoint- und andere Dokumente zu signieren, können Sie die Online‑Apps der **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** verwenden.
