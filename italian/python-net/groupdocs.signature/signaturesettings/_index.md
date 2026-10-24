---
title: "Classe SignatureSettings"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta le impostazioni per personalizzare il comportamento di Signature."
type: docs
url: /it/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Rappresenta le impostazioni per personalizzare il comportamento di [`Signature`](/signature/python-net/groupdocs.signature/signature/).

Il tipo SignatureSettings espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Inizializza un'istanza predefinita di SignatureSettings con valori predefiniti. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Inizializza un'istanza predefinita di SignatureSettings con l'implementazione di Logger. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | La cultura predefinita utilizzata durante l'elaborazione dei documenti. Il valore predefinito è "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | Il flag che indica se le firme di metadati del documento standard, come Autore, Proprietario, data di creazione e data di modifica, sono incluse nell'elenco dei metadati. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | I flag di livello di log che determinano quali tipi di messaggi vengono passati a [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | L'implementazione del logger usata per la registrazione (Errori, Avvisi, Tracce). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Il flag che determina se il documento sorgente viene risalvato quando il metodo Delete non ha firme interessate da rimuovere. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | Il flag che determina se il documento sorgente viene risalvato quando il metodo `Update` non ha firme da aggiornare. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | Il flag che determina se le firme eliminate sono incluse nel risultato delle informazioni del documento. Ogni [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) ha un flag `Deleted` per indicare se è stata eliminata. |

### Vedi anche
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
