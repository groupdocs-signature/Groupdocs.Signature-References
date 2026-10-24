---
title: "Свойство skip_external_resources"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, который препятствует загрузке документом внешних ресурсов."
type: docs
url: /ru/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

Флаг, который останавливает загрузку внешних ресурсов документом. Значение по умолчанию — True; внешние ресурсы не загружаются, за исключением тех, которые соответствуют [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Документ может ссылаться на ресурсы, хранящиеся за его пределами, такие как связанные изображения, картинки, вставленные полем INCLUDEPICTURE, связанные изображения в презентациях и таблицах, а также изображения и таблицы стилей, на которые ссылается SVG‑изображение. Загрузка такого ресурса заставляет библиотеку запрашивать его адрес. На сервере, обрабатывающем недоверенные документы, документ может использовать это для отправки сервером запросов к внутренним адресам (server‑side request forgery), а путь UNC или `file://` может привести к тому, что Windows отправит учетные данные NTLM аккаунта другому хосту. В автономной или изолированной установке запросы завершаются неудачей или ждут тайм‑аута.

Пропущенные ресурсы не отображаются в предварительном просмотре страниц и в документах, сохраненных как изображения, и поиск изображений, штрих‑кодов и QR‑кодов их не видит. Устанавливайте это свойство в False только для доверенных документов и предпочтительно разрешайте конкретные адреса с помощью [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Эта настройка применяется к документам обработки текста, презентациям, таблицам и SVG‑изображениям, включая документы внутри архивов. Для SVG‑изображений ссылки, не разрешённые, удаляются из изображения перед чтением, а SVG‑изображение, не являющееся корректным XML, отклоняется. Настройка не контролирует проверки отзыва сертификатов, серверы временных меток или лицензирование.

Это свойство заменяет [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), которое имеет противоположное значение.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### См. также
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
