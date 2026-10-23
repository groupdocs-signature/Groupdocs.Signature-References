---
title: "Générer un aperçu des pages du document"
linkTitle: "Generate document pages preview"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Ce sujet explique comment obtenir un aperçu des pages du document sous forme d'images avec diverses options grâce à GroupDocs.Signature pour Python via .NET."
type: docs
url: /fr/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
Voici les étapes pour générer un aperçu du document avec GroupDocs.Signature :

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

Le flux renvoyé par la fonction create est fermé automatiquement dès que l'image de la page est écrite : un fichier est fermé, et un `io.BytesIO` contient déjà l'image complète. Si vous devez traiter chaque image terminée ou nettoyer les ressources vous-même, passez une fonction de libération en tant qu'argument supplémentaire (voir [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature appelle la fonction create une fois pour chaque page et écrit l'image de la page dans le flux qu'elle renvoie : un objet fichier ouvrable, un `io.BytesIO`, ou un flux .NET. L'argument `page_data` est un objet [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) contenant le `page_number`, le `file_name` du document et le `preview_format`.

Les numéros de page commencent à 0 : `page_data.page_number` vaut `0` pour la première page du document.

```python
def create_page_stream(page_data):
    # Commence à 0 : preview_page_0.png est la première page
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

Lorsque vous prévisualisez une archive, la fonction est appelée pour les pages de chaque document qu'elle contient. Les numéros de page recommencent à `0` pour chaque document, utilisez donc également `page_data.file_name` lors du nommage des images.

## ReleasePageStream delegate implementation

La fonction de libération reçoit le même `page_data` et le même objet renvoyé par la fonction create. Au moment où elle est appelée, l'image est complète.

```python
def release_page_stream(page_data, page_stream):
    # page_stream est l'objet renvoyé par create_page_stream
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs "generate_document_preview" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Les numéros de page commencent à 0 : preview_page_0.png est la première page
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # Créez l’objet d’options d’aperçu : une image PNG par page
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # Générer l’aperçu
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d’exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "generate-document-preview-outputs.zip" >}}
```text
preview_page_0.png (75 KB)
preview_page_1.png (64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview/generate-document-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Generate document preview from stream with custom stream releasing delegate

Cet exemple lit le document depuis un flux et conserve les images de page en mémoire : la fonction create renvoie un `io.BytesIO`, et la fonction release le reçoit rempli de l’image complète.

{{< tabs "generate_document_preview_from_stream" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Conservez chaque image de page en mémoire au lieu d’écrire un fichier
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream est le BytesIO renvoyé ci‑dessus, contenant déjà l’image complète
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # Créez l’objet d’options d’aperçu avec les deux fonctions
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # Générer l’aperçu
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d’exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "generate-document-preview-from-stream.txt" >}}
```text
Page 0: 276044 bytes of JPEG
Page 1: 224194 bytes of JPEG
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_from_stream/generate-document-preview-from-stream.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate preview of particular pages

Définissez `page_numbers` pour prévisualiser seulement certaines pages. Les numéros commencent à 0, donc `[1]` sélectionne la deuxième page.

{{< tabs "generate_document_preview_of_selected_pages" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}.png", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_of_selected_pages():
    with Signature("sample.pdf") as signature:
        preview_options = PreviewOptions(create_page_stream, release_page_stream)
        # Les numéros de page commencent à 0 : [1] est la deuxième page
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d’exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "preview_page_1.png" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

La résolution par défaut est de 96 DPI. Transmettez la résolution comme troisième argument de [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/), ou définissez la propriété `resolution`.

{{< tabs "generate_document_preview_with_resolution" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}_150dpi.jpg", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_with_resolution():
    with Signature("sample.pdf") as signature:
        resolution = 150
        # Créez l’objet d’options d’aperçu : 150 DPI au lieu des 96 par défaut
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # Générer l’aperçu
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` est le fichier d’exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) pour le télécharger.

{{< /tab >}}
{{< tab "generate-document-preview-with-resolution-outputs.zip" >}}
```text
preview_page_0_150dpi.jpg (495 KB)
preview_page_1_150dpi.jpg (425 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_with_resolution/generate-document-preview-with-resolution-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

Vous pouvez facilement exécuter le code ci‑dessus et voir la fonctionnalité en action dans nos exemples GitHub :

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

En plus de la bibliothèque Python complète, nous proposons des applications en ligne simples mais puissantes et gratuites.

Pour signer des PDF, Word, Excel, PowerPoint et d'autres documents, vous pouvez utiliser les applications en ligne de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
