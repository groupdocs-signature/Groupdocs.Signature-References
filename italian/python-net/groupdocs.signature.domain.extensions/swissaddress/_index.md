---
title: "Classe SwissAddress"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta l'indirizzo del creditore o del debitore."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Rappresenta l'indirizzo del creditore o del debitore.

È possibile impostare street, house number, postal code e town (tipo di indirizzo strutturato) oppure address line 1 e 2 (tipo di elementi di indirizzo combinati).

Il tipo SwissAddress espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | La address line 1, contenente street name, house number o P.O. box, è opzionale e usata solo per indirizzi a elementi combinati. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | La address line 2, che contiene postal code e town, è obbligatoria per indirizzi a elementi combinati. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | Il codice ISO a due lettere del paese. Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori null o vuoti. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | Il house number. Questo campo è usato solo per indirizzi strutturati ed è opzionale. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | Il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | Il postal code. Questo campo è usato solo per indirizzi strutturati. Per questo tipo, è obbligatorio. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | La street dell'indirizzo, senza house number; opzionale e usata solo per indirizzi strutturati. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | Il town o city, usato solo per indirizzi strutturati ed obbligatorio per questo tipo. |

### Vedi anche
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
