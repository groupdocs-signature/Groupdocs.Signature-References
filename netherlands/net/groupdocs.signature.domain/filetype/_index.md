---
title: FileType
second_title: GroupDocs.Signature voor .NET API-referentie
description: Vertegenwoordigt bestandstype.
type: docs
weight: 450
url: /nl/net/groupdocs.signature.domain/filetype/
---
## FileType class

Vertegenwoordigt bestandstype.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Achtervoegsel bestandsnaam (inclusief de punt ".") bijv. ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Bestandstypenaam bijv. "Microsoft Word-document". |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Wijst bestandsextensie toe aan bestandstype. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Bepaalt of de stroom[`FileType`](../filetype)is hetzelfde als gespecificeerd[`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Bepaalt of de stroom[`FileType`](../filetype) is hetzelfde als gespecificeerd object. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Retourneert de hash-code voor de huidige[`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Haalt ondersteunde bestandstypen op |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Bepaalt of twee[`FileType`](../filetype) objecten zijn hetzelfde. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Bepaalt of twee[`FileType`](../filetype) objecten zijn niet hetzelfde. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap Image File (.bmp) wordt gebruikt om digitale bitmapafbeeldingen op te slaan. Deze afbeeldingen zijn onafhankelijk van de grafische adapter en worden ook wel apparaatonafhankelijke bitmapbestandsindeling (DIB) genoemd. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) is een vectorafbeeldingsbestand dat oorspronkelijk is gemaakt met CorelDRAW voor het opslaan van gecodeerde en gecomprimeerde digitale afbeeldingen. Zo'n tekenbestand bevat tekst, lijnen, vormen, afbeeldingen, kleuren en effecten voor vectorweergave van beeldinhoud. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) is een gratis, platformonafhankelijk, internationaal standaard metabestandsformaat voor het opslaan en uitwisselen van vectorafbeeldingen (2D), rasterafbeeldingen en tekst. CGM maakt gebruik van objectgeoriënteerde benadering en veel functievoorzieningen voor beeldproductie. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW uitgewisseld metabestand afbeeldingsbestand (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Bestand met door komma's gescheiden waarden (.csv) vertegenwoordigt platte tekstbestanden die gegevensrecords bevatten met door komma's gescheiden waarden. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM Image (.dcm) vertegenwoordigt een digitaal beeld dat medische informatie van patiënten opslaat, zoals MRI's, CT-scans en echografiebeelden. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu) is een grafische bestandsindeling die bedoeld is voor gescande documenten en boeken, met name degene die de combinatie van tekst, tekeningen, afbeeldingen en foto's bevatten. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word-document (.doc) vertegenwoordigt documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binaire bestandsindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) is een Microsoft Word 2007 of hoger gegenereerd document met de mogelijkheid om macro's uit te voeren. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML-document (.docx) is een bekend formaat voor Microsoft Word-documenten. Geïntroduceerd vanaf 2007 met de release van Microsoft Office 2007, werd de structuur van dit nieuwe documentformaat gewijzigd van gewoon binair naar een combinatie van XML en binaire bestanden. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word-documentsjabloon (.dot) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf geformatteerde instellingen voor het genereren van verdere DOC- of DOCX-bestanden. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) vertegenwoordigt een sjabloonbestand gemaakt met Microsoft Word 2007 of hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML-documentsjabloon (.dotx) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf geformatteerde instellingen voor het genereren van verdere DOCX-bestanden. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Verbeterd Windows-metabestand (.emf) vertegenwoordigt grafische afbeeldingen apparaatonafhankelijk. Metabestanden van EMF bestaan uit records met variabele lengte in chronologische volgorde die de opgeslagen afbeelding kunnen weergeven na parseren op elk uitvoerapparaat. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps) beschrijft een Encapsulated PostScript-taalprogramma dat het uiterlijk van een enkele pagina beschrijft. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif) is een type sterk gecomprimeerde afbeelding. Voor elke afbeelding staat GIF doorgaans maximaal 8 bits per pixel toe en maximaal 256 kleuren zijn toegestaan in de afbeelding. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG-afbeelding (.jpeg) is een type afbeeldingsindeling die wordt opgeslagen met behulp van de methode van compressie met verlies. Het uitvoerbeeld, als resultaat van compressie, is een wisselwerking tussen opslaggrootte en beeldkwaliteit. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG-afbeelding (.jpg) is een type afbeeldingsindeling die wordt opgeslagen met behulp van de methode van compressie met verlies. Het uitvoerbeeld, als resultaat van compressie, is een wisselwerking tussen opslaggrootte en beeldkwaliteit. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument Graphic File (.odg) wordt gebruikt door de Draw-toepassing van Apache OpenOffice om tekenelementen op te slaan als een vectorafbeelding. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp) vertegenwoordigt het presentatiebestandsformaat dat wordt gebruikt door OpenOffice.org in de OASISOpen-standaard. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) staat voor OpenDocument Spreadsheet Documentformaat dat door de gebruiker kan worden bewerkt. Gegevens worden in het ODF-bestand opgeslagen in rijen en kolommen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument-tekstdocumenten (.odt) zijn type documenten die zijn gemaakt met tekstverwerkingsprogramma's die zijn gebaseerd op de OpenDocument-tekstbestandsindeling. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument-presentatiesjabloon (.otp) vertegenwoordigt presentatiesjabloonbestanden gemaakt door toepassingen in de OASIS OpenDocument-standaardindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument Spreadsheet-sjabloon (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument-documentsjabloon (.ott) vertegenwoordigt sjabloondocumenten die zijn gegenereerd door toepassingen in overeenstemming met het OpenDocument-standaardformaat van OASIS. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Printeropdrachttaaldocument (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) is een type document dat in de jaren negentig door Adobe is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van applicatiesoftware, hardware en besturingssysteem. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Scalable Vector Graphics File (.svg) is een Scalar Vector Graphics-bestand dat op XML gebaseerd tekstformaat gebruikt om het uiterlijk van een afbeelding te beschrijven. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) is een type rasterafbeeldingsbestandsindeling die lossless compressie gebruikt. Deze bestandsindeling is gemaakt ter vervanging van Graphics Interchange Format (GIF) en kent geen copyrightbeperkingen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint-sjabloon (.pot) vertegenwoordigt Microsoft PowerPoint-sjabloonbestanden gemaakt door PowerPoint 97-2003-versies. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-enabled presentatiesjabloon (.potm) zijn Microsoft PowerPoint-sjabloonbestanden met ondersteuning voor macro's. POTM-bestanden worden gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om meer presentatiebestanden te maken. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML-presentatiesjabloon (.potx) vertegenwoordigt Microsoft PowerPoint-sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint-diavoorstellingen (.pps) worden gemaakt met behulp van Microsoft PowerPoint voor diavoorstellingen. Het lezen en maken van PPS-bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) staat voor Macro-enabled Slide Show-bestandsindeling gemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML-diavoorstellingsbestanden (.ppsx) worden gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint-presentatie (.ppt) vertegenwoordigt een PowerPoint-bestand dat bestaat uit een verzameling dia's voor weergave als SlideShow. Het specificeert de binaire bestandsindeling die wordt gebruikt door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML-presentatie met macro's zijn presentatiebestanden met macro's die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML-presentatie (.pptx) zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint-toepassing. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX-formaat gebaseerd op het Microsoft PowerPoint open XML-presentatiebestandsformaat. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript-bestand (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd) vertegenwoordigt de oorspronkelijke bestandsindeling van Adobe Photoshop die wordt gebruikt voor het ontwerpen en ontwikkelen van grafische afbeeldingen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) vertegenwoordigt een methode voor het coderen van opgemaakte tekst en afbeeldingen voor gebruik in toepassingen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) is een Scalar Vector Graphics-bestand dat op XML gebaseerd tekstformaat gebruikt om het uiterlijk van een afbeelding te beschrijven. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif) vertegenwoordigt rasterafbeeldingen die bedoeld zijn voor gebruik op verschillende apparaten die voldoen aan deze standaard voor bestandsindelingen. Het is in staat bilevel-, grijswaarden-, paletkleur- en full-color afbeeldingsgegevens in verschillende kleurruimten te beschrijven. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) vertegenwoordigt rasterafbeeldingen die bedoeld zijn voor gebruik op verschillende apparaten die voldoen aan deze standaard voor bestandsindelingen. Het is in staat bilevel-, grijswaarden-, paletkleur- en full-color afbeeldingsgegevens in verschillende kleurruimten te beschrijven. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Bestand met door tabs gescheiden waarden (.tsv) vertegenwoordigt gegevens gescheiden door tabs in tekst zonder opmaak. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Platte tekstbestand (.txt) vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Vertegenwoordigt onbekend bestandstype. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard File (.vcf) is een digitaal bestandsformaat voor het opslaan van contactgegevens. Het formaat wordt veel gebruikt voor gegevensuitwisseling tussen populaire toepassingen voor informatie-uitwisseling. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) is een moderne indeling voor rasterwebafbeeldingen die is gebaseerd op lossless en lossy compressie. Het biedt dezelfde beeldkwaliteit terwijl het beeldformaat aanzienlijk wordt verkleind. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) vertegenwoordigt Microsoft Windows Metafile (WMF) voor het opslaan van zowel vector- als bitmap-afbeeldingsgegevens. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect-document (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel-spreadsheet (.xls) vertegenwoordigt de binaire bestandsindeling van Excel. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel en andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) specificeert de Excel Binary File Format, een verzameling records en structuren die de inhoud van de Excel-werkmap specificeren. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is een type Spreadsheet-bestanden dat macro's ondersteunt. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) is een bekende indeling voor Microsoft Excel-documenten die door Microsoft is geïntroduceerd met de release van Microsoft Office 2007. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Binaire Excel-sjabloon (.xlt) vertegenwoordigt Excel-sjabloonbestandsindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML-bestandssjabloon (.xltm) staat voor Excel-sjabloonbestandsindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/xltm) . |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs. Handtekening: [Documentindelingen ondersteund door GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* Meer informatie over het verkrijgen van een lijst met ondersteunde indelingen in C#: [Ondersteunde bestandsindelingen verkrijgen in C#-code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Zie ook

* naamruimte [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
