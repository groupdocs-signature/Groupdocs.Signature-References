---
title: "Generar vista previa de páginas del documento"
linkTitle: "Generate document pages preview"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Este tema explica cómo obtener una vista previa de las páginas del documento como imágenes con varias opciones mediante GroupDocs.Signature para Python vía .NET."
type: docs
url: /es/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
Estos son los pasos para generar la vista previa del documento con GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

El flujo devuelto por la función create se cierra automáticamente tan pronto como se escribe la imagen de la página: se cierra un archivo y un `io.BytesIO` ya contiene la imagen completa. Si necesita procesar cada imagen terminada o liberar recursos usted mismo, pase una función de liberación como argumento adicional (ver [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature llama a la función create una vez por cada página y escribe la imagen de la página en el flujo que devuelve: un objeto de archivo escribible, un `io.BytesIO` o un flujo .NET. El argumento `page_data` es un objeto [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) con el `page_number`, el `file_name` del documento y el `preview_format`.

Los números de página comienzan en 0: `page_data.page_number` es `0` para la primera página del documento.

```python
def create_page_stream(page_data):
    # Basado en 0: preview_page_0.png es la primera página
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

Al previsualizar un archivo, la función se llama para las páginas de cada documento que contiene. Los números de página vuelven a comenzar en `0` para cada documento, por lo que también debe usar `page_data.file_name` al nombrar las imágenes.

## ReleasePageStream delegate implementation

La función de liberación recibe el mismo `page_data` y el mismo objeto que devolvió la función create. Cuando se llama, la imagen está completa.

```python
def release_page_stream(page_data, page_stream):
    # page_stream es el objeto devuelto por create_page_stream
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs "generate_document_preview" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Los números de página son base 0: preview_page_0.png es la primera página
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # Crear objeto de opciones de vista previa: una imagen PNG por página
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # Generar vista previa
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) para descargarlo.

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

Este ejemplo lee el documento desde un flujo y mantiene las imágenes de página en memoria: la función create devuelve un `io.BytesIO`, y la función release lo recibe lleno con la imagen completa.

{{< tabs "generate_document_preview_from_stream" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Mantenga cada imagen de página en memoria en lugar de escribir un archivo
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream es el BytesIO devuelto arriba, que ya contiene la imagen completa
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # Crear objeto de opciones de vista previa con ambas funciones
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # Generar vista previa
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) para descargarlo.

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

Establezca `page_numbers` para previsualizar solo algunas páginas. Los números son base 0, por lo que `[1]` selecciona la segunda página.

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
        # Los números de página son base 0: [1] es la segunda página
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) para descargarlo.

{{< /tab >}}
{{< tab "preview_page_1.png" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

La resolución predeterminada es 96 DPI. Pase la resolución como tercer argumento de [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/), o establezca la propiedad `resolution`.

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
        # Crear objeto de opciones de vista previa: 150 DPI en lugar de los 96 predeterminados
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # Generar vista previa
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) para descargarlo.

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

Puede ejecutar fácilmente el código anterior y ver la función en acción en nuestros ejemplos de GitHub:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Junto con la biblioteca Python completa, ofrecemos aplicaciones en línea gratuitas, simples pero potentes.

Para firmar PDF, Word, Excel, PowerPoint y otros documentos, puedes usar las aplicaciones en línea de la **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
