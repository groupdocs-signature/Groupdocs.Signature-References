---
title: "DataMatrixEncodeMode Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "DataMatrixEncodeMode Aufzählung — GroupDocs.Signature für Python über .NET API‑Referenz."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

Der Typ DataMatrixEncodeMode stellt die folgenden Mitglieder bereit:

### Felder
| Feld | Beschreibung |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Automatisch den besten Kodiermodus für DataMatrix‑Kodierung auswählen |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Kodiert ein alphanumerisches oder zwei numerische Zeichen pro Byte |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Kodiert 8‑Bit‑Werte |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Kodiert mit der in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding angegebenen Kodierung |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Verwendet C40‑Kodierung. Kodiert Großbuchstaben‑Alphanumerisch, Kleinbuchstaben und Sonderzeichen |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Verwendet Text‑Kodierung. Kodiert Kleinbuchstaben‑Alphanumerisch, Großbuchstaben und Sonderzeichen. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Verwendet EDIFACT‑Kodierung. Verwendet sechs Bits pro Zeichen, kodiert Ziffern, Großbuchstaben und viele Satzzeichen, unterstützt jedoch keine Kleinbuchstaben. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Verwendet ANSI‑X12‑Kodierung. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | Der ExtendedCodetext‑Modus ermöglicht das manuelle Umschalten von Kodierungsschemata im Code‑Text. Format : \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\". Erlaubte Kodierungsschemata sind: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Beispiel für erweiterten Code‑Text: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText\" Alle Rückwärtsschrägstriche (\\) müssen im Text verdoppelt werden. |

### Siehe auch
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
