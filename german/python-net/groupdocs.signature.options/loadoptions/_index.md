---
title: "LoadOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Die Klasse LoadOptions ermöglicht das Angeben zusätzlicher Optionen (wie z. B. ein Passwort) beim Öffnen eines Dokuments zum Signieren."
type: docs
url: /de/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

Die Klasse LoadOptions ermöglicht das Angeben zusätzlicher Optionen (wie z. B. ein Passwort) beim Öffnen eines Dokuments zum Signieren.

Setzen Sie das Attribut `password` auf das Dokumentenpasswort, wenn die Datei verschlüsselt ist.

Der Typ LoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Initialisiert eine neue Instanz der LoadOptions Klasse. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Initialisiert eine neue Instanz der [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) Klasse mit einem angegebenen Dateityp. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | Der Dateityp, der mit den Ladeoptionen verknüpft ist und standardmäßig auf [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/) gesetzt wird. |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | Das Flag, das bestimmt, ob das Dokument externe Ressourcen lädt. Diese Eigenschaft ist veraltet; verwenden Sie stattdessen [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/), das die gegenteilige Bedeutung hat. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | Das Passwort, das zum Öffnen eines geschützten Dokuments und zum Speichern eines signierten Dokuments als geschützt verwendet wird. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | Die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion. Nur für PDF-Dokumente. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | Das Flag, das das Laden externer Ressourcen durch das Dokument verhindert. Der Standardwert ist True; externe Ressourcen werden nicht geladen, außer denen, die mit [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) übereinstimmen. |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | Die Liste von Adressfragmenten externer Ressourcen, die geladen werden, selbst wenn [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) true ist. Der Standardwert ist eine leere Liste. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
