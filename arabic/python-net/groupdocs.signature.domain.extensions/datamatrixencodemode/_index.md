---
title: "فئة DataMatrixEncodeMode"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تعداد DataMatrixEncodeMode — GroupDocs.Signature للبايثون عبر مرجع API .NET."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

يعرض نوع DataMatrixEncodeMode الأعضاء التالية:

### الحقول
| حقل | الوصف |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | اختيار تلقائي لأفضل وضع ترميز لتشفير DataMatrix |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | يقوم بترميز حرف أبجدي رقمي واحد أو حرفين رقميين لكل بايت |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | ترميز قيم 8 بت |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | ترميز باستخدام الترميز المحدد في BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | يستخدم ترميز C40. يرمز الأحرف الأبجدية الرقمية الكبيرة، الأحرف الصغيرة والرموز الخاصة |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | يستخدم ترميز النص. يرمز الأحرف الأبجدية الرقمية الصغيرة، الأحرف الكبيرة والرموز الخاصة. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | يستخدم ترميز EDIFACT. يستخدم ست بتات لكل حرف، يرمز الأرقام، الأحرف الكبيرة، والعديد من علامات الترقيم، لكنه لا يدعم الأحرف الصغيرة. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | يستخدم ترميز ANSI X12. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | وضع ExtendedCodetext يسمح بالتبديل اليدوي بين مخططات الترميز في code-text. الصيغة : "\Encodation_scheme_name:text\Encodation_scheme_name:text". مخططات الترميز المسموح بها هي: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. مثال على code-text الموسع: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" يجب أن تكون جميع الشرطات المائلة العكسية (\) مضاعفة في النص. |

### انظر أيضًا
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
