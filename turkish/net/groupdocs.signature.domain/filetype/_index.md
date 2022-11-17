---
title: FileType
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Dosya türünü temsil eder.
type: docs
weight: 430
url: /tr/net/groupdocs.signature.domain/filetype/
---
## FileType class

Dosya türünü temsil eder.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Dosya adı son eki ("." noktası dahil) ör. ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Dosya türü adı, örneğin "Microsoft Word Belgesi". |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Dosya uzantısını dosya türüyle eşler. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Mevcut olup olmadığını belirler.[`FileType`](../filetype)belirtilenle aynı[`FileType`](../filetype) nesne. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Mevcut olup olmadığını belirler.[`FileType`](../filetype) belirtilen nesneyle aynı. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Mevcut için hash kodunu döndürür[`FileType`](../filetype) nesne. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Desteklenen dosya türlerini alır |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | İki olup olmadığını belirler[`FileType`](../filetype) nesneler aynıdır. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | İki olup olmadığını belirler[`FileType`](../filetype) nesneler aynı değil. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap Görüntü Dosyası (.bmp), bitmap dijital görüntüleri depolamak için kullanılır. Bu görüntüler, grafik bağdaştırıcısından bağımsızdır ve aygıttan bağımsız bit eşlem (DIB) dosya biçimi olarak da adlandırılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr), dijital görüntüyü kodlanmış ve sıkıştırılmış olarak depolamak için CorelDRAW ile yerel olarak oluşturulmuş bir vektör çizim görüntü dosyasıdır. Böyle bir çizim dosyası, görüntü içeriğinin vektör temsili için metin, çizgiler, şekiller, görüntüler, renkler ve efektler içerir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Bilgisayar Grafikleri Meta Dosyası (.cgm), vektör grafikleri (2B), tarama grafikleri ve metinleri depolamak ve değiştirmek için ücretsiz, platformdan bağımsız, uluslararası standart bir meta dosyası biçimidir. CGM, görüntü üretimi için nesne yönelimli yaklaşım ve birçok fonksiyon provizyonu kullanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW Meta Dosyası Değişim Görüntü Dosyası (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Virgülle Ayrılmış Değerler Dosyası (.csv), virgülle ayrılmış değerler içeren veri kayıtlarını içeren düz metin dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM Görüntüsü (.dcm), MRI'lar, CT taramaları ve ultrason görüntüleri gibi hastaların tıbbi bilgilerini depolayan dijital görüntüyü temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Görüntüsü (.djvu), özellikle metin, çizim, resim ve fotoğrafların birleşimini içeren taranmış belgeler ve kitaplar için tasarlanmış bir grafik dosyası biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word Belgesi (.doc), Microsoft Word veya diğer kelime işlem belgeleri tarafından ikili dosya biçiminde oluşturulan belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm), Microsoft Word 2007 veya daha yüksek sürümde oluşturulmuş ve makro çalıştırabilen bir belgedir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Açık XML Belgesi (.docx), Microsoft Word belgeleri için iyi bilinen bir biçimdir. 2007'den itibaren Microsoft Office 2007'nin piyasaya sürülmesiyle tanıtılan bu yeni Belge biçiminin yapısı, düz ikiliden XML ve ikili dosyaların birleşimine değiştirildi. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word Belge Şablonu (.dot), daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Açık XML Makro Etkin Belge Şablonu (.dotm), Microsoft Word 2007 veya üstü ile oluşturulan şablon dosyasını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Açık XML Belge Şablonu (.dotx), daha fazla DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Gelişmiş Windows Meta Dosyası (.emf), cihazdan bağımsız olarak grafik görüntüleri temsil eder. EMF'nin meta dosyaları, herhangi bir çıktı aygıtında ayrıştırıldıktan sonra depolanan görüntüyü işleyebilen, kronolojik sırada yer alan değişken uzunluklu kayıtlardan oluşur. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps), tek bir sayfanın görünümünü tanımlayan Encapsulated PostScript dil programını tanımlar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Grafik Değişim Biçimi Dosyası (.gif), yüksek oranda sıkıştırılmış bir görüntü türüdür. Her görüntü için GIF tipik olarak piksel başına 8 bite kadar izin verir ve görüntü genelinde 256 renge kadar izin verilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG Görüntüsü (.jpeg), kayıplı sıkıştırma yöntemi kullanılarak kaydedilen bir görüntü formatı türüdür. Çıktı görüntüsü, sıkıştırmanın bir sonucu olarak, depolama boyutu ile görüntü kalitesi arasında bir değiş tokuştur. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG Görüntüsü (.jpg), kayıplı sıkıştırma yöntemi kullanılarak kaydedilen bir tür görüntü formatıdır. Çıktı görüntüsü, sıkıştırmanın bir sonucu olarak, depolama boyutu ile görüntü kalitesi arasında bir değiş tokuştur. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument Grafik Dosyası (.odg), çizim öğelerini vektör görüntüsü olarak depolamak için Apache OpenOffice'in Draw uygulaması tarafından kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp), OpenOffice.org tarafından OASISOpen standardında kullanılan sunum dosyası formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Elektronik Tablosu (.ods), kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablosu Belge biçimi anlamına gelir. Veriler, ODF dosyası içinde satırlar ve sütunlar halinde depolanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument Metin Belgesi (.odt), OpenDocument Metin Dosyası biçimini temel alan kelime işlem uygulamalarıyla oluşturulan belge türleridir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument Sunum Şablonu (.otp), uygulamalar tarafından OASIS OpenDocument standart biçiminde oluşturulan sunum şablonu dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument Elektronik Tablo Şablonu (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument Belge Şablonu (.ott), OASIS'in OpenDocument standart formatına uygun uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Yazıcı Komut Dili Belgesi (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf), Adobe tarafından 1990'larda oluşturulmuş bir belge türüdür. Bu dosya biçiminin amacı, belgelerin ve diğer başvuru malzemelerinin uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir biçimde temsil edilmesi için bir standart getirmekti. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Taşınabilir Ağ Grafiği (.png), kayıpsız sıkıştırma kullanan bir tür raster görüntü dosyası formatıdır. Bu dosya biçimi, Grafik Değişim Biçimi'nin (GIF) yerini almak üzere oluşturulmuştur ve hiçbir telif hakkı sınırlaması yoktur. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint Şablonu (.pot), PowerPoint 97-2003 sürümleri tarafından oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Açık XML Makro Etkin Sunum Şablonu (.potm), Makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM dosyaları PowerPoint 2007 veya üzeri ile oluşturulur ve daha fazla sunum dosyası oluşturmak için kullanılabilecek varsayılan ayarları içerir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Açık XML Sunum Şablonu (.potx), Microsoft PowerPoint 2007 ve sonraki sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint Slayt Gösterisi (.pps), Slayt Gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulur. PPS dosyası okuma ve oluşturma, Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Açık XML Makro Etkin Slayt (.ppsm), Microsoft PowerPoint 2007 veya sonraki sürümlerle oluşturulan Makro etkin Slayt Gösterisi dosya biçimini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Açık XML Slayt Gösterisi (.ppsx) dosyaları, Slayt Gösterisi amacıyla Microsoft PowerPoint 2007 ve üzeri kullanılarak oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint Sunumu (.ppt), SlideShow olarak görüntülemek için bir slayt koleksiyonundan oluşan PowerPoint dosyasını temsil eder. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Biçimini belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Açık XML Makro Etkin Sunum, Microsoft PowerPoint 2007 veya daha yüksek sürümleriyle oluşturulan Makro Etkin Sunum dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Açık XML Sunumu (.pptx), popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. İkili olan sunum dosyası biçimi PPT'nin önceki sürümünün aksine, PPTX biçimi Microsoft PowerPoint açık XML sunum dosyası biçimini temel alır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript Dosyası (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Belgesi (.psd), Adobe Photoshop'un grafik tasarımı ve geliştirme için kullanılan yerel dosya biçimini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Zengin Metin Biçimi Dosyası (.rtf), uygulamalarda kullanılmak üzere biçimlendirilmiş metin ve grafikleri kodlama yöntemini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Ölçeklenebilir Vektör Grafik Dosyası (.svg), bir görüntünün görünümünü açıklamak için XML tabanlı metin formatı kullanan bir Skaler Vektör Grafik dosyasıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Etiketli Görüntü Dosyası (.tif), bu dosya biçimi standardına uyan çeşitli aygıtlarda kullanılması amaçlanan raster görüntüleri temsil eder. Birkaç renk uzayında çift seviyeli, gri tonlamalı, palet renkli ve tam renkli görüntü verilerini tanımlayabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Etiketli Görüntü Dosyası Biçimi (.tiff), bu dosya biçimi standardına uyan çeşitli aygıtlarda kullanılması amaçlanan raster görüntüleri temsil eder. Birkaç renk uzayında çift seviyeli, gri tonlamalı, palet renkli ve tam renkli görüntü verilerini tanımlayabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Sekmeyle Ayrılmış Değerler Dosyası (.tsv), düz metin biçiminde sekmelerle ayrılmış verileri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Düz Metin Dosyası (.txt), satır biçiminde düz metin içeren bir metin belgesini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Bilinmeyen dosya türünü temsil eder. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard Dosyası (.vcf), iletişim bilgilerini depolamak için kullanılan bir dijital dosya biçimidir. Biçim, popüler bilgi alışverişi uygulamaları arasında veri alışverişi için yaygın olarak kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Görüntüsü (.webp), kayıpsız ve kayıplı sıkıştırmaya dayalı modern bir raster web görüntü dosyası biçimidir. Görüntü boyutunu önemli ölçüde azaltırken aynı görüntü kalitesini sağlar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Meta Dosyası (.wmf), vektörün yanı sıra bitmap biçimli görüntü verilerini depolamak için Microsoft Windows Meta Dosyasını (WMF) temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect Belgesi (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Elektronik Tablosu (.xls), Excel İkili Dosya Biçimini temsil eder. Bu tür dosyalar, Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel İkili Hesap Tablosu (.xlsb), Excel çalışma kitabı içeriğini belirten bir kayıt ve yapı koleksiyonu olan Excel İkili Dosya Biçimini belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Açık XML Makro Etkin Elektronik Tablo (.xlsm), makroları destekleyen bir Elektronik Tablo dosyası türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Açık XML Elektronik Tablosu (.xlsx), Microsoft tarafından Microsoft Office 2007'nin piyasaya sürülmesiyle tanıtılan, Microsoft Excel belgeleri için iyi bilinen bir biçimdir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel ikili Şablonu (.xlt), Excel Şablonu Dosya Biçimini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML dosya Şablonu (.xltm), Excel Şablon Dosya Biçimini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/xltm) . |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen dosya türleri hakkında daha fazla bilgi.Signature: [GroupDocs.Signature tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* C#: 'de desteklenen biçimler listesinin nasıl alınacağı hakkında daha fazla bilgi[C# kodunda desteklenen dosya biçimleri nasıl elde edilir](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Ayrıca bakınız

* ad alanı [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
