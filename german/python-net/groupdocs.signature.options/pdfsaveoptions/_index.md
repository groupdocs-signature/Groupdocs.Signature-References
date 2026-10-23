---
title: "PdfSaveOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Speicheroptionen für PDF-Dokumente dar."
type: docs
url: /de/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

Stellt Speicheroptionen für PDF-Dokumente dar.

Der Typ PdfSaveOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | Initialisiert eine neue Instanz von PdfSaveOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | Initialisiert eine neue Instanz von PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | Initialisiert eine neue Instanz von PdfSaveOptions mit einem Überschreibungs-Flag. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | Initialisiert eine neue Instanz von PdfSaveOptions mit dem angegebenen Ausgabe-Dateiformat und Überschreibungs-Flag. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | Das Dateiformat des signierten Dokuments. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | Das Berechtigungspasswort (das primäre Passwort), das zum Ändern der Berechtigungseinstellungen erforderlich ist. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Das Flag bestimmt, ob automatisch eine Erweiterung hinzugefügt wird, wenn sie im Ausgabepfad fehlt. Standardwert ist False. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Das Flag gibt an, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Das zum Schutz des gespeicherten signierten Dokuments verwendete Passwort. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Das Flag gibt an, ob das Passwort aus [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) beim Speichern des signierten Dokuments als geschützt verwendet werden soll. Der Standardwert ist True. Nicht unterstützt für Bilddokumente. (geerbt von [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
