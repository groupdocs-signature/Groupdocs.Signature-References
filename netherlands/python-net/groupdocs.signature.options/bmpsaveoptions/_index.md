---
title: "BmpSaveOptions‑klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt BMP-opslagopties voor beelddocumenten."
type: docs
url: /nl/python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

Vertegenwoordigt BMP-opslagopties voor beelddocumenten.

Het type BmpSaveOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | Initialiseert BmpSaveOptions met standaardwaarden. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | Het aantal bits per pixel van de afbeelding. |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | De compressie. Zie `BitmapCompression`. |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | De horizontale resolutie. Merk op dat door afronding de resulterende resolutie iets kan afwijken van de ingestelde waarde. |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | De verticale resolutie; merk op dat door afronding de resulterende resolutie iets kan afwijken van de ingestelde waarde. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | De vlag die bepaalt of er automatisch een extensie wordt toegevoegd wanneer deze ontbreekt in het uitvoerbestandspad. Standaardwaarde is False. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Het bestandsformaat van het ondertekende document. (geërfd van [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | De vlag die aangeeft of een bestaand bestand moet worden overschreven met het nieuwe uitvoerbestand. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Het wachtwoord dat wordt gebruikt om het opgeslagen ondertekende document te beveiligen. Niet ondersteund voor afbeeldingsdocumenten. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | De vlag die aangeeft of het wachtwoord van [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) moet worden gebruikt bij het opslaan van het ondertekende document als beschermd. De standaardwaarde is True. Niet ondersteund voor afbeeldingsdocumenten. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
