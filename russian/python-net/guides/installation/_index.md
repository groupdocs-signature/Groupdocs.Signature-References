---
title: "Установка"
linkTitle: "Installation"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Установите GroupDocs.Signature for Python via .NET из PyPI, зафиксируйте его в requirements.txt или установите предварительно загруженный wheel для офлайн‑среды — затем проверьте установку."
type: docs
url: /ru/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET распространяется как самодостаточный wheel, включающий встроенную среду выполнения .NET. Один wheel `py3-none-{platform}` работает с Python **3.5 – 3.14** на Windows, Linux и macOS (Intel и Apple Silicon). На Windows ничего больше не требуется; для Linux и macOS нужны несколько системных пакетов, перечисленных ниже.

Прежде чем устанавливать, ознакомьтесь с [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Для установки wheel требуются Linux с glibc 2.27 или новее, либо macOS 12 или новее, и pip 20.3 или новее. На Linux установите ICU, fontconfig, `libgdiplus` и шрифты Microsoft core fonts; на macOS установите `mono-libgdiplus`.

## Install Package from PyPI

Все пакеты размещены на [PyPI](https://pypi.org/project/groupdocs-signature-net/). Установите последнюю версию с помощью `pip`:

{{< tabs "install-from-pypi">}}
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

Чтобы обновить существующую установку до последней версии, добавьте флаг `--upgrade`:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

Использование [виртуального окружения](https://docs.python.org/3/library/venv.html) рекомендуется, чтобы пакет и его зависимости были изолированы от системного Python. См. [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) для шагов настройки `venv`.

## Add the Package to `requirements.txt`

Для воспроизводимых сборок зафиксируйте версию в файле `requirements.txt` вашего проекта:

```text
groupdocs-signature-net==26.10.0
```

Затем установите все зависимости одним командой:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

В средах без доступа к PyPI (например, в изолированном CI‑раннере или на закрытом сервере) скачайте wheel для вашей платформы и установите его из локального файла.

Скачайте wheel, соответствующий вашей операционной системе и архитектуре CPU, со страницы [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/):

| Платформа | Имя файла колеса заканчивается на | Самая старая система |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Начиная с версии 26.10 имена файлов указывают самую старую систему, на которой может работать каждое колесо, поэтому pip 20.3 и новее отказываются от более старой версии сразу, вместо установки среды выполнения, которая не может запуститься. Колёса до версии 26.1 были помечены `manylinux1_x86_64`, `macosx_10_14_x86_64` и `macosx_11_0_arm64`, и включали 32‑битное колесо Windows (`win32`); 32‑битных колёс больше нет, поэтому используйте 64‑битный Python в Windows.

Установите загруженный файл с помощью `pip` (замените имя файла на скачанное колесо):

{{< tabs "install-from-wheel">}}
{{< tab "Windows (64-bit)" >}}
```ps
py -m pip install .\groupdocs_signature_net-26.10.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab "Linux (glibc)" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Apple Silicon)" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< tab "macOS (Intel)" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

Укажите имя файла колеса явно: PowerShell не расширяет шаблон `*` для нативной команды, поэтому `pip install groupdocs_signature_net-*.whl` не работает.

## Verify the Installation

Подтвердите, что пакет установлен и его можно импортировать:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

Вы также можете проверить установленную версию с помощью `pip`:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
