---
title: "SaveOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Gibt zusätzliche Optionen (wie z. B. ein Passwort) beim Speichern eines Dokuments zum Signieren an."
type: docs
url: /de/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Gibt zusätzliche Optionen (wie z. B. ein Passwort) beim Speichern eines Dokuments zum Signieren an.

Der SaveOptions‑Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | Initialisiert eine neue Instanz der SaveOptions‑Klasse mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | Initialisiert eine neue Instanz der SaveOptions‑Klasse mit dem angegebenen Ausgabetyp und dem Überschreibungs‑Flag. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Das Flag, das bestimmt, ob automatisch eine Erweiterung hinzugefügt wird, wenn sie im Ausgabedateipfad fehlt. Der Standardwert ist False. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Das Flag, das angibt, ob eine vorhandene Datei mit der neuen Ausgabedatei überschrieben werden soll. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Das Passwort, das zum Schutz des gespeicherten signierten Dokuments verwendet wird. Nicht unterstützt für Bilddokumente. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Das Flag, das angibt, ob das Passwort aus [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) beim Speichern des signierten Dokuments als geschützt verwendet werden soll. Der Standardwert ist True. Nicht unterstützt für Bilddokumente. |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
