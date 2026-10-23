---
title: "Klasse Signature"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Hauptklasse dar, die den Dokumenten‑Signaturprozess steuert."
type: docs
url: /de/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Stellt die Hauptklasse dar, die den Dokumenten‑Signaturprozess steuert.

Erfahren Sie mehr über die Funktionen von GroupDocs.Signature:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Der Typ Signature stellt die folgenden Member bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Initialisiert eine neue Signature‑Instanz mit einem als Stream bereitgestellten Dokument. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Initialisiert eine neue [`Signature`](/signature/python-net/groupdocs.signature/signature/)‑Instanz mit einem Dokument‑Stream und Ladeoptionen. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Initialisiert eine neue [`Signature`](/signature/python-net/groupdocs.signature/signature/)‑Instanz mit einem durch einen Stream bereitgestellten Dokument und optionalen [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Initialisiert eine neue Instanz von [`Signature`](/signature/python-net/groupdocs.signature/signature/) mit einem Dokument‑Stream, Ladeoptionen und Signatur‑Einstellungen. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Initialisiert eine neue Instanz von [`Signature`](/signature/python-net/groupdocs.signature/signature/) mit einem durch Dateipfad bereitgestellten Dokument. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Initialisiert eine neue Signature‑Instanz mit dem durch Dateipfad bereitgestellten Dokument und Ladeoptionen. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Initialisiert eine neue [`Signature`](/signature/python-net/groupdocs.signature/signature/)‑Instanz mit dem durch einen Dateipfad bereitgestellten Dokument und optionalen [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Initialisiert eine neue Instanz von [`Signature`](/signature/python-net/groupdocs.signature/signature/) mit einem durch Dateipfad bereitgestellten Dokument, Ladeoptionen und Signatur‑Einstellungen. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Löscht die angegebene [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) aus dem Dokument. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Löscht die bereitgestellte Liste von Signaturen aus dem Dokument. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Löscht Signaturen des angegebenen Typs aus dem Dokument. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Löscht Signaturen der angegebenen `SignatureType`-Liste aus dem Dokument. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Löscht eine Signatur anhand ihrer spezifischen Signatur‑Id aus dem Dokument. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Löscht die angegebenen Signaturen aus dem Dokument. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Räumt interne Ressourcen auf, die vom Signaturobjekt verwendet werden. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Erstellt eine Vorschau der Dokumentseiten. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Erstellt eine Signaturvorschau basierend auf den angegebenen SignOptions. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Ruft Informationen über Dokumentseiten ab: deren Größen, maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Sucht nach Signaturen in einem Dokument mithilfe einer Liste von [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Sucht nach Signaturen im Dokument unter Verwendung der bereitgestellten Suchoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Sucht nach angegebenen Signaturtypen im Dokument anhand des `SignatureType`-Werts. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Sucht nach Signaturen im Dokument unter Verwendung aller verfügbaren Suchoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Signiert das Dokument mit [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis in einen Stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Signiert ein Dokument mit [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis in einen Stream unter Verwendung vordefinierter [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Signiert das Dokument mit einer Sammlung von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis in einen Stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Signiert das Dokument mit einer Sammlung von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis in einen Stream unter Verwendung vordefinierter [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Signiert das Dokument mit SignOptions und speichert das Ergebnis im angegebenen Dateipfad. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Signiert das Dokument mit [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis im angegebenen Dateipfad unter Verwendung vordefinierter [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Signiert das Dokument mit einer Sammlung von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis im angegebenen Dateipfad. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Signiert das Dokument mit einer Sammlung von [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) und speichert das Ergebnis im angegebenen Dateipfad unter Verwendung vordefinierter [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Aktualisiert die übergebene Signatur BaseSignature im Dokument. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Aktualisiert übergebene Signaturen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) im Dokument. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Überprüft die Dokumentensignaturen mit den angegebenen VerifyOptions-Daten. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Überprüft die Dokumentensignaturen unter Verwendung der bereitgestellten Verifizierungsoptionen und filtert die Ergebnisse basierend auf dem angegebenen Prädikat. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Überprüft die Dokumentensignaturen mit einer Liste von VerifyOptions-Daten. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Überprüft Dokumentensignaturen mit den bereitgestellten Verifizierungsoptionen und filtert die Ergebnisse mit dem angegebenen Prädikat. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Aufgabenleitfäden, die `Signature` verwenden:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Siehe auch
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
