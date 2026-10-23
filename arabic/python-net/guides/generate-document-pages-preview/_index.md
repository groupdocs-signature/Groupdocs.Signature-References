---
title: "إنشاء معاينة صفحات المستند"
linkTitle: "Generate document pages preview"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يوضح هذا الموضوع كيفية الحصول على معاينة صفحات المستند كصور مع خيارات متعددة بواسطة GroupDocs.Signature للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
إليك الخطوات لإنشاء معاينة المستند باستخدام GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

يتم إغلاق الدفق الذي تُعيده دالة create تلقائيًا بمجرد كتابة صورة الصفحة: يتم إغلاق الملف، وتحتوي `io.BytesIO` بالفعل على الصورة الكاملة. إذا كنت بحاجة إلى معالجة كل صورة مكتملة أو تنظيف الموارد بنفسك، مرّر دالة release كمعامل إضافي (انظر [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

تستدعي GroupDocs.Signature دالة create مرة واحدة لكل صفحة وتكتب صورة الصفحة في الدفق الذي تُعيده: كائن ملف قابل للكتابة، أو `io.BytesIO`، أو دفق .NET. المعامل `page_data` هو كائن [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) يحتوي على `page_number` و`file_name` للمستند و`preview_format`.

أرقام الصفحات تبدأ من الصفر: `page_data.page_number` يساوي `0` للصفحة الأولى من المستند.

```python
def create_page_stream(page_data):
    # بدءًا من الصفر: preview_page_0.png هي الصفحة الأولى
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

عند معاينة أرشيف، تُستدعى الدالة لصفحات كل مستند فيه. تبدأ أرقام الصفحات من `0` مرة أخرى لكل مستند، لذا استخدم `page_data.file_name` أيضًا عند تسمية الصور.

## ReleasePageStream delegate implementation

تستقبل دالة release نفس `page_data` ونفس الكائن الذي أرجعته دالة create. بحلول الوقت الذي تُستدعى فيه، تكون الصورة مكتملة.

```python
def release_page_stream(page_data, page_stream):
    # page_stream هو الكائن الذي أرجعته create_page_stream
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs "generate_document_preview" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # أرقام الصفحات تبدأ من الصفر: preview_page_0.png هي الصفحة الأولى
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # إنشاء كائن خيارات المعاينة: صورة PNG واحدة لكل صفحة
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # إنشاء المعاينة
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) لتنزيله.

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

تقرأ هذه المثال المستند من تدفق وتحتفظ بصور الصفحات في الذاكرة: تُعيد الدالة create كائن `io.BytesIO`، وتستقبل الدالة release هذا الكائن مملوءًا بالصورة الكاملة.

{{< tabs "generate_document_preview_from_stream" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # احتفظ بصورة كل صفحة في الذاكرة بدلاً من كتابة ملف
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream هو الـ BytesIO الذي تم إرجاعه أعلاه، وهو يحمل الصورة الكاملة بالفعل
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # إنشاء كائن خيارات المعاينة مع كلتا الدالتين
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # إنشاء المعاينة
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) لتنزيله.

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

عيّن `page_numbers` لمعاينة بعض الصفحات فقط. الأرقام تبدأ من الصفر، لذا `[1]` يختار الصفحة الثانية.

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
        # أرقام الصفحات تبدأ من الصفر: [1] هي الصفحة الثانية
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "preview_page_1.png" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

الدقة الافتراضية هي 96 DPI. مرّر الدقة كالمعامل الثالث لـ [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/)، أو عيّن خاصية `resolution`.

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
        # إنشاء كائن خيارات المعاينة: 150 DPI بدلاً من الافتراضي 96
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # إنشاء المعاينة
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) لتنزيله.

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

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلة GitHub الخاصة بنا:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

إلى جانب مكتبة Python المتكاملة، نوفر تطبيقات مجانية على الإنترنت بسيطة لكنها قوية.

لتوقيع ملفات PDF و Word و Excel و PowerPoint وغيرها من المستندات يمكنك استخدام التطبيقات عبر الإنترنت من **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
