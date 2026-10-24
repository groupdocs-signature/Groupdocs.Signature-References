---
title: "Classe Mailmark2D"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Codifica e decodifica il testo incorporato nel Royal Mail 2D Mailmark."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Codifica e decodifica il testo incorporato nel Royal Mail 2D Mailmark.

Il tipo Mailmark2D espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Inizializza i dati combinati Royal Mail Mailmark con i valori predefiniti dei dati primari e secondari. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | Restituisce una copia di questo oggetto. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | La classe dell'elemento. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | Lo spazio opzionale per l'uso del cliente. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | La modalità di codifica del codice a barre DataMatrix. Valore predefinito: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | La proprietà contiene il codice postale dell'indirizzo di consegna con DPS, che per gli indirizzi interni è composto da un'area (1‑2 caratteri), distretto (1‑2 caratteri), settore (1 carattere), unità (2 caratteri) e DPS (2 caratteri), deve seguire un formato PAF® valido e ha una lunghezza massima di 9 caratteri. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | L'identificatore del payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | L'identificatore unico dell'elemento all'interno del Supply Chain ID, richiesto su ogni codice a barre Mailmark per un'identificazione univoca per almeno 90 giorni (valore massimo: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | Il codice postale di ritorno al mittente senza DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | Il flag che indica quale livello di servizio di ritorno al mittente è richiesto. La lunghezza massima è 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | Il gruppo unico di clienti coinvolti nella spedizione. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | L'ID paese UPU (lunghezza massima: 4 caratteri). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | L'identificatore della versione del codice a barre rilevante per ogni ID tipo di informazione. |

### Vedi anche
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
