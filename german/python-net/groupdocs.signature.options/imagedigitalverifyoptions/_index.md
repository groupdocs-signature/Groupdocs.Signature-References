---
title: "ImageDigitalVerifyOptions Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Enthält Optionen zur Überprüfung digitaler Signaturen in Rasterbildern."
type: docs
url: /de/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Enthält Optionen zur Überprüfung digitaler Signaturen in Rasterbildern.

Der Typ ImageDigitalVerifyOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Initialisiert eine neue Instanz der ImageDigitalVerifyOptions-Klasse zum Verifizieren digitaler (Steganografie-) Signaturen in Rasterbildern. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | Die von AnalyzePercentageDigitalSignature zurückgegebene Wahrscheinlichkeit (0‑100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | Der Erkennungs‑Schwellenwert in Prozent für die partielle Extraktion (0‑100). Standardwert ist 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | Das Passwort, das zum Einbetten der Signatur verwendet wurde. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | Die Eigenschaft bestimmt, ob eine vollständige Datenauswertung (AnalyzePercentageDigitalSignature) für maximale Genauigkeit durchgeführt wird. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Das Flag gibt an, ob jede Dokumentseite verifiziert werden soll. Standardmäßig ist der Wert True. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Die zusätzlichen Erweiterungen für die Verifizierung alternativer Signaturoptionen. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Das gültige Eigenschafts‑Flag. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Die zu verifizierende Dokumentseitennummer; wenn nicht festgelegt, werden alle Seiten des Dokuments für das erste Vorkommen verifiziert (Mindestwert ist 1). (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Die Seitenoptionen zur Angabe der zu verifizierenden Seiten. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Die Formposition im Dokumentlayout, die zum Verifizieren von Signaturen in Kopf‑/Fußzeilen verwendet wird. (geerbt von [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
