---
title: "الفئة TextShadow"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خصائص ظل النص لتوقيعات النص."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/textshadow/
is_root: false
weight: 380
---


## TextShadow class

يمثل خصائص ظل النص لتوقيعات النص.

قد تختلف النتيجة اعتمادًا على نوع التوقيع وتنسيق المستند.

يُوصى باستخدام TextShadow مع توقيع `TextAsImage` لجميع أنواع المستندات المدعومة، وأيضًا مع [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) البسيط و[`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) كعلامة مائية للجداول (`.xslx`) والعروض التقديمية (`.pptx`).

يُوصى أيضًا باستخدام [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) البسيط لمستندات Word (`.docx`)، لكنه يملك وظائف محدودة.

نوع TextShadow يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/__init__/) | يُنشئ TextShadow بالخيارات الافتراضية. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | يحصل على نسخة من هذا الكائن. (موروث من [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [angle](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/angle/) | الزاوية لوضع الظل بالنسبة للنص. القيمة الافتراضية هي 0. |
| [blur](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/blur/) | ضبابية الظل. القيمة الافتراضية هي 4. |
| [color](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/color/) | لون الظل. القيمة الافتراضية هي Black. |
| [distance](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/distance/) | المسافة بين النص والظل. |
| [transparency](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/transparency/) | شفافية الظل. |

### انظر أيضًا
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
