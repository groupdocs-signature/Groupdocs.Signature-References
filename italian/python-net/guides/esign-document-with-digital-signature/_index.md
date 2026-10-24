---
title: "Firma documento con firma digitale"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Scopri i vantaggi dell'utilizzo delle firme digitali per firmare i documenti in modo sicuro. Scopri come aggiungere firme digitali in Python in modo programmatico con istruzioni passo passo."
type: docs
url: /it/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

Nell'era digitale odierna, garantire l'autenticità e l'integrità dei documenti elettronici è fondamentale. Un metodo altamente efficace per raggiungere questo obiettivo è l'uso delle firme digitali. In questa guida, esploreremo il mondo delle firme digitali, spiegando cosa sono, perché sono essenziali e come puoi utilizzare GroupDocs.Signature for Python via .NET per firmare elettronicamente i tuoi documenti senza interruzioni.

## What is a Digital Signature?

Una firma digitale è un meccanismo crittografico per verificare l'autenticità e l'integrità dei documenti elettronici. Fornisce una forte garanzia che il documento provenga da un mittente noto e non sia stato manomesso da fonti non autorizzate. Le firme digitali sono tipicamente rappresentate da certificati contenenti chiavi private (per la firma) e chiavi pubbliche (per la verifica). Vari standard di crittografia a chiave pubblica, come il formato PFX, sono comunemente utilizzati a questo scopo.
L'immagine qui sotto mostra come appare una firma digitale su una pagina di documento PDF per impostazione predefinita.

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

I certificati scaduti e non ancora validi vengono rifiutati: `sign` genera [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) con un messaggio come "Il certificato di firma è scaduto il ...". Per firmare comunque con un certificato di questo tipo, imposta `allow_expired` o `allow_not_yet_valid` su `True`.

### Follow these steps to sign your documents with a digital signature

1. Installa il pacchetto GroupDocs.Signature usando pip:
```bash
pip install groupdocs-signature-net
```

2. Crea una nuova istanza della classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) e passa il percorso del documento sorgente come parametro del costruttore.
3. Istanzia l'oggetto [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) con il certificato richiesto e la sua password.
4. Chiama il metodo [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) dell'istanza della classe [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) e passa il [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) come argomento.

L'esempio qui sotto mostra come firmare un documento PDF con una firma elettronica digitale usando Python. Possiamo firmare qualsiasi altro formato di documento supportato allo stesso modo.

{{< tabs "sign_with_digital_signature" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Crea le opzioni di firma digitale con il file del certificato
        options = DigitalSignOptions("certificate.pfx")

        # Imposta la password del certificato
        options.password = "1234567890"

        # Opzionale: un'immagine che mostra la firma sulla pagina
        options.image_file_path = "signature.jpg"

        # Imposta la posizione della firma
        options.left = 100
        options.top = 400

        # Firma il documento e salva il risultato
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` è il certificato di esempio utilizzato in questo esempio (password `1234567890`). Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) per scaricarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Puoi personalizzare ulteriormente la firma digitale con opzioni aggiuntive: la dimensione della firma sulla pagina, e il contatto, il motivo e la posizione memorizzati in essa:

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Passa il certificato e l'immagine di aspetto al costruttore
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Mostra la firma sulla pagina, in questa posizione e dimensione
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Informazioni memorizzate nella firma
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

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` è il certificato di esempio utilizzato in questo esempio (password `1234567890`). Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) per scaricarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

Puoi anche caricare il certificato da uno stream. Mantieni lo stream aperto fino a quando `sign` restituisce:

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Carica il certificato da uno stream
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Imposta la posizione e le dimensioni della firma
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

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` è il certificato di esempio utilizzato in questo esempio (password `1234567890`). Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Questa guida dimostra come utilizzare [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) per firmare documenti con firme digitali. Spiega come caricare i documenti, configurare firme basate su certificato e salvare i file firmati in modo sicuro. Sono trattate anche funzionalità avanzate, come l'aspetto della firma e le informazioni memorizzate nella firma. Consulta le risorse correlate per ulteriori dettagli sui flussi di lavoro di firma digitale.

## More Resources

### GitHub Examples

Puoi facilmente eseguire il codice sopra e vedere la funzionalità in azione nei nostri esempi su GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Oltre alla libreria Python completa, forniamo semplici ma potenti app online gratuite.

Per firmare PDF, Word, Excel, PowerPoint e altri documenti puoi utilizzare le app online della **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
