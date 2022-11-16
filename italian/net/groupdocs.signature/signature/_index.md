---
title: Signature
second_title: Riferimento API GroupDocs.Signature per .NET
description: Rappresenta la classe principale che controlla il processo di firma del documento.
type: docs
weight: 1800
url: /it/net/groupdocs.signature/signature/
---
## Signature class

Rappresenta la classe principale che controlla il processo di firma del documento.

```csharp
public class Signature : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Inizializza la nuova istanza di[`Signature`](../signature) classe con documento fornito da stream. |
| [Signature](signature#constructor_4)(string) | Inizializza la nuova istanza di[`Signature`](../signature) istanza di classe con documento fornito dal percorso del file. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Inizializza la nuova istanza di[`Signature`](../signature) classe con documento fornito da stream e opzioni di caricamentoLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Inizializza la nuova istanza di[`Signature`](../signature) istanza di classe con documento fornito da stream e[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Inizializza la nuova istanza di[`Signature`](../signature) istanza di classe con documento fornito dal percorso del file eLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Inizializza la nuova istanza di[`Signature`](../signature) istanza di classe con documento fornito dal percorso del file e[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Inizializza la nuova istanza di[`Signature`](../signature) istanza di classe con documento fornito da stream, opzioni di caricamentoLoadOptions e impostazioni[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Inizializza la nuova istanza di[`Signature`](../signature) istanza di classe con documento fornito dal percorso del file,LoadOptions e[`SignatureSettings`](../signaturesettings) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Elimina la firma passata[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dal documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Elimina l'elenco delle firme passate[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dal documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Elimina le firme dell'elenco di determinati tipi[`SignatureType`](../../groupdocs.signature.domain/signaturetype) dal documento. Solo le firme aggiunte con il metodo Firma e contrassegnate come Firme[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) verrà rimosso. Sono supportati i seguenti tipi di firma: testo, immagine, digitale, codice a barre, codice QR |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Elimina l'elenco delle firme passate[`BaseSignature`](../../groupdocs.signature.domain/basesignature) dal documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Elimina le firme di un determinato tipo[`SignatureType`](../../groupdocs.signature.domain/signaturetype) dal documento. Solo le firme aggiunte con il metodo Firma e contrassegnate come Firme[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) verrà rimosso. Sono supportati i seguenti tipi di firma: testo, immagine, digitale, codice a barre, codice QR |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Elimina la firma in base al suo ID firma specifico dal documento. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementa l'interfaccia IDisposable per ripulire le risorse interne |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Genera l'anteprima delle pagine del documento. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Cerca le firme in un documento per[`SearchOptions`](../../groupdocs.signature.options/searchoptions) elenco. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Cerca i tipi di firma specificati nel documento per[`SignatureType`](../../groupdocs.signature.domain/signaturetype) valore. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Cerca le firme in un documento per[`SearchOptions`](../../groupdocs.signature.options/searchoptions) opzioni. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Cerca il tipo esatto di firme nel documento per[`SignatureType`](../../groupdocs.signature.domain/signaturetype) valore. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Segni documento con raccolta di[`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato in un flusso. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Firma il documento con[`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato in un flusso. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Segni documento con raccolta di[`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso del file specificato. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Firma il documento con[`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso del file specificato. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Segni documento con raccolta di[`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato in un flusso con predefinito[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Firma il documento con[`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato in un flusso con predefinito[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Segni documento con raccolta di[`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso del file specificato con predefinito[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Firma il documento con[`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso del file specificato con predefinito[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Gli aggiornamenti hanno superato la firma[`BaseSignature`](../../groupdocs.signature.domain/basesignature) nel documento. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Aggiornamenti passati firme[`BaseSignature`](../../groupdocs.signature.domain/basesignature) nel documento. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifica le firme del documento con l'elenco dei dati di VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifica le firme dei documenti con i dati di VerifyOptions forniti. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Genera l'anteprima della firma in base a determinate SignOptions.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Si verifica al completamento del processo di ricerca della firma. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Si verifica quando l'avanzamento del processo di ricerca della firma è cambiato. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Si verifica all'avvio del processo di ricerca della firma. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Si verifica al completamento del processo di firma del documento. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Si verifica quando l'avanzamento del processo di firma del documento viene modificato. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Si verifica all'avvio del processo di firma del documento. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Si verifica al completamento del processo di verifica della firma. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Si verifica quando l'avanzamento del processo di verifica della firma è cambiato. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Si verifica all'avvio del processo di verifica della firma. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sulle funzionalità di GroupDocs.Signature: [Guida per gli sviluppatori di GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Guarda anche

* spazio dei nomi [GroupDocs.Signature](../../groupdocs.signature)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
