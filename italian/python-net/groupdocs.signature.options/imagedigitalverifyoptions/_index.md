---
title: "Classe ImageDigitalVerifyOptions"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Conserva le opzioni per verificare le firme digitali nelle immagini raster."
type: docs
url: /it/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Conserva le opzioni per verificare le firme digitali nelle immagini raster.

Il tipo ImageDigitalVerifyOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Inizializza una nuova istanza della classe ImageDigitalVerifyOptions per verificare firme digitali (steganografia) in immagini raster. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | La probabilità restituita da AnalyzePercentageDigitalSignature (0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | La percentuale soglia di rilevamento per l'estrazione parziale (0-100). Il valore predefinito è 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | La password utilizzata per incorporare la firma. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | La proprietà determina se viene eseguita l'estrazione completa dei dati (AnalyzePercentageDigitalSignature) per la massima precisione. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Il flag indica se ogni pagina del documento deve essere verificata. Per impostazione predefinita il valore è True. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Le estensioni aggiuntive per la verifica delle opzioni di firma alternative. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Il flag della proprietà valida. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Il numero di pagina del documento da verificare; se non impostato, tutte le pagine del documento sono verificate per la prima occorrenza (valore minimo è 1). (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Le opzioni di pagina per specificare le pagine da verificare. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | La posizione della forma nel layout del documento utilizzata per verificare le firme in intestazioni/piè di pagina. (eredita da [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Vedi anche
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
