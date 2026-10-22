---
title: "FileType"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Representerar filtyp."
type: docs
weight: 610
url: /sv/net/groupdocs.signature.domain/filetype/
---
## FileType class

Representerar filtyp.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Filnamnsuffix (inklusive punkten ".") t.ex. ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Filtypnamn t.ex. "Microsoft Word Document". |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Mappar filändelse till filtyp. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Bestämmer om den aktuella [`FileType`](../filetype) är densamma som det angivna [`FileType`](../filetype)-objektet. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Bestämmer om den aktuella [`FileType`](../filetype) är densamma som det angivna objektet. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Returnerar hashkoden för det aktuella [`FileType`](../filetype)-objektet. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Hämtar stödda filtyper |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Bestämmer om två [`FileType`](../filetype)-objekt är desamma. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Bestämmer om två [`FileType`](../filetype)-objekt inte är desamma. |

## Fields

| Namn | Beskrivning |
| --- | --- |
| static readonly [APNG](../../groupdocs.signature.domain/filetype/apng) | Animated Portable Network Graphics (.png) är ett rasterbildformat som använder förlustfri kompression. Det utvecklades som en utökning av PNG för att stödja animation, och fungerar som ett alternativ till GIF-formatet utan upphovsrättsliga begränsningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/apng). |
| static readonly [AZW3](../../groupdocs.signature.domain/filetype/azw3) | WordPerfect-dokument (.wpd) |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap Image File (.bmp) används för att lagra bitmapdigitala bilder. Dessa bilder är oberoende av grafikadapter och kallas också för device independent bitmap (DIB)-filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/bmp). |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) är en vektorritningsfil som ursprungligen skapas med CorelDRAW för lagring av kodade och komprimerade digitala bilder. En sådan ritningsfil innehåller text, linjer, former, bilder, färger och effekter för vektorrepräsentation av bildinnehåll. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/cdr). |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) är ett fritt, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. CGM använder ett objektorienterat tillvägagångssätt och många funktionsmöjligheter för bildproduktion. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/cgm). |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW Metafile Exchange Image File (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Comma Separated Values File (.csv) representerar vanliga textfiler som innehåller datarader med kommaseparerade värden. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM Image (.dcm) representerar en digital bild som lagrar medicinsk information om patienter, såsom MR, CT-skanningar och ultraljudsbilder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/dcm). |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu) är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/djvu). |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word Document (.doc) representerar dokument som genereras av Microsoft Word eller andra ordbehandlingsprogram i binärt filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) är ett Microsoft Word 2007 eller senare genererat dokument med möjlighet att köra makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML-dokument (.docx) är ett välkänt format för Microsoft Word-dokument. Introducerat från 2007 med lanseringen av Microsoft Office 2007, ändrades strukturen för detta nya dokumentformat från ren binär till en kombination av XML- och binära filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word-dokumentmall (.dot) är mallfiler som skapas av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML-makroaktiverad dokumentmall (.dotm) representerar en mallfil som skapats med Microsoft Word 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML-dokumentmall (.dotx) är mallfiler som skapas av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) representerar grafiska bilder enhetsoberoende. Metafiler i EMF består av variabelt långa poster i kronologisk ordning som kan återge den lagrade bilden efter parsning på vilken utskriftsenhet som helst. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/emf). |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript-fil (.eps) beskriver ett Encapsulated PostScript-språkprogram som beskriver utseendet på en enda sida. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/eps). |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format-fil (.gif) är en typ av starkt komprimerad bild. För varje bild tillåter GIF vanligtvis upp till 8 bitar per pixel och upp till 256 färger är tillåtna i bilden. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/gif). |
| static readonly [GZip](../../groupdocs.signature.domain/filetype/gzip) | GZip-komprimerat arkiv (.gz) komprimerar filer med en hög komprimeringsgrad. Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/gz). |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG-bild (.jpeg) är en typ av bildformat som sparas med en förlustkomprimeringsmetod. Den resulterande bilden, som ett resultat av komprimeringen, är en avvägning mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG-bild (.jpg) är en typ av bildformat som sparas med en förlustkomprimeringsmetod. Den resulterande bilden, som ett resultat av komprimeringen, är en avvägning mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jpeg). |
| static readonly [LZip](../../groupdocs.signature.domain/filetype/lzip) | LZip-komprimerat arkiv (.lz) komprimerar filer med en hög komprimeringsgrad. Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/lz). |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument-grafikfil (.odg) används av Apache OpenOffice Draw-applikationen för att lagra ritningselement som en vektorbild. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/odg). |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument-presentation (.odp) representerar presentationsfilformat som används av OpenOffice.org i OASISOpen-standarden. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) står för OpenDocument Spreadsheet-dokumentformat som är redigerbart av användaren. Data lagras i ODF-filen i rader och kolumner. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument Text Document (.odt) är en typ av dokument som skapas med ordbehandlingsprogram som är baserade på OpenDocument Text-filformatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument Presentation Template (.otp) representerar presentationsmallfiler som skapas av program i OASIS OpenDocument-standardformatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/otp). |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument Spreadsheet-mall (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument Document Template (.ott) representerar mall-dokument som genereras av program i enlighet med OASIS OpenDocument-standardformatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Printer Command Language-dokument (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) är en typ av dokument som skapades av Adobe på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. Läs mer om detta filformat [här](https://wiki.fileformat.com/view/pdf). |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Personal Information Exchange (.pfx)-fil är ett lösenordsskyddat certifikat som ofta används för kodsignering av din applikation. Läs mer om detta filformat [här](https://fileinfo.com/extension/pfx). |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) är en typ av rasterbildfilformat som använder förlustfri komprimering. Detta filformat skapades som en ersättning för Graphics Interchange Format (GIF) och har inga upphovsrättsliga begränsningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/png). |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint Template (.pot) representerar Microsoft PowerPoint-mallfiler som skapades av PowerPoint 97-2003-versionerna. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pot). |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) är Microsoft PowerPoint-mallfiler med stöd för makron. POTM-filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potm). |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) representerar Microsoft PowerPoint-mallpresentationer som skapas med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potx). |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint Slide Show (.pps) skapas med Microsoft PowerPoint för bildspelsändamål. PPS-filer kan läsas och skapas av Microsoft PowerPoint 97-2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Makroaktiverad bild (.ppsm) representerar makroaktiverat bildspelsfilformat skapat med Microsoft PowerPoint 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML Bildspel (.ppsx) filer skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint-presentation (.ppt) representerar en PowerPoint‑fil som består av en samling bilder för visning som bildspel. Den specificerar det binära filformatet som används av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Makroaktiverad presentation är makroaktiverade presentationsfiler som skapas med Microsoft PowerPoint 2007 eller senare versioner. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML-presentation (.pptx) är presentationsfiler skapade med det populära Microsoft PowerPoint‑programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX‑formatet baserat på Microsoft PowerPoints öppna XML‑presentationsfilformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript‑fil (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop-dokument (.psd) representerar Adobe Photoshops inhemska filformat som används för grafisk design och utveckling. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/psd). |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format‑fil (.rtf) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [SevenZip](../../groupdocs.signature.domain/filetype/sevenzip) | Högkomprimerat arkiv (.7z) komprimerar filer och mappar med en hög komprimeringsgrad. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/7z). |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics‑fil (.svg) är en skalär vektorgrafikfil som använder ett XML‑baserat textformat för att beskriva en bilds utseende. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [TAR](../../groupdocs.signature.domain/filetype/tar) | Unix‑baserat verktyg för att samla en eller flera filer (.tar) är ett arkiv som kan innehålla en eller flera filer eller kataloger. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/tar/). |
| static readonly [TGA](../../groupdocs.signature.domain/filetype/tga) | Truevision TGA (.tga), även känd som TARGA, är ett rasterbildfilformat utvecklat av Truevision Inc. Det stöder olika färgdjup och valfri RLE‑komprimering. TGA‑filer används ofta i videospel, animationspipelines och grafikprogram för högkvalitativ bildrendering med valfritt alfakanalstöd. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tga). |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. Den kan beskriva tvånivå-, gråskala-, palett‑färg‑ och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff). |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. Det kan beskriva tvånivå-, gråskala-, palettfärg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff). |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Tab Separated Values File (.tsv) representerar data separerade med tabbar i vanligt textformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Plain Text File (.txt) representerar ett textdokument som innehåller vanlig text i form av rader. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Representerar okänd filtyp. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard File (.vcf) är ett digitalt filformat för lagring av kontaktinformation. Formatet används i stor utsträckning för datautbyte mellan populära informationsutbytesprogram. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/vcf). |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) är ett modernt rasterwebbbildfilformat som är baserat på förlustfri och förlustkomprimering. Det ger samma bildkvalitet samtidigt som det avsevärt minskar bildstorleken. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/webp). |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) representerar Microsoft Windows Metafile (WMF) för lagring av både vektor- och bitmapformatbilder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/wmf). |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect-dokument (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Spreadsheet (.xls) representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) specificerar Excel Binary File Format, som är en samling poster och strukturer som beskriver Excel-arbetsbokens innehåll. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) är en typ av kalkylbladsfiler som stödjer makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel binary Template (.xlt) representerar Excel Template File Format. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML file Template (.xltm) representerar Excel Template File Format. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [ZIP](../../groupdocs.signature.domain/filetype/zip) | Document ZIP archive (.zip) är ett arkivfilformat som stödjer förlustfri datakomprimering. Kan innehålla en eller flera filer eller kataloger. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/zip/). |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* More about how to get supported formats list in C#: [How to get supported file formats in C# code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Se även

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
