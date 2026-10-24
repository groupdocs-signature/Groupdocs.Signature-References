---
title: "SaveOptions-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Anger ytterligare alternativ (t.ex. lösenord) när ett dokument sparas för signering."
type: docs
url: /sv/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Anger ytterligare alternativ (t.ex. lösenord) när ett dokument sparas för signering.

SaveOptions-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | Initierar en ny instans av SaveOptions-klassen med standardvärden. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | Initierar en ny instans av SaveOptions-klassen med specificerad utmatningstyp och överskrivningsflagga. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Flaggan som bestämmer om en filändelse automatiskt ska läggas till när den saknas i utdatafilens sökväg. Standardvärdet är False. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Flaggan som indikerar om en befintlig fil ska skrivas över med den nya utdatafilen. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Lösenordet som används för att skydda det sparade signerade dokumentet. Stöds inte för bilddokument. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Flaggan som anger om lösenordet från [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) ska användas när det signerade dokumentet sparas som skyddat. Standardvärdet är True. Stöds inte för bilddokument. |

### Se även
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
