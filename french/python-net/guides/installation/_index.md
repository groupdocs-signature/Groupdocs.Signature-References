---
title: "Installation"
linkTitle: "Installation"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Installez GroupDocs.Signature for Python via .NET depuis PyPI, épinglez‑le dans requirements.txt, ou installez une roue pré‑téléchargée pour les environnements hors ligne — puis vérifiez l'installation."
type: docs
url: /fr/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET est distribué sous forme de roue autonome qui regroupe le runtime .NET intégré. Une seule roue `py3-none-{platform}` fonctionne avec Python **3.5 – 3.14** sur Windows, Linux et macOS (Intel et Apple Silicon). Rien d'autre n'est nécessaire sous Windows ; Linux et macOS nécessitent quelques paquets système, listés ci‑dessous.

Avant d'installer, consultez les [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Les roues nécessitent Linux avec glibc 2.27 ou plus récent, ou macOS 12 ou plus récent, et pip 20.3 ou plus récent pour l'installation. Sous Linux, installez ICU, fontconfig, `libgdiplus` et les polices Microsoft core ; sous macOS, installez `mono-libgdiplus`.

## Install Package from PyPI

Tous les paquets sont hébergés sur [PyPI](https://pypi.org/project/groupdocs-signature-net/). Installez la dernière version avec `pip` :

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

Pour mettre à jour une installation existante vers la dernière version, ajoutez le drapeau `--upgrade` :

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

L'utilisation d'un [virtual environment](https://docs.python.org/3/library/venv.html) est recommandée afin que le paquet et ses dépendances restent isolés de votre Python système. Consultez le [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) pour les étapes de configuration du `venv`.

## Add the Package to `requirements.txt`

Pour des builds reproductibles, épinglez la version dans le `requirements.txt` de votre projet :

```text
groupdocs-signature-net==26.10.0
```

Installez ensuite toutes les dépendances en une fois :

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Dans les environnements sans accès à PyPI (par exemple, un runner CI isolé ou un serveur verrouillé), téléchargez la roue pour votre plateforme et installez‑la depuis un fichier local.

Téléchargez la roue correspondant à votre système d'exploitation et à votre architecture CPU depuis la page des [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) :

| Plateforme | Le nom du fichier wheel se termine par | Système le plus ancien |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Depuis la version 26.10, les noms de fichiers indiquent le système le plus ancien sur lequel chaque wheel s'exécute, ainsi pip 20.3 ou plus récent refuse d'emblée une version plus ancienne au lieu d'installer un runtime qui ne peut pas démarrer. Les wheels jusqu'à la version 26.1 étaient étiquetées `manylinux1_x86_64`, `macosx_10_14_x86_64` et `macosx_11_0_arm64`, et comprenaient une wheel Windows 32 bits (`win32`) ; il n'existe plus de wheel 32 bits, utilisez donc un Python 64 bits sous Windows.

Installez le fichier téléchargé avec `pip` (remplacez le nom du fichier par la wheel que vous avez téléchargée ):

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

Nommez explicitement le fichier wheel : PowerShell n'expande pas le caractère générique `*` pour une commande native, ainsi `pip install groupdocs_signature_net-*.whl` échoue dans ce cas.

## Verify the Installation

Confirmez que le paquet est installé et importable :

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

Vous pouvez également vérifier la version installée avec `pip` :

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
