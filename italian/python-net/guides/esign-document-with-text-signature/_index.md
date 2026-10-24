---
title: "Documento eSign con firma di testo"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Questo articolo spiega come firmare un documento con firma di Testo usando GroupDocs.Signature for Python via .NET API. Scopri come aggiungere una firma digitale a un PDF programmaticamente in Python."
type: docs
url: /it/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

Una firma elettronica **Text** è un testo arbitrario che viene aggiunto a un documento in modo nativo a seconda del tipo di documento. GroupDocs.Signature fornisce la funzionalità di firma di testo e consente di personalizzare un'ampia gamma di impostazioni del testo - dal nome del carattere, dimensione e colore all'allineamento, bordi, effetti ombra ecc. Ecco come può apparire una firma di testo:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Proviamo ad aggiungere una firma di testo a un PDF programmaticamente usando Python.

Per manipolare le firme di testo programmaticamente [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) fornisce la classe [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) e l'intero flusso di lavoro è così semplice:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Questo esempio mostra come aggiungere una firma di testo a un documento usando Python:

{{< tabs "sign_with_text_signature" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Crea le opzioni per la firma di testo
        options = TextSignOptions("John Smith")

        # Imposta la posizione e le dimensioni della firma
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Imposta il colore e il carattere del testo
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Firma il documento e salva il risultato
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Puoi personalizzare ulteriormente la firma di testo con opzioni aggiuntive: allineamento e margini, stile del carattere, sfondo, bordo, rotazione e trasparenza. Quando è impostato un allineamento, sostituisce la coordinata `left` o `top`, e il `margin` sposta la firma dal bordo della pagina.

{{< tabs "sign_with_text_signature_advanced" >}}
{{< tab \"Python\" >}}
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

        # Posiziona la firma nell'angolo in basso a destra della pagina
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Stile del carattere e colore del testo
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Sfondo, bordo, rotazione e trasparenza
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

        # Renderizza il testo come immagine, che disegna anche il bordo sulle pagine PDF
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_text_advanced.pdf\" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Questa guida spiega come aggiungere firme basate su testo ai documenti con [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Copre la configurazione delle proprietà del testo come carattere, colore, dimensione e posizione, e l'applicazione della firma testuale a un documento. Il documento firmato viene quindi salvato con la firma testuale aggiunta.

## More Resources

### GitHub Examples

Puoi facilmente eseguire il codice sopra e vedere la funzionalità in azione nei nostri esempi su GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Oltre alla libreria Python completa, forniamo semplici ma potenti app online gratuite.

Per firmare PDF, Word, Excel, PowerPoint e altri documenti puoi utilizzare le app online della **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
