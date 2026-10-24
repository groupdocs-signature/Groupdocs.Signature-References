---
title: "ExportImageSaveOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt opslagopties voor het exporteren van documenten naar afbeelding."
type: docs
url: /nl/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Vertegenwoordigt opslagopties voor het exporteren van documenten naar afbeelding.

Het ExportImageSaveOptions type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | Initialiseert een nieuw exemplaar van de ExportAsImageSaveOptions klasse met standaardwaarden. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Initialiseert een nieuw exemplaar van ExportAsImageSaveOptions met het opgegeven bestandsformaat. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | De instellingen voor de afbeeldingsrand. Standaard is deze waarde niet ingesteld. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | De vlag om elke pagina te exporteren. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | Het aantal kolommen voor geëxporteerde afbeeldingen. Gebruik deze eigenschap als u afbeeldingen in een rij wilt plaatsen. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | Het paginanummer van het document voor export (minimumwaarde is 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | De opties om pagina's op te geven die moeten worden ondertekend. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | De documentpagina's worden op verschillende frames in een TIFF-afbeelding geplaatst. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | De vlag die bepaalt of er automatisch een extensie wordt toegevoegd wanneer deze ontbreekt in het uitvoerbestandspad. Standaardwaarde is False. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Het bestandsformaat van het ondertekende document. (geërfd van [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | De vlag die aangeeft of een bestaand bestand moet worden overschreven met het nieuwe uitvoerbestand. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Het wachtwoord dat wordt gebruikt om het opgeslagen ondertekende document te beveiligen. Niet ondersteund voor afbeeldingsdocumenten. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | De vlag die aangeeft of het wachtwoord van [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) moet worden gebruikt bij het opslaan van het ondertekende document als beschermd. De standaardwaarde is True. Niet ondersteund voor afbeeldingsdocumenten. (geërfd van [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
