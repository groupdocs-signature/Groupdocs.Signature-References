---
title: "Documento eSign con firma QR Code"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Questo articolo spiega come firmare i documenti con firma elettronica come QR code sulla pagina del documento con GroupDocs.Signature per Python tramite API .NET."
type: docs
url: /it/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

Il QR code (o Quick Response code) è una sorta di [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) bidimensionale che consiste in quadrati neri disposti in una griglia quadrata su sfondo bianco. I QR code possono essere letti dalle fotocamere degli smartphone o da dispositivi specializzati dedicati alla lettura dei QR – scanner portatili, terminali tascabili, scanner da desktop, scanner integrati e così via. Di solito i QR code contengono dati che puntano a un sito web o a un'applicazione, email o numeri di telefono, identificatori di prodotto o tracker. Pertanto, l'ambito delle applicazioni dei QR code si estende dal marketing generale e dall'identificazione degli articoli alla gestione dei documenti.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Codice Aztec | Codice DataMatrix | GS1 DataMatrix | GS1 QR code | QR |
| --- | --- | --- | --- | --- | --- |
| **Applicazione** | * trasporto e biglietteria;<br> * nell'industria aerea per carte d'imbarco elettroniche;<br> * nel settore ferroviario per biglietti venduti online e stampati dai clienti o visualizzati su schermi di telefoni cellulari. Il codice è scansionato da uno scanner portatile dal personale a bordo del treno o al tornello per convalidare il biglietto.<br> * medicina - braccialetti di identificazione del paziente e etichette per farmaci monodose, ecc. | * media stampati come etichette e lettere;<br> * scopi di ingegneria industriale - marcatura di componenti ecc;<br>  * industria alimentare - per evitare che i prodotti alimentari vengano confezionati e datati in modo errato; | Utilizzato in<br> * Sanità;<br> * Governo;<br> * Industria.<br> Codifica informazioni aggiuntive sull'oggetto, come:<br> * peso;<br> * data di scadenza;<br> * numero di lotto;<br> * data di produzione;<br> * ecc. | Utilizzato nel marketing per codificare informazioni aggiuntive sull'oggetto sulla confezione | Ampiamente utilizzato nell'industria automobilistica e nelle applicazioni mobili. Utile per codificare una grande quantità di caratteri dati e URL specifici. |
| **Lunghezza** | 3067 alfanumerico,<br> 3832 numerico,<br> 1914 byte | 2335 alfanumerico,<br> 3116 numerico | 2335 alfanumerico,<br> 3116 numerico,<br> 1556 byte | 7089 alfanumerico,<br> 4296 numerico,<br> 2953 byte | 4296 alfanumerico,<br> 7089 numerico,<br> 2953 byte |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

Quando si aggiunge la firma elettronica QR code a un documento, le impostazioni principali sono il testo da codificare e il [tipo di QR code](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) che deve essere specificato tramite la classe [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions).

Ecco i passaggi per firmare elettronicamente un documento con la firma QR code:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

Il frammento di codice seguente dimostra come firmare un documento PDF con la firma QR code utilizzando Python:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Crea le opzioni di firma QR code con il testo da codificare
        options = QrCodeSignOptions("John Smith")

        # Imposta il tipo di QR code
        options.encode_type = QrCodeTypes.QR

        # Imposta la posizione e le dimensioni del QR code
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Firma il documento e salva il risultato
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio utilizzato in questo caso. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

Gli altri tipi di QR code dalla tabella sopra sono impostati allo stesso modo, ad esempio `QrCodeTypes.AZTEC` o `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Ecco un esempio che mostra come creare una firma QR code più complessa con personalizzazioni aggiuntive: allineamento e margini, colore del modulo, sfondo e bordo:

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
        # Passa il testo e il tipo di QR code al costruttore
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Posiziona il QR code nell'angolo inferiore destro della pagina
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Colore del modulo, sfondo e un bordo puntinato con un po' di spazio interno
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

`sample.pdf` è il file di esempio utilizzato in questo caso. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Questa guida dimostra come aggiungere firme QR code ai documenti utilizzando [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Include i passaggi per generare una firma QR code, configurare le sue proprietà come dimensione e codifica, e applicarla a un documento. Le firme QR code possono essere usate per una rapida verifica del documento firmato.

## More Resources

### GitHub Examples

Puoi facilmente eseguire il codice sopra e vedere la funzionalità in azione nei nostri esempi su GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Oltre alla libreria Python completa, forniamo semplici ma potenti app online gratuite.

Per generare QR code e/o firmare i tuoi file con QR code gratuitamente, puoi utilizzare l'app online [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode).

Per firmare PDF, Word, Excel, PowerPoint e altri documenti puoi utilizzare le altre app online della **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
