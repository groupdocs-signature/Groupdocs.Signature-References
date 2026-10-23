---
title: "Klasse CertificateVerifyOptions"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Enthält Optionen zur Überprüfung von Zertifikatsdokumenten."
type: docs
url: /de/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Enthält Optionen zur Überprüfung von Zertifikatsdokumenten.

Mehr erfahren

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

Der CertificateVerifyOptions-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Initialisiert eine neue Instanz von TextVerifyOptions mit Standardwerten. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Initialisiert eine neue CertificateVerifyOptions-Instanz mit dem zu prüfenden Betreff. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | Die Eigenschaft gibt an, ob das Zertifikat basierend auf dem Validierungsergebnis abgelaufen ist. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | Der zu prüfende Zertifikataussteller. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | Der für die Verifizierung verwendete Textabgleichstyp. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | Der Verifizierungsprozess sollte eine X.509-Kettenvalidierung unter Verwendung der Basisvalidierungsrichtlinie bereitstellen. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | Die zu prüfende Zertifikatsseriennummer. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | Der zu prüfende Zertifikatsbetreff. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | Der zu prüfende Zertifikatsfingerabdruck. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Das Flag gibt an, ob jede Dokumentseite verifiziert werden soll. Standardmäßig ist der Wert True. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Die zusätzlichen Erweiterungen für die Verifizierung alternativer Signaturoptionen. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Das gültige Eigenschafts‑Flag. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Die zu verifizierende Dokumentseitennummer; wenn nicht festgelegt, werden alle Seiten des Dokuments für das erste Vorkommen verifiziert (Mindestwert ist 1). (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Die Seitenoptionen zur Angabe der zu verifizierenden Seiten. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Die Formposition im Dokumentlayout, die zum Verifizieren von Signaturen in Kopf‑/Fußzeilen verwendet wird. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
