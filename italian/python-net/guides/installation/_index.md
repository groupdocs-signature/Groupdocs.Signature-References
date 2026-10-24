---
title: "Installazione"
linkTitle: "Installation"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Installa GroupDocs.Signature for Python via .NET da PyPI, fissalo in requirements.txt, oppure installa una wheel pre‑scaricata per ambienti offline — poi verifica l'installazione."
type: docs
url: /it/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET è distribuito come una wheel autonoma che include il runtime .NET incorporato. Una singola wheel `py3-none-{platform}` funziona con Python **3.5 – 3.14** su Windows, Linux e macOS (Intel e Apple Silicon). Non è necessario altro su Windows; Linux e macOS richiedono alcuni pacchetti di sistema, elencati di seguito.

Prima di installare, consulta i [Requisiti di sistema](https://docs.groupdocs.com/signature/python-net/system-requirements/). Le wheel richiedono Linux con glibc 2.27 o superiore, o macOS 12 o superiore, e pip 20.3 o superiore per l'installazione. Su Linux, installa ICU, fontconfig, `libgdiplus` e i font core di Microsoft; su macOS, installa `mono-libgdiplus`.

## Install Package from PyPI

Tutti i pacchetti sono ospitati su [PyPI](https://pypi.org/project/groupdocs-signature-net/). Installa l'ultima versione con `pip`:

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

Per aggiornare un'installazione esistente all'ultima versione, aggiungi il flag `--upgrade`:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

È consigliato usare un [ambiente virtuale](https://docs.python.org/3/library/venv.html) così il pacchetto e le sue dipendenze rimangono isolate dal Python di sistema. Consulta la [Guida rapida](/signature/python-net/guides/quick-start-guide/) per i passaggi di configurazione del `venv`.

## Add the Package to `requirements.txt`

Per build riproducibili, fissa la versione nel file `requirements.txt` del tuo progetto:

```text
groupdocs-signature-net==26.10.0
```

Quindi installa tutte le dipendenze in una volta:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

In ambienti senza accesso a PyPI (ad esempio, un runner CI isolato o un server bloccato), scarica la wheel per la tua piattaforma e installala da un file locale.

Scarica la wheel che corrisponde al tuo sistema operativo e all'architettura CPU dalla pagina dei [rilasci GroupDocs.Signature](https://releases.groupdocs.com/signature/python-net/) :

| Piattaforma | Il nome del file wheel termina con | Sistema più vecchio |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Dal 26.10 i nomi dei file indicano il sistema più vecchio su cui ogni wheel può essere eseguito, quindi pip 20.3 o versioni successive rifiuta subito una wheel più vecchia invece di installare un runtime che non può avviarsi. Le wheel fino alla 26.1 erano etichettate `manylinux1_x86_64`, `macosx_10_14_x86_64` e `macosx_11_0_arm64`, e includevano una wheel Windows a 32 bit (`win32`); non esiste più una wheel a 32 bit, quindi usa Python a 64 bit su Windows.

Installa il file scaricato con `pip` (sostituisci il nome del file con la wheel che hai scaricato):

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

Specifica esplicitamente il nome del file wheel: PowerShell non espande il carattere jolly `*` per un comando nativo, quindi `pip install groupdocs_signature_net-*.whl` fallisce.

## Verify the Installation

Conferma che il pacchetto sia installato e importabile:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

Puoi anche verificare la versione installata con `pip`:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
