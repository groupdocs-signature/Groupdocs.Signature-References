---
title: "Document ondertekenen met digitale handtekening"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Leer over de voordelen van het gebruik van digitale handtekeningen om documenten veilig te ondertekenen. Ontdek hoe u programmatisch digitale handtekeningen in Python kunt toevoegen met stapsgewijze instructies."
type: docs
url: /nl/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

In het digitale tijdperk van vandaag is het waarborgen van de authenticiteit en integriteit van elektronische documenten cruciaal. Een zeer effectieve methode om dit te bereiken is het gebruik van digitale handtekeningen. In deze gids verkennen we de wereld van digitale handtekeningen, leggen we uit wat ze zijn, waarom ze essentieel zijn, en hoe u GroupDocs.Signature for Python via .NET kunt gebruiken om uw documenten naadloos elektronisch te ondertekenen.

## What is a Digital Signature?

Een digitale handtekening is een cryptografisch mechanisme om de authenticiteit en integriteit van elektronische documenten te verifiëren. Het biedt sterke zekerheid dat het document afkomstig is van een bekende afzender en niet is gemanipuleerd door onbevoegde bronnen. Digitale handtekeningen worden doorgaans weergegeven door certificaten die een privésleutel (voor ondertekenen) en een openbare sleutel (voor verificatie) bevatten. Diverse standaarden voor asymmetrische cryptografie, zoals het PFX-formaat, worden vaak voor dit doel gebruikt.
De afbeelding hieronder toont hoe een digitale handtekening er standaard uitziet op een PDF‑documentpagina.

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

Verlopen en nog niet geldige certificaten worden afgewezen: `sign` veroorzaakt een [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) met een bericht zoals "Het ondertekeningscertificaat is verlopen op ...". Om toch met zo'n certificaat te ondertekenen, stelt u `allow_expired` of `allow_not_yet_valid` in op `True`.

### Follow these steps to sign your documents with a digital signature

1. Installeer het GroupDocs.Signature‑pakket met pip:
```bash
pip install groupdocs-signature-net
```

2. Maak een nieuw exemplaar van de [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature)‑klasse en geef het pad naar het brondocument door als constructor‑parameter.
3. Instantieer het [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/)‑object met het vereiste certificaat en het bijbehorende wachtwoord.
4. Roep de [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/)‑methode aan van het [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature)‑klasse‑exemplaar en geef de [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) door.

Het onderstaande voorbeeld toont hoe u een PDF‑document kunt ondertekenen met een digitale e‑handtekening met Python. We kunnen elk ander ondersteund documentformaat op dezelfde manier ondertekenen.

{{< tabs \"sign_with_digital_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Maak digitale handtekeningopties aan met het certificaatbestand
        options = DigitalSignOptions("certificate.pfx")

        # Stel het certificaatwachtwoord in
        options.password = "1234567890"

        # Optioneel: een afbeelding die de handtekening op de pagina toont
        options.image_file_path = "signature.jpg"

        # Stel de handtekeningpositie in
        options.left = 100
        options.top = 400

        # Onderteken het document en sla het resultaat op
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` is het voorbeeldcertificaat dat in dit voorbeeld wordt gebruikt (wachtwoord `1234567890`). Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) om het te downloaden.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) om het te downloaden.

{{< /tab >}}
{{< tab "signed_digital.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

U kunt de digitale handtekening verder aanpassen met extra opties: de grootte van de handtekening op de pagina, en de contactgegevens, reden en locatie die erin zijn opgeslagen:

{{< tabs "sign_with_digital_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Geef het certificaat en de weergave‑afbeelding door aan de constructor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Toon de ondertekening op de pagina, op deze positie en grootte
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Informatie opgeslagen in de handtekening
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` is het voorbeeldcertificaat dat in dit voorbeeld wordt gebruikt (wachtwoord `1234567890`). Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) om het te downloaden.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) om het te downloaden.

{{< /tab >}}
{{< tab "signed_digital_advanced.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

U kunt het certificaat ook laden vanuit een stream. Houd de stream open totdat `sign` terugkeert:

{{< tabs "sign_with_certificate_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Laad het certificaat vanuit een stream
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Stel handtekeningpositie en -grootte in
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

`sample.pdf` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) om het te downloaden.

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` is het voorbeeldcertificaat dat in dit voorbeeld wordt gebruikt (wachtwoord `1234567890`). Klik [hier](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) om het te downloaden.

{{< /tab >}}
{{< tab "signed_digital_stream.pdf" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Deze gids toont hoe u [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) kunt gebruiken om documenten te ondertekenen met digitale handtekeningen. Het legt uit hoe u documenten laadt, certificaatgebaseerde handtekeningen configureert en ondertekende bestanden veilig opslaat. Geavanceerde functies, zoals het uiterlijk van de handtekening en de informatie die in de handtekening is opgeslagen, worden ook behandeld. Raadpleeg gerelateerde bronnen voor extra details over digitale ondertekeningsworkflows.

## More Resources

### GitHub Examples

U kunt de bovenstaande code eenvoudig uitvoeren en de functie in actie zien in onze GitHub-voorbeelden:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Naast de volledig uitgeruste Python-bibliotheek bieden we eenvoudige maar krachtige gratis online apps.

Om PDF, Word, Excel, PowerPoint en andere documenten te ondertekenen, kun je de online apps van de **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** gebruiken.
