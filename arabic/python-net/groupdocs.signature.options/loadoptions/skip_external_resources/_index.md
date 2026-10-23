---
title: "خاصية skip_external_resources"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "العلم الذي يمنع المستند من تحميل الموارد الخارجية."
type: docs
url: /ar/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

العلم الذي يمنع المستند من تحميل الموارد الخارجية. القيمة الافتراضية هي True؛ لا يتم تحميل الموارد الخارجية إلا تلك التي تتطابق مع [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

يمكن للمستند الإشارة إلى موارد مخزنة خارجه، مثل الصور المرتبطة، والصور التي تُدرج عبر حقل INCLUDEPICTURE، والصور المرتبطة في العروض التقديمية وجداول البيانات، والملفات النمطية والصور التي تُشير إليها صورة SVG. تحميل مثل هذا المورد يجعل المكتبة تطلب عنوانه. على خادم يعالج مستندات غير موثوقة، قد يستخدم المستند ذلك لجعل الخادم يرسل طلبات إلى عناوين داخلية (انتحال طلب من جانب الخادم)، وقد يتسبب مسار UNC أو `file://` في إرسال بيانات اعتماد NTLM الخاصة بالحساب إلى مضيف آخر. في تثبيت غير متصل أو معزول، تفشل الطلبات أو تنتظر انتهاء المهلة.

الموارد التي يتم تخطيها لا تُرسم في معاينات الصفحات أو في المستندات المحفوظة كصور، ولا يتم اكتشافها في بحث الصور أو الباركود أو رموز QR. اضبط هذه الخاصية على False فقط للمستندات الموثوقة، ويفضل السماح بعناوين محددة باستخدام [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

ينطبق هذا الإعداد على مستندات معالجة الكلمات والعروض التقديمية وجداول البيانات وصور SVG، بما في ذلك المستندات داخل الأرشيفات. بالنسبة لصور SVG، تُزال المراجع غير المسموح بها من الصورة قبل قراءتها، وتُرفض صورة SVG التي ليست XMLً مُشكلًا بشكل صحيح. لا يتحكم هذا الإعداد في فحوصات إبطال الشهادات أو خوادم الطوابع الزمنية أو الترخيص.

هذه الخاصية تستبدل [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/)، التي لها معنى عكسي.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### انظر أيضًا
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
