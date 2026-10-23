---
title: "فئة Mailmark2D"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يقوم بترميز وفك ترميز النص المدمج في علامة البريد الملكي 2D Mailmark."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

يقوم بترميز وفك ترميز النص المدمج في علامة البريد الملكي 2D Mailmark.

نوع Mailmark2D يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | يُهيئ بيانات Royal Mail Mailmark المدمجة بالقيم الافتراضية للبيانات الأولية والثانوية. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | يرجع نسخة من هذا الكائن. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | فئة العنصر. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | المساحة الاختيارية لاستخدام العميل. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | وضع الترميز لباركود DataMatrix. القيمة الافتراضية: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | نوع Mailmark ثنائي الأبعاد يحدد حجم باركود Data Matrix. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | الخاصية تحتفظ بالرمز البريدي لعنوان التسليم مع DPS، والذي بالنسبة للعناوين الداخلية يتكون من منطقة (1‑2 حرف)، حي (1‑2 حرف)، قطاع (حرف واحد)، وحدة (حرفان)، وDPS (حرفان)، ويجب أن يتبع تنسيق PAF® صالح، ويبلغ الحد الأقصى للطول 9 أحرف. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | معرّف حمولة باركود Royal Mail Mailmark لكل نوع منتج. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | معرّف العنصر الفريد داخل معرف سلسلة الإمداد، مطلوب على كل باركود Mailmark لتحديد فريد لمدة لا تقل عن 90 يومًا (القيمة القصوى: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | رمز البريد لإعادة الإرسال إلى المرسل بدون DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | العلم الذي يشير إلى مستوى خدمة إعادة الإرسال المطلوبة. الحد الأقصى للطول هو 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | المجموعة الفريدة من العملاء المشاركين في الإرسال. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | معرّف دولة UPU (حد أقصى 4 أحرف). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | معرّف إصدار الباركود المتعلق بكل معرّف نوع المعلومات. |

### انظر أيضًا
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
