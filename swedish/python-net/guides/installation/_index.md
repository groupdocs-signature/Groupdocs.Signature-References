---
title: "Installation"
linkTitle: "Installation"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Installera GroupDocs.Signature for Python via .NET från PyPI, lås den i requirements.txt, eller installera ett förhandsnedladdat wheel för offline-miljöer — verifiera sedan installationen."
type: docs
url: /sv/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET distribueras som ett självständigt wheel som innehåller den inbäddade .NET-runtime. Ett enda `py3-none-{platform}` wheel fungerar över Python **3.5 – 3.14** på Windows, Linux och macOS (Intel och Apple Silicon). Inget annat behövs på Windows; Linux och macOS kräver några systempaket, som listas nedan.

Innan du installerar, granska [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Hjul kräver Linux med glibc 2.27 eller nyare, eller macOS 12 eller nyare, och pip 20.3 eller nyare för att installera. På Linux, installera ICU, fontconfig, `libgdiplus` och Microsofts kärnfonter; på macOS, installera `mono-libgdiplus`.

## Install Package from PyPI

Alla paket finns på [PyPI](https://pypi.org/project/groupdocs-signature-net/). Installera den senaste versionen med `pip`:

{{< tabs \"install-from-pypi\">}}
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

För att uppgradera en befintlig installation till den senaste releasen, lägg till flaggan `--upgrade`:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

Att använda en [virtual environment](https://docs.python.org/3/library/venv.html) rekommenderas så att paketet och dess beroenden förblir isolerade från ditt system‑Python. Se [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) för `venv`‑installationsstegen.

## Add the Package to `requirements.txt`

För reproducerbara byggen, lås versionen i ditt projekts `requirements.txt`:

```text
groupdocs-signature-net==26.10.0
```

Installera sedan alla beroenden på en gång:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

I miljöer utan åtkomst till PyPI (till exempel en luftspärrad CI‑runner eller en låst server), ladda ner hjulet för din plattform och installera det från en lokal fil.

Ladda ner hjulet som matchar ditt operativsystem och CPU‑arkitektur från sidan [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) :

| Plattform | Hjulfilens namn slutar med | Äldsta system |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Sedan 26.10 anger filnamnen det äldsta systemet varje hjul kan köras på, så pip 20.3 eller nyare avvisar ett äldre hjul direkt istället för att installera en körtid som inte kan starta. Hjul upp till 26.1 var märkta `manylinux1_x86_64`, `macosx_10_14_x86_64` och `macosx_11_0_arm64`, och inkluderade ett 32‑bit Windows‑hjul (`win32`); det finns inget 32‑bit hjul längre, så använd en 64‑bit Python på Windows.

Installera den nedladdade filen med `pip` (ersätt filnamnet med hjulet du laddade ner):

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

Namnge hjulet explicit: PowerShell expanderar inte en `*`‑jokertecken för ett inbyggt kommando, så `pip install groupdocs_signature_net-*.whl` misslyckas där.

## Verify the Installation

Bekräfta att paketet är installerat och importerat:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

Du kan också kontrollera den installerade versionen med `pip`:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
