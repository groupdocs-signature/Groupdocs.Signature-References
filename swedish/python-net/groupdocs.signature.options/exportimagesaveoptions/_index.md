---
title: "ExportImageSaveOptions klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar sparalternativ för att exportera dokument till bild."
type: docs
url: /sv/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Representerar sparalternativ för att exportera dokument till bild.

Den ExportImageSaveOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | Initierar en ny instans av ExportAsImageSaveOptions-klass med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Initierar en ny instans av ExportAsImageSaveOptions med det angivna filformatet. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | Bildraminställningarna. Som standard är detta värde inte angivet. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | Flaggan för att exportera varje sida. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | Antalet kolumner för exporterade bilder. Använd den här egenskapen om du behöver placera bilder i en rad. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | Dokumentsidans nummer för export (minsta värde är 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | Alternativen för att ange vilka sidor som ska signeras. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | Dokumentsidorna placeras på olika ramar i en TIFF-bild. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Flaggan som bestämmer om en filändelse ska läggas till automatiskt när den saknas i sökvägen för utdatafilen. Standardvärdet är False. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Filformatet för det signerade dokumentet. (ärvd från [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Flaggan som indikerar om en befintlig fil ska skrivas över med den nya utdatafilen. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Lösenordet som används för att skydda det sparade signerade dokumentet. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Flaggan som indikerar om lösenordet från [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) ska användas när det signerade dokumentet sparas som skyddat. Standardvärdet är True. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
