---
title: "فئة SwissAddress"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل عنوان الدائن أو المدين."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

يمثل عنوان الدائن أو المدين.

يمكنك إما تعيين الشارع ورقم المنزل والرمز البريدي والمدينة (نوع العنوان المهيكل) أو السطر الأول والثاني للعنوان (نوع عناصر العنوان المدمجة).

يعرض نوع SwissAddress الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | السطر الأول للعنوان، الذي يحتوي على اسم الشارع أو رقم المنزل أو صندوق البريد، هو اختياري ويُستخدم فقط لعناوين العناصر المدمجة. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | السطر الثاني للعنوان، الذي يحتوي على الرمز البريدي والمدينة، هو إلزامي لعناوين العناصر المدمجة. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | رمز الدولة ISO المكوّن من حرفين. يكون رمز الدولة إلزاميًا ما لم يحتوي العنوان بالكامل على قيم فارغة أو null. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | رقم المنزل. يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | الاسم، إما الاسم الأول واللقب لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | الرمز البريدي. يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | شارع العنوان، بدون رقم منزل؛ اختياري ويُستخدم فقط للعناوين المهيكلة. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | المدينة أو البلدة، تُستخدم فقط للعناوين المهيكلة وإلزامية لهذا النوع. |

### انظر أيضًا
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
