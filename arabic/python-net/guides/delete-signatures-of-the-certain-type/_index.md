---
title: "حذف التوقيعات من النوع المحدد"
linkTitle: "Certain Type"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تشرح هذه المقالة كيفية حذف التوقيعات الإلكترونية من النوع المحدد باستخدام واجهة برمجة تطبيقات GroupDocs.Signature."
type: docs
url: /ar/python-net/guides/delete-signatures-of-the-certain-type/
is_root: false
weight: 110
---


## Overview
[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides ability to delete signatures of the certain type from the documents over [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method.  
يرجى العلم أن طريقة [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) تعدّل نفس المستند الذي تم تمريره إلى مُنشئ الفئة [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) ، لذا فإن المثال أدناه ينسخ المستند الموقّع أولاً ويحذف التوقيعات من النسخة.

## How to delete signatures of the certain type from the document
فيما يلي الخطوات لحذف التوقيعات من النوع المحدد من المستند باستخدام GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass source document path as a constructor parameter;
* Call [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) object [delete](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/delete) method and pass the [SignatureType](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/signaturetype/) of the signatures to remove, for example `SignatureType.TEXT`;
* Check the returned [DeleteResult](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/deleteresult/): its `succeeded` list holds the deleted signatures and `failed` holds the signatures that could not be deleted.

يوضح هذا المثال كيفية حذف جميع التوقيعات النصية من المستند. يتم حذف التوقيعات التي أضافتها GroupDocs.Signature فقط؛ يبقى نص المستند نفسه كما هو.

{{< tabs "delete_signatures_by_type" >}}
{{< tab "Python" >}}
```python
import shutil

from groupdocs.signature import Signature
from groupdocs.signature.domain import SignatureType

def delete_signatures_by_type():
    # تقوم delete() بحفظ التغييرات في المستند المفتوح، لذا اعمل على نسخة.
    shutil.copy("signed.docx", "all_text_signatures_deleted.docx")

    with Signature("all_text_signatures_deleted.docx") as signature:
        # حذف كل توقيع نصي في المستند
        result = signature.delete(SignatureType.TEXT)
        print(f"Deleted {len(result.succeeded)} text signature(s), {len(result.failed)} failed")
        for number, deleted in enumerate(result.succeeded, 1):
            print(f"  #{number}: '{deleted.text}' (id {deleted.signature_id})")

if __name__ == "__main__":
    delete_signatures_by_type()
```
{{< /tab >}}
{{< tab "signed.docx" >}}

`signed.docx` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/signed.docx) لتنزيله.

{{< /tab >}}
{{< tab "all_text_signatures_deleted.docx" >}}
```text
Binary file (DOCX, 147 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/delete-signatures-from-documents/delete-signatures-of-the-certain-type/delete_signatures_by_type/all_text_signatures_deleted.docx)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

يمكنك بسهولة تشغيل الشيفرة أعلاه ورؤية الميزة قيد التنفيذ في أمثلة GitHub الخاصة بنا:

* [GroupDocs.Signature for Python via .NET examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

إلى جانب مكتبة Python المتكاملة، نوفر تطبيقات مجانية على الإنترنت بسيطة لكنها قوية.

لتوقيع ملفات PDF و Word و Excel و PowerPoint وغيرها من المستندات يمكنك استخدام التطبيقات عبر الإنترنت من **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
