---
title: "Installation"
linkTitle: "Installation"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Installieren Sie GroupDocs.Signature for Python via .NET von PyPI, fixieren Sie es in requirements.txt, oder installieren Sie ein vorab heruntergeladenes Wheel für Offline-Umgebungen — und überprüfen Sie anschließend die Installation."
type: docs
url: /de/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET wird als eigenständiges Wheel verteilt, das die eingebettete .NET-Laufzeit enthält. Ein einzelnes `py3-none-{platform}` Wheel funktioniert über Python **3.5 – 3.14** hinweg auf Windows, Linux und macOS (Intel und Apple Silicon). Auf Windows wird nichts Weiteres benötigt; Linux und macOS benötigen einige Systempakete, die unten aufgeführt sind.

Bevor Sie installieren, prüfen Sie die [Systemanforderungen](https://docs.groupdocs.com/signature/python-net/system-requirements/). Die Wheels benötigen Linux mit glibc 2.27 oder neuer, oder macOS 12 oder neuer, sowie pip 20.3 oder neuer zur Installation. Unter Linux installieren Sie ICU, fontconfig, `libgdiplus` und die Microsoft Core Fonts; unter macOS installieren Sie `mono-libgdiplus`.

## Install Package from PyPI

Alle Pakete werden bei [PyPI](https://pypi.org/project/groupdocs-signature-net/) gehostet. Installieren Sie die neueste Version mit `pip`:

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

Um eine bestehende Installation auf die neueste Version zu aktualisieren, fügen Sie das `--upgrade` Flag hinzu:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

Die Verwendung einer [virtuellen Umgebung](https://docs.python.org/3/library/venv.html) wird empfohlen, damit das Paket und seine Abhängigkeiten von Ihrem System‑Python isoliert bleiben. Siehe die [Schnellstart‑Anleitung](/signature/python-net/guides/quick-start-guide/) für die `venv`‑Einrichtungsschritte.

## Add the Package to `requirements.txt`

Für reproduzierbare Builds sollten Sie die Version in der `requirements.txt`‑Datei Ihres Projekts festlegen:

```text
groupdocs-signature-net==26.10.0
```

Installieren Sie dann alle Abhängigkeiten auf einmal:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

In Umgebungen ohne Zugriff auf PyPI (z. B. ein luftdichter CI‑Runner oder ein abgesichertes Server), laden Sie das Wheel für Ihre Plattform herunter und installieren Sie es aus einer lokalen Datei.

Laden Sie das Wheel, das zu Ihrem Betriebssystem und Ihrer CPU‑Architektur passt, von der Seite der [GroupDocs.Signature‑Releases](https://releases.groupdocs.com/signature/python-net/) herunter:

| Plattform | Wheel‑Dateiname endet mit | Ältestes System |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Seit Version 26.10 geben die Dateinamen das älteste System an, auf dem jedes Wheel läuft, sodass pip 20.3 oder neuer ein älteres Wheel bereits im Vorfeld ablehnt, anstatt eine Laufzeit zu installieren, die nicht starten kann. Wheels bis Version 26.1 wurden mit `manylinux1_x86_64`, `macosx_10_14_x86_64` und `macosx_11_0_arm64` gekennzeichnet und enthielten ein 32‑Bit‑Windows‑Wheel (`win32`); ein 32‑Bit‑Wheel gibt es nicht mehr, verwenden Sie daher ein 64‑Bit‑Python unter Windows.

Installieren Sie die heruntergeladene Datei mit `pip` (ersetzen Sie den Dateinamen durch das heruntergeladene Wheel):

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

Benennen Sie die Wheel‑Datei explizit: PowerShell expandiert ein `*`‑Wildcard für einen nativen Befehl nicht, sodass `pip install groupdocs_signature_net-*.whl` dort fehlschlägt.

## Verify the Installation

Bestätigen Sie, dass das Paket installiert und importierbar ist:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

Sie können die installierte Version auch mit `pip` prüfen:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
