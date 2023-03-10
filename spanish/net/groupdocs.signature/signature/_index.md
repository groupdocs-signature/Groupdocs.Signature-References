---
title: Signature
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Representa la clase principal que controla el proceso de firma de documentos.
type: docs
weight: 1880
url: /es/net/groupdocs.signature/signature/
---
## Signature class

Representa la clase principal que controla el proceso de firma de documentos.

```csharp
public class Signature : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Inicializa una nueva instancia de[`Signature`](../signature) clase con documento proporcionado por stream. |
| [Signature](signature#constructor_4)(string) | Inicializa una nueva instancia de[`Signature`](../signature) instancia de clase con documento proporcionado por la ruta del archivo. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Inicializa una nueva instancia de[`Signature`](../signature) clase con documento proporcionado por flujo y opciones de cargaLoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Inicializa una nueva instancia de[`Signature`](../signature)instancia de clase con documento proporcionado por stream y[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | Inicializa una nueva instancia de[`Signature`](../signature) instancia de clase con documento proporcionado por ruta de archivo yLoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Inicializa una nueva instancia de[`Signature`](../signature) instancia de clase con documento proporcionado por ruta de archivo y[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Inicializa una nueva instancia de[`Signature`](../signature) instancia de clase con documento proporcionado por flujo, opciones de cargaLoadOptions y ajustes[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Inicializa una nueva instancia de[`Signature`](../signature) instancia de clase con documento proporcionado por ruta de archivo,LoadOptions y[`SignatureSettings`](../signaturesettings) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Elimina la firma pasada[`BaseSignature`](../../groupdocs.signature.domain/basesignature) del documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Elimina la lista aprobada de firmas[`BaseSignature`](../../groupdocs.signature.domain/basesignature) del documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Elimina las firmas de la lista de ciertos tipos[`SignatureType`](../../groupdocs.signature.domain/signaturetype) del documento. Solo las firmas que se agregaron mediante el método Firmar y se marcaron como Firmas[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) será eliminado. Se admiten los siguientes tipos de firma: texto, imagen, digital, código de barras, código QR |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Elimina la lista aprobada de firmas[`BaseSignature`](../../groupdocs.signature.domain/basesignature) del documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Elimina firmas de cierto tipo[`SignatureType`](../../groupdocs.signature.domain/signaturetype) del documento. Solo las firmas que se agregaron mediante el método Firmar y se marcaron como Firmas[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) será eliminado. Se admiten los siguientes tipos de firma: texto, imagen, digital, código de barras, código QR |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Elimina la firma por su ID de firma específico del documento. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementar interfaz IDisposable para limpiar recursos internos |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Genera vista previa de las páginas del documento. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Obtiene información sobre las páginas del documento: sus tamaños, altura máxima de página, el ancho de una página con la altura máxima. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Busca firmas en un documento por[`SearchOptions`](../../groupdocs.signature.options/searchoptions) lista. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Busca tipos de firma especificados en el documento por[`SignatureType`](../../groupdocs.signature.domain/signaturetype) valor. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | Busca firmas en un documento por[`SearchOptions`](../../groupdocs.signature.options/searchoptions) opciones. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | Busca el tipo exacto de firmas en el documento por[`SignatureType`](../../groupdocs.signature.domain/signaturetype) valor. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Firma documento con cobro de[`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en un stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Firma documento con[`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en un stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Firma documento con cobro de[`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Firma documento con[`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Firma documento con cobro de[`SignOptions`](../../groupdocs.signature.options/signoptions) guarda el resultado en una secuencia con predefinido[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Firma documento con[`SignOptions`](../../groupdocs.signature.options/signoptions) guarda el resultado en una secuencia con predefinido[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Firma documento con cobro de[`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada con predefinido[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Firma documento con[`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada con predefinido[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Actualizaciones aprobadas firma[`BaseSignature`](../../groupdocs.signature.domain/basesignature) en el documento. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Actualizaciones aprobadas firmas[`BaseSignature`](../../groupdocs.signature.domain/basesignature) en el documento. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifica las firmas del documento con la lista de datos de VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifica las firmas del documento con los datos VerifyOptions dados. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Genera una vista previa de la firma basada en SignOptions dadas.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Ocurre cuando se completa el proceso de búsqueda de firmas. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Ocurre cuando cambia el progreso del proceso de búsqueda de firmas. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Ocurre cuando se inicia el proceso de búsqueda de firmas. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Ocurre cuando se completa el proceso de firma del documento. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Ocurre cuando cambia el progreso del proceso de firma de documentos. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Ocurre cuando se inicia el proceso de firma del documento. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Ocurre cuando se completa el proceso de verificación de firma. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Ocurre cuando cambia el progreso del proceso de verificación de firma. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Ocurre cuando se inicia el proceso de verificación de firma. |

### Observaciones

**Aprende más**

* Más sobre GroupDocs.Características de firma: [Guía para desarrolladores de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Ver también

* espacio de nombres [GroupDocs.Signature](../../groupdocs.signature)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
