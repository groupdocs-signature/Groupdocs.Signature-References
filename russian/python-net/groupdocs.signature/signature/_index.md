---
title: "Класс Signature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет основной класс, который контролирует процесс подписи документа."
type: docs
url: /ru/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Представляет основной класс, который контролирует процесс подписи документа.

Узнайте больше о возможностях GroupDocs.Signature:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Тип Signature предоставляет следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Инициализирует новый экземпляр Signature с документом, предоставленным в виде потока. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с потоком документа и параметрами загрузки. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с документом, предоставленным через поток, и необязательными [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с потоком документа, параметрами загрузки и настройками подписи. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с документом, предоставленным по пути к файлу. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Инициализирует новый экземпляр Signature с документом, предоставленным по пути к файлу, и параметрами загрузки. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с документом, предоставленным по пути к файлу, и необязательными [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Инициализирует новый экземпляр [`Signature`](/signature/python-net/groupdocs.signature/signature/) с документом, предоставленным по пути к файлу, параметрами загрузки и настройками подписи. |

### Методы
| Метод | Описание |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Удаляет указанную [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) из документа. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Удаляет предоставленный список подписей из документа. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Удаляет подписи указанного типа из документа. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Удаляет подписи из списка указанного `SignatureType` в документе. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Удаляет подпись по её конкретному идентификатору подписи из документа. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Удаляет указанные подписи из документа. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Очищает внутренние ресурсы, используемые объектом подписи. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Создаёт предварительный просмотр страниц документа. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Создаёт предварительный просмотр подписи на основе заданных SignOptions. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Получает информацию о страницах документа: их размеры, максимальную высоту страницы, ширину страницы с максимальной высотой. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Ищет подписи в документе, используя список [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Ищет подписи в документе, используя предоставленные параметры поиска, и фильтрует результаты на основе указанного предиката. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Ищет указанные типы подписей в документе по значению `SignatureType`. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Ищет подписи в документе, используя все доступные параметры поиска, и фильтрует результаты на основе указанного предиката. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Подписывает документ с помощью [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат в поток. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Подписывает документ с помощью [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат в поток, используя предопределённые [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Подписывает документ набором [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат в поток. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Подписывает документ набором [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат в поток, используя предопределённые [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Подписывает документ с помощью SignOptions и сохраняет результат по указанному пути к файлу. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Подписывает документ с помощью [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат по указанному пути к файлу, используя предопределённые [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Подписывает документ набором [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат по указанному пути к файлу. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Подписывает документ набором [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) и сохраняет результат по указанному пути к файлу, используя предопределённые [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Обновляет переданную подпись BaseSignature в документе. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Обновляет переданные подписи [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) в документе. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Проверяет подписи документа с использованием заданных данных VerifyOptions. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Проверяет подписи документа, используя предоставленные параметры проверки, и фильтрует результаты на основе указанного предиката. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Проверяет подписи документа со списком данных VerifyOptions. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Проверяет подписи документов, используя предоставленные параметры проверки, и фильтрует результаты с помощью заданного предиката. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Пример

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
Руководства задач, использующие `Signature`:

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

### См. также
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
