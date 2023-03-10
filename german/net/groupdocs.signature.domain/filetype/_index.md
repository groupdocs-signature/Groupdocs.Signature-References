---
title: FileType
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Stellt den Dateityp dar.
type: docs
weight: 450
url: /de/net/groupdocs.signature.domain/filetype/
---
## FileType class

Stellt den Dateityp dar.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Dateinamensuffix (einschließlich Punkt „.“) zB „.doc“. |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Name des Dateityps, z. B. "Microsoft Word-Dokument". |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Ordnet die Dateierweiterung dem Dateityp zu. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Bestimmt, ob der Strom[`FileType`](../filetype)ist genauso wie angegeben[`FileType`](../filetype) Objekt. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Bestimmt, ob der Strom[`FileType`](../filetype) ist das gleiche wie das angegebene Objekt. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Gibt den Hash-Code für den Strom zurück[`FileType`](../filetype) Objekt. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Ruft unterstützte Dateitypen ab |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Bestimmt, ob zwei[`FileType`](../filetype) Objekte sind gleich. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Bestimmt, ob zwei[`FileType`](../filetype) Objekte sind nicht gleich. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap-Bilddatei (.bmp) wird zum Speichern digitaler Bitmap-Bilder verwendet. Diese Bilder sind grafikadapterunabhängig und werden auch als DIB-Dateiformat (Device Independent Bitmap) bezeichnet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) ist eine Vektorzeichnungsbilddatei, die nativ mit CorelDRAW zum Speichern digitaler Bilder kodiert und komprimiert erstellt wird. Eine solche Zeichnungsdatei enthält Texte, Linien, Formen, Bilder, Farben und Effekte zur vektoriellen Darstellung von Bildinhalten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) ist ein kostenloses, plattformunabhängiges, internationales Standard-Metafile-Format zum Speichern und Austauschen von Vektorgrafiken (2D), Rastergrafiken und Text. CGM verwendet einen objektorientierten Ansatz und viele Funktionsvorkehrungen für die Bilderzeugung. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW Metafile Exchange-Bilddatei (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Comma Separated Values File (.csv) stellt reine Textdateien dar, die Datensätze mit kommagetrennten Werten enthalten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM-Bild (.dcm) stellt ein digitales Bild dar, das medizinische Informationen von Patienten wie MRTs, CT-Scans und Ultraschallbilder speichert. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu-Bild (.djvu) ist ein Grafikdateiformat für gescannte Dokumente und Bücher, insbesondere solche, die eine Kombination aus Text, Zeichnungen, Bildern und Fotos enthalten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word-Dokument (.doc) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsdokumenten im binären Dateiformat erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) ist ein von Microsoft Word 2007 oder höher generiertes Dokument mit der Fähigkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) ist ein bekanntes Format für Microsoft Word-Dokumente. Die Struktur dieses neuen Dokumentformats, das 2007 mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde, wurde von einer reinen Binärdatei in eine Kombination aus XML- und Binärdateien geändert. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word-Dokumentvorlagen (.dot) sind von Microsoft Word erstellte Vorlagendateien mit vorformatierten Einstellungen für die Generierung weiterer DOC- oder DOCX-Dateien. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) sind von Microsoft Word erstellte Vorlagendateien mit vorformatierten Einstellungen für die Generierung weiterer DOCX-Dateien. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) stellt grafische Bilder geräteunabhängig dar. Metadateien von EMF bestehen aus Datensätzen variabler Länge in chronologischer Reihenfolge, die das gespeicherte Bild nach dem Parsen auf jedem Ausgabegerät wiedergeben können. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps) beschreibt ein Encapsulated PostScript-Sprachprogramm, das das Erscheinungsbild einer einzelnen Seite beschreibt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif) ist eine Art stark komprimiertes Bild. Für jedes Bild sind in GIF normalerweise bis zu 8 Bit pro Pixel und bis zu 256 Farben im gesamten Bild zulässig. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG-Bild (.jpeg) ist ein Bildformat, das mit der Methode der verlustbehafteten Komprimierung gespeichert wird. Das Ausgabebild ist als Ergebnis der Komprimierung ein Kompromiss zwischen Speichergröße und Bildqualität. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG-Bild (.jpg) ist ein Bildformat, das mit der Methode der verlustbehafteten Komprimierung gespeichert wird. Das Ausgabebild ist als Ergebnis der Komprimierung ein Kompromiss zwischen Speichergröße und Bildqualität. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument-Grafikdatei (.odg) wird von der Anwendung Draw von Apache OpenOffice verwendet, um Zeichnungselemente als Vektorbild zu speichern. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument-Präsentation (.odp) stellt das Präsentationsdateiformat dar, das von OpenOffice.org im OASISOpen-Standard verwendet wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) steht für OpenDocument Spreadsheet-Dokumentformat, das vom Benutzer bearbeitet werden kann. Daten werden in der ODF-Datei in Zeilen und Spalten gespeichert. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument-Textdokumente (.odt) sind Dokumenttypen, die mit Textverarbeitungsanwendungen erstellt wurden, die auf dem OpenDocument-Textdateiformat basieren. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument-Präsentationsvorlage (.otp) stellt Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument-Tabellenvorlage (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument Document Template (.ott) stellt Vorlagendokumente dar, die von Anwendungen in Übereinstimmung mit dem OpenDocument-Standardformat von OASIS generiert wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Druckerbefehlssprachendokument (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) ist ein Dokumenttyp, der von Adobe in den 1990er Jahren erstellt wurde. Der Zweck dieses Dateiformats bestand darin, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware und Betriebssystem ist. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Scalable Vector Graphics File (.svg) ist eine Scalar Vector Graphics-Datei, die ein XML-basiertes Textformat zur Beschreibung des Aussehens eines Bildes verwendet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) ist ein Rasterbild-Dateiformat, das verlustfreie Komprimierung verwendet. Dieses Dateiformat wurde als Ersatz für das Graphics Interchange Format (GIF) erstellt und unterliegt keinen Urheberrechtsbeschränkungen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint-Vorlage (.pot) stellt Microsoft PowerPoint-Vorlagendateien dar, die von PowerPoint 97-2003-Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) sind Microsoft PowerPoint-Vorlagendateien mit Unterstützung für Makros. POTM-Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zum Erstellen weiterer Präsentationsdateien verwendet werden können. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML-Präsentationsvorlage (.potx) stellt Microsoft PowerPoint-Präsentationsvorlagen dar, die mit Microsoft PowerPoint 2007 und höher erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint-Diashows (.pps) werden mit Microsoft PowerPoint für Diashowzwecke erstellt. Das Lesen und Erstellen von PPS-Dateien wird von Microsoft PowerPoint 97-2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) stellt ein Makro-fähiges Diashow-Dateiformat dar, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML-Diashowdateien (.ppsx) werden mit Microsoft PowerPoint 2007 und höher für Diashowzwecke erstellt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint-Präsentation (.ppt) stellt eine PowerPoint-Datei dar, die aus einer Sammlung von Folien zur Anzeige als Diashow besteht. Es gibt das von Microsoft PowerPoint 97-2003 verwendete binäre Dateiformat an. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation sind Makro-fähige Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder höheren Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML-Präsentation (.pptx) sind Präsentationsdateien, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurden. Anders als die vorherige Version des Präsentationsdateiformats PPT, die binär war, basiert das PPTX-Format auf dem offenen XML-Präsentationsdateiformat von Microsoft PowerPoint. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript-Datei (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop-Dokument (.psd) stellt das native Dateiformat von Adobe Photoshop dar, das für Grafikdesign und -entwicklung verwendet wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) ist eine Methode zur Codierung von formatiertem Text und Grafiken zur Verwendung in Anwendungen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) ist eine Scalar Vector Graphics-Datei, die ein XML-basiertes Textformat zur Beschreibung des Aussehens eines Bildes verwendet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif) stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Es ist in der Lage, Bilevel-, Graustufen-, Palettenfarben- und Vollfarben-Bilddaten in mehreren Farbräumen zu beschreiben. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Es ist in der Lage, Bilevel-, Graustufen-, Palettenfarben- und Vollfarben-Bilddaten in mehreren Farbräumen zu beschreiben. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Tabulatorgetrennte Wertedatei (.tsv) stellt durch Tabulatoren getrennte Daten im Nur-Text-Format dar. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Plain Text File (.txt) stellt ein Textdokument dar, das einfachen Text in Form von Zeilen enthält. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | steht für unbekannten Dateityp. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard-Datei (.vcf) ist ein digitales Dateiformat zum Speichern von Kontaktinformationen. Das Format wird häufig für den Datenaustausch zwischen beliebten Informationsaustauschanwendungen verwendet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) ist ein modernes Raster-Webbild-Dateiformat, das auf verlustfreier und verlustbehafteter Komprimierung basiert. Es bietet die gleiche Bildqualität, während die Bildgröße erheblich reduziert wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) steht für Microsoft Windows Metafile (WMF) zum Speichern von Bilddaten im Vektor- und Bitmap-Format. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect-Dokument (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Spreadsheet (.xls) steht für Excel Binary File Format. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel-Binärtabelle (.xlsb) gibt das Excel-Binärdateiformat an, bei dem es sich um eine Sammlung von Datensätzen und Strukturen handelt, die den Inhalt von Excel-Arbeitsmappen angeben. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) ist eine Art Tabellenkalkulationsdatei, die Makros unterstützt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel-Binärvorlage (.xlt) stellt das Excel-Vorlagendateiformat dar. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML-Dateivorlage (.xltm) stellt das Excel-Vorlagendateiformat dar. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/xltm) . |

### Bemerkungen

**Erfahren Sie mehr**

* Mehr zu den von GroupDocs unterstützten Dateitypen. Signatur: [Von GroupDocs.Signature unterstützte Dokumentformate](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* Weitere Informationen zum Abrufen einer Liste unterstützter Formate in C#: [So erhalten Sie unterstützte Dateiformate in C#-Code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Siehe auch

* namensraum [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
