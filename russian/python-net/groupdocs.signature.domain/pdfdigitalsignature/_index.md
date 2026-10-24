---
title: "Класс PdfDigitalSignature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет свойства цифровой подписи PDF."
type: docs
url: /ru/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

Представляет свойства цифровой подписи PDF.

Тип PdfDigitalSignature раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | Инициализирует цифровую подпись PDF без сертификата. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | Инициализирует цифровую подпись PDF, используя указанный хранилище X509. Будет использован первый сертификат из хранилища. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | Инициализирует цифровую подпись PDF, используя указанный хранилище X509 и индекс сертификата. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | Инициализирует цифровую подпись PDF с указанным сертификатом X509. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | Создать клон экземпляра цифровой подписи PDF. |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | Сравнивает свойства подписи для определения равенства. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | Переопределяет метод GetHashCode. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Загружает цифровые подписи из всех системных хранилищ сертификатов X509. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | Контактная информация, предоставленная подписантом, чтобы получатель мог проверить подпись, например номер телефона. |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | Имя хоста CPU или физическое местоположение подписи. |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | Причина подписи, например (I agreeРІР‚В¦). |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | Флаг, который принуждает свойства подписи отображаться или скрываться; когда истинно, поле подписи использует предопределённый формат отображения (например, `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`) и по умолчанию равно True. |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | Отметка времени для цифровой подписи PDF. Значение по умолчанию — None. |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | Тип цифровой подписи PDF. |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Сертификат X509, связанный с цифровой подписью. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Пользовательское имя хранилища сертификата. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Расположение хранилища сертификата. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Имя хранилища сертификата. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Комментарий о цели подписи. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Дата создания подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Флаг, указывающий, была ли эта подпись удалена из документа. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Высота подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Флаг, указывающий, представляет ли этот компонент подпись (`True`) или содержимое документа (`False`). (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Цифровая подпись действительна, и документ не был изменён. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Левая позиция подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Дата изменения подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Номер страницы, на которой была найдена подпись. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Время подписи документа. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Уникальный идентификатор подписи, используемый для изменения подписи в документе через операции обновления или удаления. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Тип подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Отпечаток сертификата. (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Верхняя позиция подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Ширина подписи. (унаследовано от [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Тип XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). (унаследовано от [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### См. также
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
