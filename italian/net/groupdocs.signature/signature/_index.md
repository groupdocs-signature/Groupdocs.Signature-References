---
title: "Firma"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta la classe principale che controlla il processo di firma del documento."
type: docs
weight: 2170
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
| [Signature](signature#constructor)(Stream) | Inizializza una nuova istanza della classe [`Signature`](../signature) con documento fornito tramite stream. |
| [Signature](signature#constructor_4)(string) | Inizializza una nuova istanza della classe [`Signature`](../signature) con documento fornito tramite percorso file. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Inizializza una nuova istanza della classe [`Signature`](../signature) con documento fornito tramite stream e opzioni di caricamento LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Inizializza una nuova istanza della classe [`Signature`](../signature) con documento fornito tramite stream e [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Inizializza una nuova istanza della classe [`Signature`](../signature) con documento fornito tramite percorso file e LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Inizializza una nuova istanza della classe [`Signature`](../signature) con documento fornito tramite percorso file e [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Inizializza una nuova istanza della classe [`Signature`](../signature) con documento fornito tramite stream, opzioni di caricamento LoadOptions e impostazioni [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Inizializza una nuova istanza della classe [`Signature`](../signature) con documento fornito tramite percorso file, LoadOptions e [`SignatureSettings`](../signaturesettings). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Elimina la firma fornita [`BaseSignature`](../../groupdocs.signature.domain/basesignature) dal documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Elimina l'elenco di firme fornito [`BaseSignature`](../../groupdocs.signature.domain/basesignature) dal documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Elimina le firme dei tipi specificati nella lista [`SignatureType`](../../groupdocs.signature.domain/signaturetype) dal documento. Verranno rimosse solo le firme aggiunte con il metodo Sign e contrassegnate come firme [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature). I seguenti tipi di firma sono supportati: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Elimina l'elenco di firme fornito [`BaseSignature`](../../groupdocs.signature.domain/basesignature) dal documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Elimina le firme di un determinato tipo [`SignatureType`](../../groupdocs.signature.domain/signaturetype) dal documento. Verranno rimosse solo le firme aggiunte con il metodo Sign e contrassegnate come firme [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature). I seguenti tipi di firma sono supportati: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Elimina la firma tramite il suo ID firma specifico dal documento. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementa l'interfaccia IDisposable per pulire le risorse interne |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Genera l'anteprima delle pagine del documento. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Cerca le firme nel documento utilizzando tutte le opzioni di ricerca disponibili e filtra i risultati in base al predicato specificato. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Cerca firme in un documento tramite l'elenco di [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Cerca i tipi di firma specificati nel documento tramite il valore di [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Cerca firme nel documento utilizzando le opzioni di ricerca fornite e filtra i risultati in base al predicato specificato. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Cerca firme in un documento tramite le opzioni di [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Cerca il tipo esatto di firme nel documento tramite il valore di [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Firma il documento con una collezione di [`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato in uno stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Firma il documento con [`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato in uno stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Firma il documento con una collezione di [`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso file specificato. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Firma il documento con [`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso file specificato. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Firma il documento con una collezione di [`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato in uno stream con i [`SaveOptions`](../../groupdocs.signature.options/saveoptions) predefiniti. |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Firma il documento con [`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato in uno stream con i [`SaveOptions`](../../groupdocs.signature.options/saveoptions) predefiniti. |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Firma il documento con una collezione di [`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso file specificato con i [`SaveOptions`](../../groupdocs.signature.options/saveoptions) predefiniti. |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Firma il documento con [`SignOptions`](../../groupdocs.signature.options/signoptions) e salva il risultato nel percorso file specificato con i [`SaveOptions`](../../groupdocs.signature.options/saveoptions) predefiniti. |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Aggiorna la firma fornita [`BaseSignature`](../../groupdocs.signature.domain/basesignature) nel documento. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Aggiorna le firme fornite [`BaseSignature`](../../groupdocs.signature.domain/basesignature) nel documento. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifica le firme del documento con un elenco di dati VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifica le firme del documento con i dati VerifyOptions forniti. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Verifica le firme del documento utilizzando tutte le opzioni di verifica disponibili e filtra i risultati in base al predicato specificato. Questo metodo prima ricerca le firme che corrispondono alle opzioni di verifica, le filtra usando il predicato e poi verifica solo le firme filtrate. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Verifica le firme del documento utilizzando le opzioni di verifica fornite e filtra i risultati in base al predicato specificato. Questo metodo prima ricerca le firme che corrispondono alle opzioni di verifica, le filtra usando il predicato e poi verifica solo le firme filtrate. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Genera un'anteprima della firma basata su SignOptions forniti. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Si verifica quando il processo di ricerca della firma è completato. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Si verifica quando il progresso del processo di ricerca della firma è cambiato. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Si verifica quando il processo di ricerca della firma è avviato. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Si verifica quando il processo di firma del documento è completato. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Si verifica quando il progresso del processo di firma del documento è cambiato. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Si verifica quando il processo di firma del documento è iniziato. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Si verifica quando il processo di verifica della firma è completato. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Si verifica quando il progresso del processo di verifica della firma è cambiato. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Si verifica quando il processo di verifica della firma è iniziato. |

### Osservazioni

**Learn more**

Maggiori informazioni sulle funzionalità di GroupDocs.Signature: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Vedi anche

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
