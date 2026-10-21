---
title: "Firma"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa la clase principal que controla el proceso de firma de documentos."
type: docs
weight: 2170
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
| [Signature](signature#constructor)(Stream) | Inicializa una nueva instancia de la clase [`Signature`](../signature) con el documento proporcionado mediante stream. |
| [Signature](signature#constructor_4)(string) | Inicializa una nueva instancia de la clase [`Signature`](../signature) con el documento proporcionado mediante ruta de archivo. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Inicializa una nueva instancia de la clase [`Signature`](../signature) con el documento proporcionado mediante stream y opciones de carga LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Inicializa una nueva instancia de la clase [`Signature`](../signature) con el documento proporcionado mediante stream y [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Inicializa una nueva instancia de la clase [`Signature`](../signature) con el documento proporcionado mediante ruta de archivo y LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Inicializa una nueva instancia de la clase [`Signature`](../signature) con el documento proporcionado mediante ruta de archivo y [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Inicializa una nueva instancia de la clase [`Signature`](../signature) con el documento proporcionado mediante stream, opciones de carga LoadOptions y configuraciones [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Inicializa una nueva instancia de la clase [`Signature`](../signature) con el documento proporcionado mediante ruta de archivo, LoadOptions y [`SignatureSettings`](../signaturesettings). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Elimina la firma proporcionada [`BaseSignature`](../../groupdocs.signature.domain/basesignature) del documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Elimina la lista de firmas proporcionada [`BaseSignature`](../../groupdocs.signature.domain/basesignature) del documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Elimina las firmas de la lista de ciertos tipos [`SignatureType`](../../groupdocs.signature.domain/signaturetype) del documento. Solo se eliminarán las firmas que fueron añadidas mediante el método Sign y marcadas como firmas [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature). Los siguientes tipos de firma son compatibles: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Elimina la lista de firmas proporcionada [`BaseSignature`](../../groupdocs.signature.domain/basesignature) del documento. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Elimina las firmas de un determinado tipo [`SignatureType`](../../groupdocs.signature.domain/signaturetype) del documento. Solo se eliminarán las firmas que fueron añadidas mediante el método Sign y marcadas como firmas [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature). Los siguientes tipos de firma son compatibles: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Elimina la firma por su Id de firma específico del documento. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implementa la interfaz IDisposable para limpiar los recursos internos |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Genera una vista previa de las páginas del documento. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Obtiene información sobre las páginas del documento: sus tamaños, la altura máxima de página, el ancho de una página con la altura máxima. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Busca firmas en el documento utilizando todas las opciones de búsqueda disponibles y filtra los resultados según el predicado especificado. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Busca firmas en un documento mediante la lista de [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Busca tipos de firma especificados en el documento mediante el valor de [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Busca firmas en el documento usando las opciones de búsqueda proporcionadas y filtra los resultados según el predicado especificado. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Busca firmas en un documento mediante las opciones de [`SearchOptions`](../../groupdocs.signature.options/searchoptions). |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Busca el tipo exacto de firmas en el documento mediante el valor de [`SignatureType`](../../groupdocs.signature.domain/signaturetype). |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Firma el documento con una colección de [`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en un flujo. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Firma el documento con [`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en un flujo. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Firma el documento con una colección de [`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Firma el documento con [`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Firma el documento con una colección de [`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en un flujo con [`SaveOptions`](../../groupdocs.signature.options/saveoptions) predefinidas. |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Firma el documento con [`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en un flujo con [`SaveOptions`](../../groupdocs.signature.options/saveoptions) predefinidas. |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Firma el documento con una colección de [`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada con [`SaveOptions`](../../groupdocs.signature.options/saveoptions) predefinidas. |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Firma el documento con [`SignOptions`](../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada con [`SaveOptions`](../../groupdocs.signature.options/saveoptions) predefinidas. |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Actualiza la firma proporcionada [`BaseSignature`](../../groupdocs.signature.domain/basesignature) en el documento. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Actualiza las firmas proporcionadas [`BaseSignature`](../../groupdocs.signature.domain/basesignature) en el documento. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifica las firmas del documento con una lista de datos de VerifyOptions. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifica las firmas del documento con los datos de VerifyOptions proporcionados. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Verifica las firmas del documento usando todas las opciones de verificación disponibles y filtra los resultados según el predicado especificado. Este método primero busca firmas que coincidan con las opciones de verificación, las filtra usando el predicado y luego verifica solo esas firmas filtradas. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Verifica las firmas del documento usando las opciones de verificación proporcionadas y filtra los resultados según el predicado especificado. Este método primero busca firmas que coincidan con las opciones de verificación, las filtra usando el predicado y luego verifica solo esas firmas filtradas. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Genera una vista previa de la firma basada en los SignOptions proporcionados. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Ocurre cuando se completa el proceso de búsqueda de firmas. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Ocurre cuando cambia el progreso del proceso de búsqueda de firmas. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Ocurre cuando se inicia el proceso de búsqueda de firmas. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Ocurre cuando se completa el proceso de firma del documento. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Ocurre cuando el progreso del proceso de firma de documentos cambia. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Ocurre cuando se inicia el proceso de firma de documentos. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Ocurre cuando el proceso de verificación de firmas se completa. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Ocurre cuando el progreso del proceso de verificación de firmas cambia. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Ocurre cuando se inicia el proceso de verificación de firmas. |

### Observaciones

**Learn more**

Más información sobre las características de GroupDocs.Signature: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### Ver también

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
