---
title: "PdfDigitalSignature-Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Eigenschaften der PDF-Digitalunterschrift dar."
type: docs
url: /de/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

Stellt die Eigenschaften der PDF-Digitalunterschrift dar.

Der PdfDigitalSignature-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | Initialisiert eine PDF-Digitale Signatur ohne Zertifikat. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | Initialisiert eine PDF-Digitale Signatur unter Verwendung des angegebenen X509-Speichers. Das erste Zertifikat aus dem Speicher wird verwendet. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | Initialisiert eine PDF-Digitale Signatur unter Verwendung des angegebenen X509-Speichers und des Zertifikatsindex. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | Initialisiert eine PDF-Digitale Signatur mit dem angegebenen X509-Zertifikat. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | Klone die PDF-Digitale Signatur-Instanz. |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | Vergleicht Signatur-Eigenschaften, um Gleichheit zu bestimmen. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | Überschreibt die GetHashCode-Methode. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Lädt digitale Signaturen aus allen System-X509-Zertifikatspeichern. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | Die vom Unterzeichner bereitgestellten Kontaktinformationen, um einem Empfänger die Überprüfung der Signatur zu ermöglichen, z. B. eine Telefonnummer. |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | Der CPU-Hostname oder der physische Standort der Unterzeichnung. |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | Der Grund für die Unterzeichnung, z. B. (I agreeРІР‚В¦). |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | Das Flag, das die Anzeige der Signatur‑Eigenschaften erzwingt; wenn true, verwendet das Signaturfeld ein vordefiniertes Anzeigeformat (z. B. `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`) und ist standardmäßig auf True gesetzt. |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | Der Zeitstempel für eine PDF‑Digitalsignatur. Standardwert ist None. |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | Der Typ der PDF‑Digitalsignatur. |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Das X509‑Zertifikat, das mit der Digitalsignatur verknüpft ist. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Der benutzerdefinierte Speichername des Zertifikats. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Der Speicherort des Zertifikats. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Der Speichername des Zertifikats. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Der Kommentar zum Signaturzweck. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Das Erstellungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Die Höhe der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Das Flag, das angibt, ob diese Komponente eine Signatur (`True`) oder Dokumentinhalt (`False`) darstellt. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Die Digitalsignatur ist gültig und das Dokument wurde nicht manipuliert. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Die linke Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Das Änderungsdatum der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Die Seitenzahl, auf der die Signatur gefunden wurde. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Der Zeitpunkt, zu dem das Dokument signiert wurde. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Der eindeutige Bezeichner der Signatur, der verwendet wird, um die Signatur im Dokument über Update- oder Löschvorgänge zu ändern. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Der Typ der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Der Fingerabdruck eines Zertifikats. (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Die obere Position der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Die Breite der Signatur. (geerbt von [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Der XAdES‑Typ ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). (geerbt von [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Siehe auch
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
