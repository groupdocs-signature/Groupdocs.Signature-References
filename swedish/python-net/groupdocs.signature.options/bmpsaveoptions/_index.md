---
title: "Klassen BmpSaveOptions"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar BMP-sparalternativ för bilddokument."
type: docs
url: /sv/python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

Representerar BMP-sparalternativ för bilddokument.

Typen BmpSaveOptions exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | Initierar BmpSaveOptions med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | Bildens bitar per pixel-antal. |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | Komprimeringen. Se `BitmapCompression`. |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från det angivna värdet. |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | Den vertikala upplösningen; observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från det angivna värdet. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Flaggan som bestämmer om en filändelse ska läggas till automatiskt när den saknas i sökvägen för utdatafilen. Standardvärdet är False. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Filformatet för det signerade dokumentet. (ärvd från [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Flaggan som indikerar om en befintlig fil ska skrivas över med den nya utdatafilen. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Lösenordet som används för att skydda det sparade signerade dokumentet. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Flaggan som indikerar om lösenordet från [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) ska användas när det signerade dokumentet sparas som skyddat. Standardvärdet är True. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
