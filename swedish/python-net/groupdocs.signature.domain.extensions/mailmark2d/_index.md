---
title: "Mailmark2D-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Kodar och avkodar texten som är inbäddad i Royal Mail 2D Mailmark."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Kodar och avkodar texten som är inbäddad i Royal Mail 2D Mailmark.

Mailmark2D-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Initierar kombinerade data för Royal Mail Mailmark med standardvärden för primära och sekundära data. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | Returnerar en kopia av detta objekt. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | Objektets klass. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | Det valfria utrymmet för kundens bruk. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | Kodningsläget för DataMatrix-streckkoden. Standardvärde: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | 2D Mailmark-typen definierar storleken på Data Matrix-streckkoden. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | Egenskapen innehåller leveransadressens postnummer med DPS, som för inlandadresser består av ett område (1‑2 tecken), distrikt (1‑2 tecken), sektor (1 tecken), enhet (2 tecken) och DPS (2 tecken), måste följa ett giltigt PAF®‑format och har en maximal längd på 9 tecken. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | Identifieraren för Royal Mail Mailmark-streckkodens nyttolast för varje produkttyp. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | Det unika objektidentifieraren inom Supply Chain‑ID, som krävs på varje Mailmark-streckkod för unik identifiering i minst 90 dagar (maxvärde: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | Return to Sender‑postkoden utan DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | Flaggan som indikerar vilken nivå av Return to Sender‑tjänst som begärs. Maxlängd är 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | Den unika gruppen av kunder som är involverade i utskicket. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | UPU-land-ID (maxlängd: 4 tecken). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | Streckkodsversionens identifierare som är relevant för varje Information Type‑ID. |

### Se även
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
