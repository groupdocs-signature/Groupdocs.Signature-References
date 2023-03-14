---
title: FileType
second_title: GroupDocs.Signature för .NET API-referens
description: Representerar filtyp.
type: docs
weight: 450
url: /sv/net/groupdocs.signature.domain/filetype/
---
## FileType class

Representerar filtyp.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Filnamnssuffix (inklusive perioden ".") t.ex. ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Filtypsnamn t.ex. "Microsoft Word Document". |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Mappar filtillägget till filtyp. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Bestämmer om strömmen[`FileType`](../filetype)är samma som specificerats[`FileType`](../filetype) objekt. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Bestämmer om strömmen[`FileType`](../filetype) är samma som specificerat objekt. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Returnerar hashkoden för den aktuella[`FileType`](../filetype) objekt. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Hämtar filtyper som stöds |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Bestämmer om två[`FileType`](../filetype) objekten är desamma. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Bestämmer om två[`FileType`](../filetype) objekt är inte samma sak. |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmappsbildfil (.bmp) används för att lagra digitala bitmappsbilder. Dessa bilder är oberoende av grafikkort och kallas även enhetsoberoende bitmapps (DIB) filformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) är en vektorritningsbildfil som skapas med CorelDRAW för att lagra digitala bilder kodade och komprimerade. En sådan ritfil innehåller text, linjer, former, bilder, färger och effekter för vektorrepresentation av bildinnehåll. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) är ett gratis, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. CGM använder ett objektorienterat tillvägagångssätt och många funktioner för bildproduktion. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW Metafile Exchange Image File (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Comma Separated Values File (.csv) representerar vanliga textfiler som innehåller dataposter med kommaseparerade värden. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM-bild (.dcm) representerar en digital bild som lagrar medicinsk information om patienter som MRI, datortomografi och ultraljudsbilder. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu) är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word-dokument (.doc) representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) är ett Microsoft Word 2007 eller högre genererat dokument med förmågan att köra makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) är ett välkänt format för Microsoft Word-dokument. Introducerad från 2007 med lanseringen av Microsoft Office 2007, ändrades strukturen för detta nya dokumentformat från vanligt binärt till en kombination av XML och binära filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word Document Template (.dot) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) representerar mallfil skapad med Microsoft Word 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) representerar grafiska bilder enhetsoberoende. Metafiler av EMF består av poster med variabel längd i kronologisk ordning som kan återge den lagrade bilden efter analys på valfri utenhet. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps) beskriver ett Encapsulated PostScript-språkprogram som beskriver utseendet på en enskild sida. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif) är en typ av mycket komprimerad bild. För varje bild tillåter GIF vanligtvis upp till 8 bitar per pixel och upp till 256 färger är tillåtna över hela bilden. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG-bild (.jpeg) är en typ av bildformat som sparas med metoden för förlustkomprimering. Utdatabilden, som ett resultat av komprimering, är en kompromiss mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG-bild (.jpg) är en typ av bildformat som sparas med metoden för förlustkomprimering. Utdatabilden, som ett resultat av komprimering, är en kompromiss mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument Graphic File (.odg) används av Apache OpenOffices Draw-applikation för att lagra ritelement som en vektorbild. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp) representerar presentationsfilformat som används av OpenOffice.org i OASISOpen-standarden. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument Text Document (.odt) är typ av dokument skapade med ordbehandlingsprogram som är baserade på OpenDocument Text File-format. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument Presentation Template (.otp) representerar presentationsmallfiler skapade av applikationer i OASIS OpenDocument standardformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument Spreadsheet Mall (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument Document Template (.ott) representerar malldokument som genereras av applikationer i enlighet med OASIS OpenDocument-standardformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Skrivarkommandospråkdokument (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) är en typ av dokument som skapades av Adobe redan på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av applikationsprogramvara, hårdvara samt operativsystem. Läs mer om detta filformat[här](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Scalable Vector Graphics File (.svg) är en Scalar Vector Graphics-fil som använder XML-baserat textformat för att beskriva utseendet på en bild. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) är en typ av rasterbildsfilformat som använder förlustfri komprimering. Det här filformatet skapades som en ersättning för Graphics Interchange Format (GIF) och har inga upphovsrättsliga begränsningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint-mall (.pot) representerar Microsoft PowerPoint-mallfiler skapade av PowerPoint 97-2003-versioner. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Makro-aktiverad presentationsmall (.potm) är Microsoft PowerPoint-mallfiler med stöd för makron. POTM-filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML-presentationsmall (.potx) representerar Microsoft PowerPoint-mallpresentationer som skapats med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint-bildspel (.pps) skapas med Microsoft PowerPoint för bildspel. PPS-filläsning och skapande stöds av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) representerar Macro-enabled Slide Show-filformat skapat med Microsoft PowerPoint 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML Slide Show-filer (.ppsx) skapas med Microsoft PowerPoint 2007 och senare för Slide Show-ändamål. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint-presentation (.ppt) representerar en PowerPoint-fil som består av en samling bilder för visning som bildspel. Den anger det binära filformatet som används av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation är makroaktiverade presentationsfiler som skapas med Microsoft PowerPoint 2007 eller senare versioner. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) är presentationsfiler skapade med populära Microsoft PowerPoint-applikationer. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX-formatet baserat på Microsoft PowerPoints öppna XML-presentationsfilformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript-fil (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd) representerar Adobe Photoshops ursprungliga filformat som används för grafisk design och utveckling. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) är en Scalar Vector Graphics-fil som använder XML-baserat textformat för att beskriva utseendet på en bild. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Taggad bildfil (.tif) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som överensstämmer med denna filformatstandard. Den kan beskriva bilevel-, gråskala-, palett-färg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som överensstämmer med denna filformatstandard. Den kan beskriva bilevel-, gråskala-, palett-färg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Tab Separated Values File (.tsv) representerar data separerade med flikar i vanligt textformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Vanlig textfil (.txt) representerar ett textdokument som innehåller ren text i form av rader. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Representerar okänd filtyp. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard-fil (.vcf) är ett digitalt filformat för att lagra kontaktinformation. Formatet används ofta för datautbyte bland populära program för informationsutbyte. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) är ett modernt rasterwebbbildfilformat som är baserat på förlustfri och förlustfri komprimering. Den ger samma bildkvalitet samtidigt som den minskar bildstorleken avsevärt. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) representerar Microsoft Windows Metafile (WMF) för lagring av vektor- och bitmappsbilddata. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect Document (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel-kalkylblad (.xls) representerar det binära filformatet för Excel. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel binära kalkylblad (.xlsb) anger det binära filformatet för Excel, som är en samling poster och strukturer som anger innehåll i Excel-arbetsboken. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) är en typ av kalkylbladsfiler som stöder makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML-kalkylblad (.xlsx) är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft i och med lanseringen av Microsoft Office 2007. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Binär Excel-mall (.xlt) representerar Excel-mallfilformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML-filmall (.xltm) representerar Excel-mallfilformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xltm) . |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Signatur: [Dokumentformat som stöds av GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* Mer om hur du får en lista över format som stöds i C#: [Hur man får filformat som stöds i C#-kod](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Se även

* namnutrymme [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
