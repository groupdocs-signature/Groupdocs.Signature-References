---
title: "Краткое руководство"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Создайте виртуальное окружение, установите groupdocs-signature-net и выполните три простых примера: подпишите PDF текстовой подписью, выполните поиск подписей и проверьте их."
type: docs
url: /ru/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Это руководство предоставляет краткий обзор того, как настроить и начать использовать GroupDocs.Signature for Python via .NET. Библиотека добавляет, ищет, проверяет, обновляет и удаляет электронные подписи в файлах PDF, Word, Excel, PowerPoint, OpenDocument и изображениях с помощью нескольких строк кода.

## Prerequisites

Чтобы продолжить, убедитесь, что у вас есть:

1. Настроенное окружение, как описано в разделе [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). На Linux и macOS это включает несколько системных пакетов.
2. При желании, [Temporary License](https://purchase.groupdocs.com/temporary-license/) для тестирования всех функций продукта. Без лицензии библиотека работает в режиме оценки: она обрабатывает документы до двух страниц и добавляет строку оценки на каждую подписанную страницу. Смотрите [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

Для лучших практик используйте виртуальное окружение для управления зависимостями. Подробнее см. в руководстве [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Создайте виртуальное окружение:

{{< tabs \"create-venv\">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Активируйте его:

{{< tabs \"activate-venv\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs \"install-package\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

Смотрите [Installation](/signature/python-net/guides/installation/) для фиксации версии и установки без доступа к PyPI.

## Example 1: Sign a PDF with a Text Signature

Откройте документ, опишите подпись с помощью [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), и сохраните подписанную копию.

{{< tabs \"sign_pdf_with_text_signature\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Откройте документ; блок with освобождает файл, когда он заканчивается
    with Signature("sample.pdf") as signature:
        # Текстовая подпись, расположенная на 100 пикселей от левого и верхнего краев первой страницы
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Подпишите и сохраните результат в новый файл; исходный файл останется без изменений
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Найдите подписи, которые уже содержит документ. `search` принимает список параметров поиска, по одному для каждого типа подписи, и возвращает их в `result.signatures`.

{{< tabs "search_document_for_signatures">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Ищите текстовые подписи на каждой странице
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Проверьте, что документ содержит ожидаемую подпись. Проверка проходит успешно, когда найдена текстовая подпись с точно этим текстом.

{{< tabs "verify_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Сохраните каждый пример в отдельный файл `.py` рядом с примерами файлов. Ваша папка должна выглядеть примерно так:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Запустите пример из этой папки:

{{< tabs "run-the-app">}}
{{< tab \"Windows\" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

Когда закончите, деактивируйте виртуальное окружение, выполнив `deactivate`, или закройте оболочку.

## Apply a License

Установите переменную окружения `GROUPDOCS_LIC_PATH` в полный путь к вашему файлу лицензии, и лицензия будет применена автоматически при импорте `groupdocs.signature`. Код не требуется. При желании можно применить её в коде один раз, перед любыми другими вызовами:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

В разделе [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) рассматриваются оба способа и лицензия с измерением использования.

## Next Steps

После освоения основ изучите дополнительные ресурсы:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
