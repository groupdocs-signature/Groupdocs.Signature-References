---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Contiene le proprietà della firma del campo modulo di input radiobutton."
type: docs
weight: 1000
url: /it/net/groupdocs.signature.domain/radiobuttonformfieldsignature/
---
## RadioButtonFormFieldSignature class

Contiene le proprietà della firma del campo modulo di input radio-button.

```csharp
public sealed class RadioButtonFormFieldSignature : FormFieldSignature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RadioButtonFormFieldSignature](radiobuttonformfieldsignature#constructor)(string) | Crea RadioButtonFieldSignature con nome predefinito. |
| [RadioButtonFormFieldSignature](radiobuttonformfieldsignature#constructor_1)(string, List&lt;string&gt;) | Crea RadioButtonFieldSignature con nome predefinito e lista di elementi. |
| [RadioButtonFormFieldSignature](radiobuttonformfieldsignature#constructor_2)(string, List&lt;string&gt;, object) | Crea RadioButtonFieldSignature con nome predefinito, lista di elementi e valore selezionato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Ottieni o imposta la data di creazione della firma. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ottieni il flag che indica se questa firma è stata eliminata dal documento. Questa proprietà è utilizzata solo per i record del registro della cronologia del documento per mantenere l'elenco delle firme eliminate. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifica l'altezza della firma. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà è utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false). |
| [Items](../../groupdocs.signature.domain/radiobuttonformfieldsignature/items) { get; set; } | Ottieni o imposta l'elenco delle opzioni dei pulsanti radio. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifica la posizione sinistra della firma. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ottieni o imposta la data di modifica della firma. |
| [Name](../../groupdocs.signature.domain/formfieldsignature/name) { get; set; } | Specifica un nome di campo modulo univoco. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifica la pagina su cui è stata trovata la firma. |
| [Selected](../../groupdocs.signature.domain/radiobuttonformfieldsignature/selected) { get; set; } | Contiene il valore selezionato. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Identificatore univoco della firma per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata dei metodi Sign o Search. Se questa proprietà è stata salvata in precedenza, può essere impostata manualmente per manipolare la firma. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifica il tipo di firma. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifica la posizione superiore della firma. |
| [Type](../../groupdocs.signature.domain/formfieldsignature/type) { get; } | Specifica il tipo di campo modulo. |
| [Value](../../groupdocs.signature.domain/formfieldsignature/value) { get; set; } | Specifica l'oggetto dati del campo modulo. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifica la larghezza della firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/radiobuttonformfieldsignature/clone)() | Clona l'istanza della firma FormField. |
| override [Equals](../../groupdocs.signature.domain/radiobuttonformfieldsignature/equals)(object) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| override [GetHashCode](../../groupdocs.signature.domain/radiobuttonformfieldsignature/gethashcode)() | Sovrascrive il metodo GetHashCode |

### Vedi anche

* class [FormFieldSignature](../formfieldsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
