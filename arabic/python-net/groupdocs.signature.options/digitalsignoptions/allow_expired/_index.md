---
title: "خاصية allow_expired"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "العلم الذي يسمح بالتوقيع بشهادة انتهت فترة صلاحيتها."
type: docs
url: /ar/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/
is_root: false
weight: 2010
---


## allow_expired property

العلم الذي يسمح بالتوقيع باستخدام شهادة انتهت فترة صلاحيتها. القيمة الافتراضية هي False؛ التوقيع بشهادة منتهية الصلاحية يثير `GroupDocsSignatureException` ولا يتم توقيع المستند.

المصادقون يبلغون عن توقيع تم إنشاؤه بشهادة منتهية الصلاحية على أنه غير صالح. اضبط هذه الخاصية على True فقط عندما تحتاج إلى مثل هذا التوقيع على أي حال، على سبيل المثال لاختبار بشهادة قديمة. ثم يتم توقيع المستند، ويُكتب تحذير إلى السجل المحدد في [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

يتم مقارنة الشهادة بالوقت الحالي بتوقيت UTC، وليس بـ [`DigitalSignature.sign_time`](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/). ينطبق هذا العلم على الشهادة المقدمة عبر [`DigitalSignOptions.CertificateFilePath`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/)، [`DigitalSignOptions.CertificateStream`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) أو [`DigitalSignOptions.Signature`](/signature/python-net/groupdocs.signature/signature/)، وعند توقيع جدول بيانات، على شهادة الامتداد الأول [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/). لا تستخدم التوقيعات الرقمية للصور شهادة ولا يتم فحصها. تُتحكم شهادة لم يبدأ بعد فترة صلاحيتها بواسطة [`DigitalSignOptions.AllowNotYetValid`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/).

### Definition:
```python
@property
def allow_expired(self):
    ...
@allow_expired.setter
def allow_expired(self, value):
    ...
```

### انظر أيضًا
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
