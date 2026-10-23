---
title: "فئة SignatureSettings"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل الإعدادات لتخصيص سلوك Signature."
type: docs
url: /ar/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

يمثل الإعدادات لتخصيص سلوك [`Signature`](/signature/python-net/groupdocs.signature/signature/).

نوع SignatureSettings يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | يُهيئ نسخة SignatureSettings افتراضية بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | يُهيئ نسخة SignatureSettings افتراضية باستخدام تنفيذ Logger. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | الثقافة الافتراضية المستخدمة أثناء معالجة المستندات. القيمة الافتراضية هي "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | العلم الذي يشير إلى ما إذا كانت توقيعات بيانات التعريف القياسية للمستند مثل المؤلف، المالك، تاريخ الإنشاء، وتاريخ التعديل مُدرجة في قائمة بيانات التعريف. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | العلم الذي يحدد مستويات السجل والذي يحدد أي أنواع الرسائل يتم تمريرها إلى [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | تنفيذ المسجل المستخدم لتسجيل (الأخطاء، التحذيرات، المتتبعات). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | العلم الذي يحدد ما إذا كان يتم حفظ المستند الأصلي مرة أخرى عندما لا يحتوي أسلوب Delete على توقيعات متأثرة لإزالتها. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | العلم الذي يحدد ما إذا كان يتم حفظ المستند الأصلي مرة أخرى عندما لا يحتوي أسلوب `Update` على توقيعات لتحديثها. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | العلم الذي يحدد ما إذا كانت التوقيعات المحذوفة مُدرجة في نتيجة معلومات المستند. كل [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) يحتوي على علم `Deleted` للإشارة إلى ما إذا تم حذفه. |

### انظر أيضًا
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
