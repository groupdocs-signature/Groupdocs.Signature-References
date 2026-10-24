---
title: "Instalación"
linkTitle: "Installation"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Instale GroupDocs.Signature for Python via .NET desde PyPI, fije la versión en requirements.txt, o instale una rueda predescargada para entornos sin conexión — luego verifique la instalación."
type: docs
url: /es/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET se distribuye como una rueda autocontenida que incluye el runtime .NET incrustado. Una única rueda `py3-none-{platform}` funciona con Python **3.5 – 3.14** en Windows, Linux y macOS (Intel y Apple Silicon). No se necesita nada más en Windows; Linux y macOS requieren algunos paquetes del sistema, enumerados a continuación.

Antes de instalar, revise los [Requisitos del Sistema](https://docs.groupdocs.com/signature/python-net/system-requirements/). Las ruedas requieren Linux con glibc 2.27 o superior, o macOS 12 o superior, y pip 20.3 o superior para la instalación. En Linux, instale ICU, fontconfig, `libgdiplus` y las fuentes principales de Microsoft; en macOS, instale `mono-libgdiplus`.

## Install Package from PyPI

Todos los paquetes están alojados en [PyPI](https://pypi.org/project/groupdocs-signature-net/). Instale la última versión con `pip`:

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

Para actualizar una instalación existente a la versión más reciente, añada la bandera `--upgrade`:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

Se recomienda usar un [entorno virtual](https://docs.python.org/3/library/venv.html) para que el paquete y sus dependencias permanezcan aislados del Python del sistema. Consulte la [Guía de inicio rápido](/signature/python-net/guides/quick-start-guide/) para los pasos de configuración del `venv`.

## Add the Package to `requirements.txt`

Para compilaciones reproducibles, fije la versión en el `requirements.txt` de su proyecto:

```text
groupdocs-signature-net==26.10.0
```

Luego instale todas las dependencias de una vez:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

En entornos sin acceso a PyPI (por ejemplo, un runner CI aislado o un servidor con restricciones), descargue la rueda para su plataforma e instálela desde un archivo local.

Descargue la rueda que coincida con su sistema operativo y arquitectura de CPU desde la página de [lanzamientos de GroupDocs.Signature](https://releases.groupdocs.com/signature/python-net/) :

| Plataforma | El nombre del archivo wheel termina con | Sistema más antiguo |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Desde la versión 26.10, los nombres de archivo indican el sistema más antiguo en el que se ejecuta cada wheel, por lo que pip 20.3 o superior rechaza de antemano uno más antiguo en lugar de instalar un tiempo de ejecución que no puede iniciarse. Los wheels hasta la 26.1 estaban etiquetados `manylinux1_x86_64`, `macosx_10_14_x86_64` y `macosx_11_0_arm64`, e incluían un wheel de Windows de 32 bits (`win32`); ya no hay un wheel de 32 bits, así que use Python de 64 bits en Windows.

Instale el archivo descargado con `pip` (reemplace el nombre del archivo con el wheel que descargó):

{{< tabs \"install-from-wheel\">}}
{{< tab \"Windows (64-bit)\" >}}
```ps
py -m pip install .\groupdocs_signature_net-26.10.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab \"Linux (glibc)\" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Apple Silicon)\" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< tab \"macOS (Intel)\" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

Nombre el archivo wheel explícitamente: PowerShell no expande un comodín `*` para un comando nativo, por lo que `pip install groupdocs_signature_net-*.whl` falla allí.

## Verify the Installation

Confirme que el paquete está instalado e importable:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

También puede comprobar la versión instalada con `pip`:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
