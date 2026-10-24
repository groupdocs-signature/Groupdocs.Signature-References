---
title: "Documento eSign con firma immagine"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Questo articolo dimostra come aggiungere un'immagine di firma su una pagina del documento con GroupDocs.Signature per Python tramite .NET."
type: docs
url: /it/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

Un **immagine** come firma è un modo alternativo per inserire qualsiasi dato presentato in forma visiva. Questo tipo di firma elettronica consente la creazione di immagini personalizzate con il logo aziendale, le iniziali del mittente, i nomi e così via.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Ecco i passaggi per creare una firma immagine su una pagina del documento:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Questo esempio mostra come firmare un documento PDF con la firma immagine utilizzando Python:

{{< tabs \"sign_with_image_signature\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Crea opzioni di firma immagine con il file immagine
        options = ImageSignOptions("signature.jpg")

        # Imposta la posizione e le dimensioni della firma
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # Firma il documento e salva il risultato
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

Puoi personalizzare ulteriormente la firma immagine con opzioni aggiuntive: allineamento e margini, rotazione, trasparenza e un bordo. Quando viene impostato un allineamento, sostituisce la coordinata `left` o `top`, e il `margin` sposta la firma dal bordo della pagina.

{{< tabs \"sign_with_image_signature_advanced\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # Posiziona la firma nell'angolo in basso a destra della pagina
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Ruota l'immagine e rendila trasparente al 20%
        options.rotation_angle = 10
        options.transparency = 0.2

        # Disegna un bordo tratteggiato attorno all'immagine
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) per scaricarlo.

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

Puoi anche caricare l'immagine della firma da uno stream. Mantieni lo stream aperto fino a quando `sign` restituisce:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # Carica l'immagine della firma da un flusso
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
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) per scaricarlo.

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Questa guida dimostra come utilizzare [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) per aggiungere firme basate su immagine ai documenti. Copre il caricamento di un documento, la configurazione delle proprietà della firma immagine (come dimensione, posizione e trasparenza) e il salvataggio del documento firmato. Vengono inoltre discusse opzioni di personalizzazione avanzate, come la regolazione dell'aspetto dell'immagine e l'allineamento della firma. Per ulteriori approfondimenti, esplora le risorse correlate alla firma dei documenti.

## More Resources

### GitHub Examples

Puoi facilmente eseguire il codice sopra e vedere la funzionalità in azione nei nostri esempi su GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Oltre alla libreria Python completa, forniamo semplici ma potenti app online gratuite.

Per generare firme immagine e/o firmare i tuoi file con esse gratuitamente, puoi utilizzare l'app online [Generate Image](https://products.groupdocs.app/signature/generate/image).

Per firmare PDF, Word, Excel, PowerPoint e altri documenti puoi utilizzare le altre app online della **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
