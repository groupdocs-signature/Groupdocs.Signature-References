---
title: "Firma elettronica del documento con firma Barcode"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Questo articolo spiega come aggiungere una firma Barcode su una pagina del documento con varie opzioni come tipo di barcode, testo del barcode, posizionamento, allineamento e altre impostazioni visive con GroupDocs.Signature per Python via .NET"
type: docs
url: /it/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

Un **barcode** o **bar code** è un modo di presentare i dati in forma visiva, leggibile da macchine. In generale, il barcode è un'immagine di forma rettangolare composta da linee nere parallele e spazi bianchi di larghezze diverse.
I barcode sono utilizzati in vari ambiti dove è necessaria un'identificazione rapida - come parte del processo di acquisto nei negozi al dettaglio, nei magazzini per tracciare l'inventario e sulle fatture per assistere la contabilità, tra i molti altri usi.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

I barcode consentono di memorizzare dati relativi al prodotto come data di produzione e scadenza, nome del produttore, paese di origine e prezzo del prodotto. Oggi esistono numerosi tipi di barcode perché diverse aziende utilizzano combinazioni diverse di numeri e barre nei loro barcode a seconda delle esigenze. Dal punto di vista della firma dei documenti, il Barcode può contenere diversi caratteri (lettere, cifre o simboli) e può avere varie lunghezze e dimensioni a seconda del tipo e delle impostazioni per conservare informazioni della firma, titolo, oggetto o dati crittografati brevi.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Per specificare diverse opzioni per la firma Barcode, GroupDocs.Signature per Python via .NET fornisce la classe [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). I principali campi sono:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

Ecco i passaggi per firmare elettronicamente un documento con la firma Barcode utilizzando l'API GroupDocs.Signature per Python via .NET:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Questo esempio mostra come firmare un documento PDF con una firma Barcode utilizzando Python:

{{< tabs \"sign_with_barcode_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Crea le opzioni della firma barcode con il testo da codificare
        options = BarcodeSignOptions("John Smith")

        # Imposta il tipo di barcode
        options.encode_type = BarcodeTypes.CODE128

        # Imposta la posizione e le dimensioni del barcode
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Firma il documento e salva il risultato
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_barcode.pdf\" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Puoi personalizzare ulteriormente la firma barcode con opzioni aggiuntive: allineamento e margini, colore della barra, posizione del testo codificato, margini interni, sfondo, bordo e trasparenza:

{{< tabs \"sign_with_barcode_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Passa il testo e il tipo di barcode al costruttore
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Posiziona il barcode nell'angolo in basso a destra della pagina
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Colore della barra, testo codificato sotto le barre, spazio all'interno del bordo
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Sfondo, bordo e trasparenza
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_barcode_advanced.pdf\" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature supporta vari tipi di barcode. Ogni tipo accetta il proprio set di caratteri e lunghezze, quindi scegli il testo in base al tipo. Questo esempio firma un documento con quattro barcode di tipi diversi in una singola chiamata:

{{< tabs \"sign_with_different_barcode_types\" >}}
{{< tab \"Python\" >}}
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

    # Un oggetto di opzioni di firma per barcode, posizionato uno sotto l'altro
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_barcode_types.pdf\" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Questa guida dimostra come utilizzare [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) per aggiungere firme basate su codici a barre ai documenti. Copre la creazione, la configurazione e l'applicazione di firme a codici a barre con supporto per vari tipi di codici a barre e opzioni di personalizzazione. Per ulteriori approfondimenti, consultare le guide correlate su informazioni sui documenti e tecniche di firma avanzate.

## More Resources

### GitHub Examples

Puoi facilmente eseguire il codice sopra e vedere la funzionalità in azione nei nostri esempi su GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Oltre alla libreria Python completa, forniamo semplici ma potenti app online gratuite.

Per generare codici a barre e/o firmare i tuoi file con codici a barre gratuitamente, puoi utilizzare l'app online [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode).

Per firmare PDF, Word, Excel, PowerPoint e altri documenti puoi utilizzare le altre app online della **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
