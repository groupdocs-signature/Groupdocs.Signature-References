---
title: "Installatie"
linkTitle: "Installation"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Installeer GroupDocs.Signature for Python via .NET vanaf PyPI, pin het in requirements.txt, of installeer een vooraf gedownloade wheel voor offline omgevingen — controleer vervolgens de installatie."
type: docs
url: /nl/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET wordt gedistribueerd als een zelfstandige wheel die de ingebedde .NET-runtime bevat. Eén enkele `py3-none-{platform}`‑wheel werkt op Python **3.5 – 3.14** onder Windows, Linux en macOS (Intel en Apple Silicon). Er is niets anders nodig op Windows; Linux en macOS hebben enkele systeempakketten nodig, hieronder vermeld.

Voordat u installeert, bekijk de [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). De wheels vereisen Linux met glibc 2.27 of nieuwer, of macOS 12 of nieuwer, en pip 20.3 of nieuwer om te installeren. Op Linux installeert u ICU, fontconfig, `libgdiplus` en de Microsoft core‑fonts; op macOS installeert u `mono‑libgdiplus`.

## Install Package from PyPI

Alle pakketten worden gehost op [PyPI](https://pypi.org/project/groupdocs-signature-net/). Installeer de nieuwste versie met `pip`:

{{< tabs "install-from-pypi">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

Om een bestaande installatie te upgraden naar de nieuwste release, voeg de `--upgrade`‑vlag toe:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

Het gebruik van een [virtual environment](https://docs.python.org/3/library/venv.html) wordt aanbevolen zodat het pakket en de afhankelijkheden geïsoleerd blijven van uw systeem‑Python. Zie de [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) voor de `venv`‑installatiestappen.

## Add the Package to `requirements.txt`

Voor reproduceerbare builds, pin de versie in het `requirements.txt`‑bestand van uw project:

```text
groupdocs-signature-net==26.10.0
```

Installeer vervolgens alle afhankelijkheden in één keer:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

In omgevingen zonder toegang tot PyPI (bijvoorbeeld een air‑gapped CI‑runner of een streng beveiligde server), download de wheel voor uw platform en installeer deze vanuit een lokaal bestand.

Download de wheel die overeenkomt met uw besturingssysteem en CPU‑architectuur vanaf de [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) pagina:

| Platform | Wheel-bestandsnaam eindigt op | Oudste systeem |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Sinds 26.10 geven de bestandsnamen het oudste systeem aan waarop elk wheel draait, zodat pip 20.3 of hoger een ouder wheel direct weigert in plaats van een runtime te installeren die niet kan starten. Wheels tot en met 26.1 waren getagd met `manylinux1_x86_64`, `macosx_10_14_x86_64` en `macosx_11_0_arm64`, en bevatten een 32-bit Windows‑wheel (`win32`); er is geen 32-bit wheel meer, dus gebruik een 64-bit Python op Windows.

Installeer het gedownloade bestand met `pip` (vervang de bestandsnaam door het wheel dat je hebt gedownload):

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

Geef de wheel‑bestandsnaam expliciet op: PowerShell breidt een `*`‑wildcard niet uit voor een native opdracht, waardoor `pip install groupdocs_signature_net-*.whl` daar faalt.

## Verify the Installation

Bevestig dat het pakket geïnstalleerd en importeerbaar is:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

Je kunt de geïnstalleerde versie ook controleren met `pip`:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
