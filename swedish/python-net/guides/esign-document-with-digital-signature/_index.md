---
title: "Signera dokument med digital signatur"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Lär dig om fördelarna med att använda digitala signaturer för att säkert signera dokument. Upptäck hur du programatiskt lägger till digitala signaturer i Python med steg‑för‑steg‑instruktioner."
type: docs
url: /sv/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

I dagens digitala era är det avgörande att säkerställa äktheten och integriteten hos elektroniska dokument. En mycket effektiv metod för att uppnå detta är genom användning av digitala signaturer. I den här guiden kommer vi att utforska världen av digitala signaturer, förklara vad de är, varför de är viktiga och hur du kan använda GroupDocs.Signature for Python via .NET för att sömlöst e‑signera dina dokument.

## What is a Digital Signature?

En digital signatur är en kryptografisk mekanism för att verifiera äktheten och integriteten hos elektroniska dokument. Den ger starkt bevis på att dokumentet kommer från en känd avsändare och inte har manipulerats av obehöriga. Digitala signaturer representeras vanligtvis av certifikat som innehåller privata (för signering) och offentliga (för verifiering) nycklar. Olika standarder för offentlig nyckelkryptografi, såsom PFX‑formatet, används ofta för detta ändamål.
Bilden nedan visar hur en digital signatur ser ut på en PDF‑dokumentssida som standard.

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

Utgångna och ännu inte giltiga certifikat avvisas: `sign` kastar [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) med ett meddelande som exempelvis "The signing certificate expired on ...". För att ändå signera med ett sådant certifikat, sätt `allow_expired` eller `allow_not_yet_valid` till `True`.

### Follow these steps to sign your documents with a digital signature

1. Installera GroupDocs.Signature‑paketet med pip:
```bash
pip install groupdocs-signature-net
```

2. Skapa en ny instans av klassen [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) och skicka källdokumentets sökväg som en konstruktörsparameter.
3. Instansiera objektet [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) med det erforderliga certifikatet och dess lösenord.
4. Anropa [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) metoden på [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) klassinstansen och skicka [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) till den.

Exemplet nedan visar hur man signerar ett PDF-dokument med en digital e-signatur med Python. Vi kan signera alla andra stödda dokumentformat på samma sätt.

{{< tabs \"sign_with_digital_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Skapa alternativ för digital signatur med certifikatfilen
        options = DigitalSignOptions("certificate.pfx")

        # Ange certifikatets lösenord
        options.password = "1234567890"

        # Valfritt: en bild som visar signaturen på sidan
        options.image_file_path = "signature.jpg"

        # Ange signaturens position
        options.left = 100
        options.top = 400

        # Signera dokumentet och spara resultatet
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` är exempelcertifikatet som används i detta exempel (lösenord `1234567890`). Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) för att ladda ner det.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) för att ladda ner den.

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Du kan anpassa den digitala signaturen ytterligare med ytterligare alternativ: signaturens storlek på sidan samt kontakt, anledning och plats som lagras i den:

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Skicka certifikatet och bild för utseende till konstruktorn
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Visa signaturen på sidan, på denna position och storlek
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Information lagrad i signaturen
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` är exempelcertifikatet som används i detta exempel (lösenord `1234567890`). Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) för att ladda ner det.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) för att ladda ner den.

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

Du kan också läsa in certifikatet från en ström. Håll strömmen öppen tills `sign` returnerar:

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Läs in certifikatet från en ström
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Ange signaturens position och storlek
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` är exempelcertifikatet som används i detta exempel (lösenord `1234567890`). Klicka på [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) för att ladda ner det.

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Denna guide visar hur man använder [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) för att signera dokument med digitala signaturer. Den förklarar hur man läser in dokument, konfigurerar certifikatbaserade signaturer och sparar signerade filer på ett säkert sätt. Avancerade funktioner, såsom signaturens utseende och informationen som lagras i signaturen, behandlas också. Se relaterade resurser för ytterligare detaljer om arbetsflöden för digital signering.

## More Resources

### GitHub Examples

Du kan enkelt köra koden ovan och se funktionen i praktiken i våra GitHub-exempel:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tillsammans med det fullständiga Python-biblioteket erbjuder vi enkla men kraftfulla gratis online‑appar.

För att signera PDF, Word, Excel, PowerPoint och andra dokument kan du använda de online‑apparna från **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
