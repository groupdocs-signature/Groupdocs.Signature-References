---
title: "Klasse DigitalVerifyOptions"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Enthält Optionen zur Überprüfung der digitalen Signatur eines Dokuments."
type: docs
url: /de/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Enthält Optionen zur Überprüfung der digitalen Signatur eines Dokuments.

Mehr erfahren

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

Der Typ DigitalVerifyOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Initialisiert eine DigitalVerifyOptions‑Instanz mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Initialisiert eine DigitalVerifyOptions‑Instanz mit dem angegebenen Dateipfad des digitalen Zertifikats. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Initialisiert eine DigitalVerifyOptions‑Instanz mit dem angegebenen Zertifikat‑Stream. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | Das X509Certificate2‑Zertifikat, das aus dem Zertifikatsdateipfad oder -Stream erhalten wird. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | Der Dateipfad des digitalen Zertifikats. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | Der Stream des digitalen Zertifikats. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | Die Kommentare der zu validierenden digitalen Signatur. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | Der Signaturkontakt zur Validierung. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | Der Ausstellername des zu validierenden Zertifikats. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | Der Signaturort zur Validierung. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | Das Passwort des digitalen Zertifikats, falls erforderlich. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | Der Grund der zu validierenden digitalen Signatur. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | Der Beginn des Datums‑ und Zeitbereichs der zu validierenden digitalen Signatur. Ein None‑Wert wird ignoriert. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | Das Ende des Datums‑ und Zeitbereichs der zu validierenden digitalen Signatur. Ein Null‑Wert wird ignoriert. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | Der Distinguished Name des Zertifikatsinhabers, der zu validieren ist; die Verifizierung prüft, ob der Subject‑Name der Signatur diesen case‑sensitive Wert enthält oder ihm entspricht. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Das Flag gibt an, ob jede Dokumentseite verifiziert werden soll. Standardmäßig ist der Wert True. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Die zusätzlichen Erweiterungen für die Verifizierung alternativer Signaturoptionen. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Das gültige Eigenschafts‑Flag. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Die zu verifizierende Dokumentseitennummer; wenn nicht festgelegt, werden alle Seiten des Dokuments für das erste Vorkommen verifiziert (Mindestwert ist 1). (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Die Seitenoptionen zur Angabe der zu verifizierenden Seiten. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Die Formposition im Dokumentlayout, die zum Verifizieren von Signaturen in Kopf‑/Fußzeilen verwendet wird. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
