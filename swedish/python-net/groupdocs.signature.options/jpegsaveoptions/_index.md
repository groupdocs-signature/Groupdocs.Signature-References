---
title: "JpegSaveOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar JPEG-sparalternativ för bilddokument."
type: docs
url: /sv/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Representerar JPEG-sparalternativ för bilddokument.

JpegSaveOptions-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Initierar JpegSaveOptions med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | Antalet bitar per kanal för en förlustfri JPEG‑bild. Stödda värden är från 2 till 8 bitar per kanal. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | Färgtypen för JPEG‑bilden. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | JPEG‑filkommentaren. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | Komprimeringstypen. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | Bildkvaliteten. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | Avrundningsläget för provet som används för att anpassa ett 8‑bitsvärde till ett n‑bitsvärde av `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Flaggan som bestämmer om en filändelse ska läggas till automatiskt när den saknas i sökvägen för utdatafilen. Standardvärdet är False. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Filformatet för det signerade dokumentet. (ärvd från [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Flaggan som indikerar om en befintlig fil ska skrivas över med den nya utdatafilen. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Lösenordet som används för att skydda det sparade signerade dokumentet. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Flaggan som indikerar om lösenordet från [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) ska användas när det signerade dokumentet sparas som skyddat. Standardvärdet är True. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
