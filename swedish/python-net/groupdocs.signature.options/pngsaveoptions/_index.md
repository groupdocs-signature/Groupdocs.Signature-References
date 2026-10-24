---
title: "PngSaveOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "PNG‑sparalternativen för bilddokument."
type: docs
url: /sv/python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

PNG‑sparalternativen för bilddokument.

PngSaveOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | Initierar PngSaveOptions med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | Bitdjupet. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | Typen av `PngColorType`. |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | PNG-bildkomprimeringsnivån i intervallet 0-9, där 9 är maximal kompression och 0 är lagringsläge. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | Filtertypen `PngFilterType` som används under PNG-filens sparprocess. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | Den progressiva flaggan som indikerar om PNG sparas progressivt. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Flaggan som bestämmer om en filändelse ska läggas till automatiskt när den saknas i sökvägen för utdatafilen. Standardvärdet är False. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Filformatet för det signerade dokumentet. (ärvd från [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Flaggan som indikerar om en befintlig fil ska skrivas över med den nya utdatafilen. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Lösenordet som används för att skydda det sparade signerade dokumentet. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Flaggan som indikerar om lösenordet från [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) ska användas när det signerade dokumentet sparas som skyddat. Standardvärdet är True. Stöds inte för bilddokument. (ärvd från [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
