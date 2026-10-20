---
title: "FileType"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يمثل نوع الملف."
type: docs
weight: 610
url: /ar/net/groupdocs.signature.domain/filetype/
---
## FileType class

يمثل نوع الملف.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | لاحقة اسم الملف (بما في ذلك النقطة ".") مثال: ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | اسم نوع الملف مثال: "Microsoft Word Document". |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | يربط امتداد الملف بنوع الملف. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | يحدد ما إذا كان [`FileType`](../filetype) الحالي هو نفسه ككائن [`FileType`](../filetype) المحدد. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | يحدد ما إذا كان [`FileType`](../filetype) الحالي هو نفسه كالكائن المحدد. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | يعيد رمز التجزئة لكائن [`FileType`](../filetype) الحالي. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | يعيد سلسلة تمثل الكائن الحالي. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | يسترجع أنواع الملفات المدعومة |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | يحدد ما إذا كان كائفا [`FileType`](../filetype) متطابقين. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | يحدد ما إذا كان كائنان من [`FileType`](../filetype) ليسا متطابقين. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [APNG](../../groupdocs.signature.domain/filetype/apng) | Animated Portable Network Graphics (.png) هو تنسيق ملف صورة نقطية يستخدم ضغطًا غير فقدان للبيانات. تم تطويره كامتداد لـ PNG لدعم الرسوم المتحركة، ويعمل كبديل لتنسيق GIF بدون قيود حقوق النشر. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/apng). |
| static readonly [AZW3](../../groupdocs.signature.domain/filetype/azw3) | مستند WordPerfect (.wpd) |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | ملف صورة نقطية (.bmp) يُستخدم لتخزين الصور الرقمية النقطية. هذه الصور مستقلة عن محول الرسومات وتُعرف أيضًا باسم تنسيق ملف bitmap غير معتمد على الجهاز (DIB). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/bmp). |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) هو ملف صورة رسم متجه يتم إنشاؤه أصلاً باستخدام CorelDRAW لتخزين الصورة الرقمية المشفرة والمضغوطة. يحتوي مثل هذا الملف على نصوص، خطوط، أشكال، صور، ألوان وتأثيرات لتمثيل المتجه لمحتوى الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/cdr). |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) هو تنسيق ملف ميتا مجاني، غير معتمد على المنصة، ومعيار دولي لتخزين وتبادل الرسومات المتجهة (2D)، الرسومات النقطية، والنص. يستخدم CGM نهجًا موجهًا للكائنات والعديد من وظائف إنتاج الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/cgm). |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | ملف صورة تبادل ميتا CorelDRAW (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | ملف القيم المفصولة بفواصل (.csv) يمثل ملفات نصية عادية تحتوي على سجلات بيانات ذات قيم مفصولة بفواصل. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | صورة DICOM (.dcm) تمثل صورة رقمية تخزن معلومات طبية للمرضى مثل صور الرنين المغناطيسي (MRI)، الأشعة المقطعية (CT) وصور الموجات فوق الصوتية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/dcm). |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | صورة DjVu (.djvu) هو تنسيق ملف رسومي مخصص للمستندات والكتب الممسوحة ضوئيًا، خاصة تلك التي تحتوي على مزيج من النصوص، الرسومات، الصور والفوتوغرافات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/djvu). |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | مستند Microsoft Word (.doc) يمثل مستندات تم إنشاؤها بواسطة Microsoft Word أو برامج معالجة النصوص الأخرى بصيغة ملف ثنائي. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) هو مستند تم إنشاؤه بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه منذ عام 2007 مع إصدار Microsoft Office 2007، حيث تم تغيير بنية هذا التنسيق الجديد من ثنائي عادي إلى مزيج من ملفات XML وملفات ثنائية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | قالب مستند Word (.dot) هو ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOC أو DOCX لاحقًا. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | قالب مستند Word Open XML Macro-Enabled (.dotm) يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أحدث. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | قالب مستند Word Open XML (.dotx) هو ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOCX لاحقًا. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) يمثل صورًا رسومية غير معتمدة على الجهاز. تتألف ملفات الميتا EMF من سجلات ذات طول متغير بترتيب زمني يمكنها عرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/emf). |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | ملف Encapsulated PostScript (.eps) يصف برنامج لغة Encapsulated PostScript يصف مظهر صفحة واحدة. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/page-description-language/eps). |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | ملف Graphical Interchange Format (.gif) هو نوع من الصور المضغوطة بشكل كبير. لكل صورة عادةً يسمح GIF بما يصل إلى 8 بت لكل بكسل وتُسمح بما يصل إلى 256 لونًا عبر الصورة. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/gif). |
| static readonly [GZip](../../groupdocs.signature.domain/filetype/gzip) | أرشيف مضغوط بتقنية GZip (.gz) يضغط الملفات بنسبة ضغط عالية. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/compression/gz). |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | صورة JPEG (.jpeg) هي نوع من تنسيقات الصور تُحفظ باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، هي موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | صورة JPEG (.jpg) هي نوع من تنسيقات الصور تُحفظ باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، هي موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/jpeg). |
| static readonly [LZip](../../groupdocs.signature.domain/filetype/lzip) | أرشيف مضغوط بتقنية LZip (.lz) يضغط الملفات بنسبة ضغط عالية. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/compression/lz). |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | ملف OpenDocument Graphic (.odg) يُستخدم بواسطة تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/odg). |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | ملف OpenDocument Presentation (.odp) يمثل تنسيق ملف العروض التقديمية المستخدم من قبل OpenOffice.org في معيار OASISOpen. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | ملف OpenDocument Spreadsheet (.ods) هو تنسيق مستند جدول بيانات OpenDocument يمكن تحريره من قبل المستخدم. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | ملف OpenDocument Text Document (.odt) هو نوع من المستندات التي تُنشأ باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف نص OpenDocument. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | ملف OpenDocument Presentation Template (.otp) يمثل ملفات قوالب العروض التقديمية التي تُنشئها التطبيقات وفقًا لتنسيق معيار OASIS OpenDocument. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/otp). |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument Spreadsheet Template (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | ملف OpenDocument Document Template (.ott) يمثل مستندات القوالب التي تُنشئها التطبيقات وفقًا لتنسيق معيار OASIS OpenDocument. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Printer Command Language Document (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | ملف Portable Document Format (.pdf) هو نوع من المستندات أنشأته شركة Adobe في التسعينيات. كان هدف هذا التنسيق تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى في تنسيق يكون مستقلاً عن برامج التطبيقات والعتاد وكذلك نظام التشغيل. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/view/pdf). |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | ملف Personal Information Exchange (.pfx) هو ملف شهادة محمي بكلمة مرور يُستخدم عادةً لتوقيع الشيفرة لتطبيقك. تعرف على المزيد حول تنسيق الملف هذا [here](https://fileinfo.com/extension/pfx). |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | ملف Portable Network Graphic (.png) هو نوع من تنسيقات ملفات الصور النقطية التي تستخدم ضغطًا غير فقداني. تم إنشاء هذا التنسيق كبديل لتنسيق Graphics Interchange Format (GIF) ولا يحتوي على قيود حقوق النشر. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/png). |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | قالب PowerPoint (.pot) يمثل ملفات قوالب Microsoft PowerPoint التي أنشأتها إصدارات PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/pot). |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | قالب عرض PowerPoint Open XML Macro-Enabled Presentation (.potm) هو ملفات قالب Microsoft PowerPoint مع دعم للماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو أحدث وتحتوي على إعدادات افتراضية يمكن استخدامها لإنشاء ملفات عرض أخرى. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/potm). |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | قالب عرض PowerPoint Open XML Presentation (.potx) يمثل قوالب عروض Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو أحدث. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/potx). |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | عرض شرائح PowerPoint Slide Show (.pps) يتم إنشاؤه باستخدام Microsoft PowerPoint لأغراض العرض الشرائحي. يتم دعم قراءة وإنشاء ملفات PPS بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | شريحة PowerPoint Open XML Macro-Enabled Slide (.ppsm) تمثل تنسيق ملف عرض شرائح مدعوم بالماكرو تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أعلى. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | ملفات عرض شرائح PowerPoint Open XML Slide Show (.ppsx) يتم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو أعلى لأغراض العرض الشرائحي. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | عرض PowerPoint Presentation (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض شرائحي. يحدد تنسيق الملف الثنائي المستخدم من قبل Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | عرض PowerPoint Open XML Macro-Enabled Presentation هو ملفات عرض مدعومة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | عرض PowerPoint Open XML Presentation (.pptx) هي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس النسخة السابقة من تنسيق ملف العرض PPT الذي كان ثنائيًا، يعتمد تنسيق PPTX على تنسيق عرض XML المفتوح من Microsoft PowerPoint. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | ملف PostScript (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | مستند Adobe Photoshop (.psd) يمثل تنسيق الملف الأصلي لبرنامج Adobe Photoshop المستخدم في تصميم وتطوير الرسومات. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/psd). |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | ملف Rich Text Format (.rtf) يمثل طريقة لترميز النص المنسق والرسومات للاستخدام داخل التطبيقات. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [SevenZip](../../groupdocs.signature.domain/filetype/sevenzip) | أرشيف مضغوط عالي الضغط (.7z) يضغط الملفات والمجلدات بنسبة ضغط عالية. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/page-description-language/7z). |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | ملف Scalable Vector Graphics (.svg) هو ملف رسومات متجهية قابلة للتوسع يستخدم تنسيق نص مبني على XML لوصف مظهر الصورة. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [TAR](../../groupdocs.signature.domain/filetype/tar) | الأداة المستندة إلى Unix لجمع ملف واحد أو أكثر (.tar) هي أرشيف يمكنه احتواء ملف أو أكثر أو أدلة. تعرف على المزيد حول تنسيق الملف هذا [here](https://docs.fileformat.com/compression/tar/). |
| static readonly [TGA](../../groupdocs.signature.domain/filetype/tga) | Truevision TGA (.tga)، المعروف أيضًا باسم TARGA، هو تنسيق ملف صورة نقطية تم تطويره بواسطة شركة Truevision Inc. يدعم أعماق ألوان مختلفة وضغط RLE اختياري. تُستخدم ملفات TGA عادةً في ألعاب الفيديو، خطوط أنابيب الرسوم المتحركة، وتطبيقات الرسومات لتقديم صور عالية الجودة مع دعم قناة ألفا اختياري. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/tga). |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | ملف الصورة الموسومة (.tif) يمثل صورًا نقطية مُصممة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار تنسيق الملف هذا. وهو قادر على وصف بيانات الصورة ذات المستوى الثنائي، وتدرج الرمادي، وألوان اللوحة، والألوان الكاملة في عدة مساحات لونية. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/image/tiff). |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | تنسيق ملف الصورة الموسومة (.tiff) يمثل صورًا نقطية مُصممة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار تنسيق الملف هذا. وهو قادر على وصف بيانات الصورة ذات المستوى الثنائي، وتدرج الرمادي، وألوان اللوحة، والألوان الكاملة في عدة مساحات لونية. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/image/tiff). |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | ملف القيم المفصولة بالجدولة (.tsv) يمثل بيانات مفصولة بعلامات الجدولة في تنسيق نص عادي. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | ملف النص العادي (.txt) يمثل مستند نص يحتوي على نص عادي على شكل سطور. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | يمثل نوع ملف غير معروف. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | ملف vCard (.vcf) هو تنسيق ملف رقمي لتخزين معلومات الاتصال. يُستخدم هذا التنسيق على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشهيرة. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/email/vcf). |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | صورة WebP (.webp) هي تنسيق ملف صورة نقطية حديث للويب يعتمد على الضغط غير الفاقد والفاقد. يوفر نفس جودة الصورة مع تقليل حجم الصورة بشكل كبير. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/image/webp). |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | ملف Windows Metafile (.wmf) يمثل ملف Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهية وكذلك بصيغة bitmap. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/image/wmf). |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | مستند WordPerfect (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | جدول بيانات Excel (.xls) يمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج الجداول المشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | جدول بيانات Excel الثنائي (.xlsb) يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | جدول بيانات Excel Open XML المدعم بالماكرو (.xlsm) هو نوع من ملفات الجداول التي تدعم الماكرو. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | جدول بيانات Microsoft Excel Open XML (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | قالب Excel الثنائي (.xlt) يمثل تنسيق ملف قالب Excel. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | قالب ملف Excel Office OpenXML (.xltm) يمثل تنسيق ملف قالب Excel. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [ZIP](../../groupdocs.signature.domain/filetype/zip) | أرشيف ZIP للوثائق (.zip) هو تنسيق ملف أرشيف يدعم ضغط البيانات غير الفاقد. يمكنه احتواء ملف أو أكثر أو أدلة. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://docs.fileformat.com/compression/zip/). |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* More about how to get supported formats list in C#: [How to get supported file formats in C# code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### انظر أيضًا

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
