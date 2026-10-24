---
title: "Clase Signature"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa la clase principal que controla el proceso de firma de documentos."
type: docs
url: /es/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Representa la clase principal que controla el proceso de firma de documentos.

Obtenga más información sobre las características de GroupDocs.Signature:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

El tipo Signature expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Inicializa una nueva instancia de Signature con un documento proporcionado como flujo. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un flujo de documento y opciones de carga. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento proporcionado mediante un flujo y opcionalmente con [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un flujo de documento, opciones de carga y configuraciones de firma. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento proporcionado por ruta de archivo. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Inicializa una nueva instancia de Signature con el documento proporcionado por ruta de archivo y opciones de carga. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con el documento proporcionado por una ruta de archivo y opcionalmente con [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Inicializa una nueva instancia de [`Signature`](/signature/python-net/groupdocs.signature/signature/) con un documento proporcionado por ruta de archivo, opciones de carga y configuraciones de firma. |

### Métodos
| Método | Descripción |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Elimina la [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) especificada del documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Elimina la lista de firmas proporcionada del documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Elimina firmas del tipo especificado del documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Elimina firmas de la lista de `SignatureType` especificada del documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Elimina una firma por su Id de firma específico del documento. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Elimina las firmas especificadas del documento. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Limpia los recursos internos utilizados por el objeto de firma. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Genera una vista previa de las páginas del documento. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Genera una vista previa de la firma basada en los SignOptions proporcionados. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Obtiene información sobre las páginas del documento: sus tamaños, la altura máxima de página, el ancho de una página con la altura máxima. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Busca firmas en un documento usando una lista de [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Busca firmas en el documento usando las opciones de búsqueda proporcionadas y filtra los resultados según el predicado especificado. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Busca tipos de firma especificados en el documento por el valor `SignatureType`. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Busca firmas en el documento usando todas las opciones de búsqueda disponibles y filtra los resultados según el predicado especificado. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Firma el documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en un flujo. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Firma un documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en un flujo usando los [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefinidos. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Firma el documento con una colección de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en un flujo. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Firma el documento con una colección de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en un flujo usando los [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefinidos. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Firma el documento con SignOptions y guarda el resultado en la ruta de archivo especificada. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Firma el documento con [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en la ruta de archivo especificada usando los [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefinidos. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Firma el documento con una colección de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en la ruta de archivo especificada. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Firma el documento con una colección de [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) y guarda el resultado en la ruta de archivo especificada usando los [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) predefinidos. |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Actualiza la BaseSignature de firma pasada en el documento. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Actualiza las firmas [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) pasadas en el documento. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Verifica las firmas del documento con los datos de VerifyOptions proporcionados. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Verifica las firmas del documento usando las opciones de verificación proporcionadas y filtra los resultados según el predicado especificado. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Verifica las firmas del documento con una lista de datos de VerifyOptions. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Verifica las firmas de documentos usando las opciones de verificación proporcionadas y filtra los resultados con el predicado dado. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Guías de tareas que usan `Signature`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Ver también
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
