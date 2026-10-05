---
title: Generate signatures preview
linkTitle: "Generate signatures preview"
second_title: GroupDocs.Signature for Python via .NET API References
description: "This topic explains how to generate document signature preview in Python with various options by GroupDocs.Signature for Python via .NET."
type: docs
url: /python-net/guides/generate-signatures-preview/
is_root: false
weight: 120
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/net/groupdocs.signature.options/previewoptions) class to specify different options to manage signature preview generation process.

Here are the steps to generate signature preview with GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/net/groupdocs.signature/signature) class and pass source document path as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/net/groupdocs.signature.options/previewoptions) object with:
* delegate for each signature stream creation (see event handler [CreatePageStream](https://reference.groupdocs.com/signature/net/groupdocs.signature.options/createpagestream));
* image preview format - PNG / JPG / BMP,
* signature numbers to process;
* custom size of preview images (if needed).

Stream that were created by CreatePageStreamdelegate will be disposed automatically once after generation of preview image. If you need to implement custom image preview stream disposing you have to pass additional argument ReleaseStream to clean up resources.  

* Call GeneratePreview method of [Signature](https://reference.groupdocs.com/signature/net/groupdocs.signature/signature) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/net/groupdocs.signature.options/previewoptions) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature expects CreatePageStreamdelegate to obtain each signature stream for image preview generation process

```python
def create_page_stream(page_data):
    image_name = f"signature-{page_data.page_number}.jpg"
    image_file_path = os.path.join("GeneratePreviewFolder", image_name)
    folder = os.path.dirname(image_file_path)
    if not os.path.exists(folder):
        os.makedirs(folder)
    return open(image_file_path, "wb")
```

## ReleasePageStream delegate implementation

```python
def release_page_stream(page_data, page_stream):
    page_stream.close()
    image_name = f"signature-{page_data.page_number}.jpg"
    image_file_path = os.path.join("GeneratePreviewFolder", image_name)
    print(f"Image file {image_file_path} is ready for preview")
```

## Generate signature preview from file on local disk

```python
import os
import groupdocs.signature as signature

def get_preview():
    with signature.Signature("sample.pdf") as sign:
        # create preview options object
        preview_option = signature.PreviewOptions(create_page_stream)
        preview_option.preview_format = signature.PreviewOptions.PreviewFormats.JPEG
        # generate preview
        sign.generate_preview(preview_option)

def create_page_stream(page_data):
    image_name = f"signature-{page_data.page_number}.jpg"
    image_file_path = os.path.join("GeneratePreviewFolder", image_name)
    folder = os.path.dirname(image_file_path)
    if not os.path.exists(folder):
        os.makedirs(folder)
    return open(image_file_path, "wb")
```

## Generate signature preview from stream with custom stream releasing delegate

```python
import os
import groupdocs.signature as signature

def get_preview():
    with open("sample.pdf", "rb") as stream:
        with signature.Signature(stream) as sign:
            # create preview options object
            preview_option = signature.PreviewOptions(create_page_stream, release_page_stream)
            preview_option.preview_format = signature.PreviewOptions.PreviewFormats.JPEG
            # generate preview
            sign.generate_preview(preview_option)

def create_page_stream(page_data):
    image_name = f"signature-{page_data.page_number}.jpg"
    image_file_path = os.path.join("GeneratePreviewFolder", image_name)
    folder = os.path.dirname(image_file_path)
    if not os.path.exists(folder):
        os.makedirs(folder)
    return open(image_file_path, "wb")

def release_page_stream(page_data, page_stream):
    page_stream.close()
    image_name = f"signature-{page_data.page_number}.jpg"
    image_file_path = os.path.join("GeneratePreviewFolder", image_name)
    print(f"Image file {image_file_path} is ready for preview")
```

## Creating a signature preview with custom Resolution

```python
import os
import groupdocs.signature as signature

# The path to the documents
file_path = "sample.pdf"
with signature.Signature(file_path) as sign:
    resolution = 96
    # create preview options object
    # You can reuse create_page_stream and release_page_stream methods from the previous example
    preview_option = signature.PreviewOptions(create_page_stream, release_page_stream, resolution)
    preview_option.preview_format = signature.PreviewOptions.PreviewFormats.JPEG
    # generate preview
    sign.generate_preview(preview_option)
```

## More resources

### GitHub Examples

You may easily run the code above and see the feature in action in our GitHub examples:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Along with the full-featured Python library, we provide simple but powerful free online apps.

To sign PDF, Word, Excel, PowerPoint, and other documents you can use the online apps from the **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
