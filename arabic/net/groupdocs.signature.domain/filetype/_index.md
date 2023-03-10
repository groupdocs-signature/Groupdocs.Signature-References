---
title: FileType
second_title: GroupDocs.Signature لمرجع .NET API
description: يمثل نوع الملف.
type: docs
weight: 450
url: /ar/net/groupdocs.signature.domain/filetype/
---
## FileType class

يمثل نوع الملف.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | لاحقة اسم الملف (بما في ذلك النقطة ".") مثل ".doc" . |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | اسم نوع الملف ، مثل "مستند Microsoft Word". |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | امتداد ملف الخرائط لنوع الملف. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | يحدد ما إذا كان التيار[`FileType`](../filetype)هو نفسه كما هو محدد[`FileType`](../filetype) الكائن . |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | يحدد ما إذا كان التيار[`FileType`](../filetype) هو نفس الكائن المحدد. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | إرجاع كود التجزئة الحالي[`FileType`](../filetype) الكائن . |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | استرداد أنواع الملفات المدعومة |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | تحديد ما إذا كان اثنان[`FileType`](../filetype) الكائنات هي نفسها. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | تحديد ما إذا كان اثنان[`FileType`](../filetype) الكائنات ليست هي نفسها. |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | ملف الصورة النقطية (.bmp) يُستخدم لتخزين الصور الرقمية للصور النقطية. هذه الصور مستقلة عن محول الرسومات وتسمى أيضًا تنسيق ملف الصورة النقطية المستقلة عن الجهاز (DIB) . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) هو ملف صورة رسم متجه تم إنشاؤه أصلاً باستخدام CorelDRAW لتخزين الصور الرقمية المشفرة والمضغوطة. يحتوي ملف الرسم هذا على نص وخطوط وأشكال وصور وألوان وتأثيرات للتمثيل المتجه لمحتويات الصورة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) هو تنسيق ملف تعريف قياسي دولي مجاني ومستقل عن النظام الأساسي لتخزين وتبادل الرسومات المتجهة (2D) والرسومات النقطية والنص. يستخدم CGM نهجًا موجهًا للكائنات والعديد من أحكام الوظائف لإنتاج الصور. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW Metafile Exchange Image File (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | يمثل ملف القيم المفصولة بفواصل (.csv) ملفات نصية عادية تحتوي على سجلات بيانات بقيم مفصولة بفواصل . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | صورة DICOM (.dcm) تمثل الصورة الرقمية التي تخزن المعلومات الطبية للمرضى مثل التصوير بالرنين المغناطيسي والأشعة المقطعية وصور الموجات فوق الصوتية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu) هو تنسيق ملف رسومي مخصص للمستندات والكتب الممسوحة ضوئيًا وخاصة تلك التي تحتوي على مجموعة من النصوص والرسومات والصور والصور الفوتوغرافية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | يمثل مستند Microsoft Word (.doc) المستندات التي تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة النصوص الأخرى بتنسيق ملف ثنائي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | مستند Word Open XML Macro-Enabled (.docm) هو مستند Microsoft Word 2007 أو إصدار أحدث مع إمكانية تشغيل وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه من عام 2007 مع إصدار Microsoft Office 2007 ، تم تغيير هيكل تنسيق المستند الجديد هذا من ثنائي عادي إلى مجموعة من ملفات XML والملفات الثنائية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | قالب مستند Word (.dot) عبارة عن ملفات قوالب تم إنشاؤها بواسطة Microsoft Word لإعدادات منسقة مسبقًا لإنشاء ملفات DOC أو DOCX أخرى. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | قالب مستند Word Open XML ممكّن بماكرو (.dotm) يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) هي ملفات قوالب تم إنشاؤها بواسطة Microsoft Word لإعدادات منسقة مسبقًا لإنشاء ملفات DOCX أخرى. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | يمثل ملف تعريف Windows المحسّن (.emf) الصور الرسومية على حدة. تتكون ملفات التعريف الخاصة بـ EMF من سجلات متغيرة الطول بترتيب زمني يمكن أن تعرض الصورة المخزنة بعد التحليل على أي جهاز إخراج . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | يصف ملف Encapsulated PostScript (.eps) برنامج لغة Encapsulated PostScript يصف مظهر صفحة واحدة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | ملف تنسيق التبادل الرسومي (.gif) هو نوع من الصور شديدة الضغط. لكل صورة ، يسمح GIF عادةً بما يصل إلى 8 بت لكل بكسل وما يصل إلى 256 لونًا مسموح به عبر الصورة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | صورة JPEG (.jpeg) هي نوع من تنسيق الصورة يتم حفظها باستخدام طريقة الضغط مع فقدان البيانات. الصورة الناتجة ، كنتيجة للضغط ، هي مقايضة بين حجم التخزين وجودة الصورة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | صورة JPEG (.jpg) هي نوع من تنسيق الصورة يتم حفظها باستخدام طريقة الضغط مع فقدان البيانات. الصورة الناتجة ، كنتيجة للضغط ، هي مقايضة بين حجم التخزين وجودة الصورة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | ملف رسومي OpenDocument (.odg) يستخدم بواسطة تطبيق رسم Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp) يمثل تنسيق ملف العرض التقديمي المستخدم بواسطة OpenOffice.org في معيار OASISOpen . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | جدول بيانات OpenDocument (.ods) يرمز إلى تنسيق OpenDocument Spreadsheet Document الذي يمكن للمستخدم تحريره. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument Text Document (.odt) هو نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة الكلمات التي تعتمد على تنسيق OpenDocument Text File. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | قالب العرض التقديمي OpenDocument (.otp) يمثل ملفات قالب العرض التقديمي التي تم إنشاؤها بواسطة تطبيقات بتنسيق OASIS OpenDocument القياسي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | قالب جدول بيانات OpenDocument (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | قالب مستند OpenDocument (.ott) يمثل مستندات نموذجية تم إنشاؤها بواسطة التطبيقات وفقًا للتنسيق القياسي OpenDocument الخاص بـ OASIS. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | مستند لغة أوامر الطابعة (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | ملف تنسيق المستند المحمول (.pdf) هو نوع من المستندات التي أنشأتها Adobe في التسعينيات. كان الغرض من تنسيق الملف هذا هو تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى بتنسيق مستقل عن برامج التطبيقات والأجهزة وكذلك نظام التشغيل. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Scalable Vector Graphics File (.svg) هو ملف Scalar Vector Graphics يستخدم تنسيقًا نصيًا يستند إلى XML لوصف مظهر الصورة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) هو نوع من تنسيق ملف الصورة النقطية الذي يستخدم ضغطًا بدون فقدان البيانات. تم إنشاء تنسيق الملف هذا كبديل لتنسيق تبادل الرسومات (GIF) وليس له قيود على حقوق النشر . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | قالب PowerPoint (.pot) يمثل ملفات قوالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | قالب العرض التقديمي لـ PowerPoint Open XML مع تمكين ماكرو (.potm) عبارة عن ملفات قالب Microsoft PowerPoint مع دعم لوحدات الماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو إصدار أحدث وتحتوي على الإعدادات الافتراضية التي يمكن استخدامها لإنشاء المزيد من ملفات العروض التقديمية . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) يمثل العروض التقديمية لقالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | يتم إنشاء عرض شرائح PowerPoint (.pps) باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يتم دعم قراءة ملف PPS وإنشائه بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) يمثل تنسيق ملف عرض الشرائح الذي تم تمكينه بماكرو والذي تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | يتم إنشاء ملفات PowerPoint Open XML Slide Show (.ppsx) باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث لغرض عرض الشرائح . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint Presentation (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح لعرضها على هيئة SlideShow. تحدد تنسيق الملف الثنائي المستخدم بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enable Presentation عبارة عن ملفات عروض تقديمية تم تمكين الماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) هي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس الإصدار السابق من تنسيق ملف العرض التقديمي PPT الذي كان ثنائيًا ، يعتمد تنسيق PPTX على تنسيق ملف العرض التقديمي XML المفتوح لبرنامج Microsoft PowerPoint. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | ملف PostScript (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | يمثل Adobe Photoshop Document (.psd) تنسيق ملف Adobe Photoshop الأصلي المستخدم في تصميم الرسومات وتطويرها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | يمثل ملف Rich Text Format (.rtf) طريقة لترميز النص والرسومات المنسقة للاستخدام داخل التطبيقات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) هو ملف Scalar Vector Graphics يستخدم تنسيقًا نصيًا يستند إلى XML لوصف مظهر الصورة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | ملف الصور ذي العلامات (.tif) يمثل الصور النقطية المخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار تنسيق الملف هذا. إنه قادر على وصف بيانات الصورة ذات المستوى الثنائي ، والرمادي ، واللون الملون ، وبيانات الصور كاملة الألوان في العديد من مساحات الألوان. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | تنسيق ملف الصورة ذي العلامات (.tiff) يمثل الصور النقطية المخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار تنسيق الملف هذا. إنه قادر على وصف بيانات الصورة ذات المستوى الثنائي ، والرمادي ، واللون الملون ، وبيانات الصور كاملة الألوان في العديد من مساحات الألوان. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | يمثل ملف القيم المفصولة بعلامات جدولة (.tsv) بيانات مفصولة بعلامات تبويب بتنسيق نص عادي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | ملف نصي عادي (.txt) يمثل مستندًا نصيًا يحتوي على نص عادي في شكل أسطر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | يمثل نوع ملف غير معروف. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | ملف vCard (.vcf) هو تنسيق ملف رقمي لتخزين معلومات جهات الاتصال. يستخدم التنسيق على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشائعة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) هو تنسيق ملف صورة ويب نقطية حديث يعتمد على ضغط بدون فقد أو فقدان البيانات. إنه يوفر نفس جودة الصورة مع تقليل حجم الصورة بشكل كبير. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | يمثل Windows Metafile (.wmf) Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهية وكذلك بصيغة الصور النقطية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | مستند WordPerfect (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | جدول بيانات Excel (.xls) يمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | يحدد جدول بيانات Excel الثنائي (.xlsb) تنسيق ملف Excel الثنائي ، وهو عبارة عن مجموعة من السجلات والهياكل التي تحدد محتوى مصنف Excel. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) هو نوع من ملفات جداول البيانات التي تدعم وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه بواسطة Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | قالب Excel الثنائي (.xlt) يمثل تنسيق ملف قالب Excel . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | قالب ملف Excel Office OpenXML (.xltm) يمثل تنسيق ملف قالب Excel . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xltm) . |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs. التوقيع: [تنسيقات المستندات التي يدعمها GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* المزيد حول كيفية الحصول على قائمة التنسيقات المدعومة في C #: [كيفية الحصول على تنسيقات الملفات المدعومة في كود C #](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### أنظر أيضا

* مساحة الاسم [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
