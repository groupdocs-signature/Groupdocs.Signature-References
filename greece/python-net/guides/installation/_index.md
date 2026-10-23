---
title: "Εγκατάσταση"
linkTitle: "Installation"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Εγκαταστήστε το GroupDocs.Signature for Python via .NET από το PyPI, κλειδώστε το στο requirements.txt, ή εγκαταστήστε ένα προ-κατεβασμένο wheel για περιβάλλοντα εκτός σύνδεσης — στη συνέχεια επαληθεύστε την εγκατάσταση."
type: docs
url: /el/python-net/guides/installation/
is_root: false
weight: 10
---


Το GroupDocs.Signature for Python via .NET διανέμεται ως ένα αυτόνομο wheel που περιλαμβάνει το ενσωματωμένο .NET runtime. Ένα μόνο wheel `py3-none-{platform}` λειτουργεί σε Python **3.5 – 3.14** στα Windows, Linux και macOS (Intel και Apple Silicon). Δεν απαιτείται τίποτα άλλο στα Windows· τα Linux και macOS χρειάζονται μερικά πακέτα συστήματος, που αναφέρονται παρακάτω.

Πριν την εγκατάσταση, εξετάστε τις [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Τα wheels απαιτούν Linux με glibc 2.27 ή νεότερο, ή macOS 12 ή νεότερο, και pip 20.3 ή νεότερο για εγκατάσταση. Σε Linux, εγκαταστήστε ICU, fontconfig, `libgdiplus` και τις γραμματοσειρές Microsoft core· σε macOS, εγκαταστήστε `mono-libgdiplus`.

## Install Package from PyPI

Όλα τα πακέτα φιλοξενούνται στο [PyPI](https://pypi.org/project/groupdocs-signature-net/). Εγκαταστήστε την τελευταία έκδοση με `pip`:

{{< tabs \"install-from-pypi\">}}
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

Για να αναβαθμίσετε μια υπάρχουσα εγκατάσταση στην πιο πρόσφατη έκδοση, προσθέστε τη σημαία `--upgrade`:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

Η χρήση ενός [virtual environment](https://docs.python.org/3/library/venv.html) συνιστάται ώστε το πακέτο και οι εξαρτήσεις του παραμείνουν απομονωμένα από το σύστημα Python σας. Δείτε τον [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) για τα βήματα ρύθμισης του `venv`.

## Add the Package to `requirements.txt`

Για επαναλήψιμες κατασκευές, κλειδώστε την έκδοση στο `requirements.txt` του έργου σας:

```text
groupdocs-signature-net==26.10.0
```

Στη συνέχεια εγκαταστήστε όλες τις εξαρτήσεις ταυτόχρονα:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Σε περιβάλλοντα χωρίς πρόσβαση στο PyPI (π.χ., ένας απομονωμένος CI runner ή ένας κλειδωμένος διακομιστής), κατεβάστε το wheel για την πλατφόρμα σας και εγκαταστήστε το από τοπικό αρχείο.

Κατεβάστε το wheel που ταιριάζει με το λειτουργικό σας σύστημα και την αρχιτεκτονική CPU από τη σελίδα των [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) :

| Πλατφόρμα | Το όνομα του αρχείου wheel τελειώνει με | Παλαιότερο σύστημα |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Από την έκδοση 26.10 τα ονόματα αρχείων δηλώνουν το παλαιότερο σύστημα στο οποίο τρέχει κάθε wheel, έτσι το pip 20.3 ή νεότερο απορρίπτει ένα παλαιότερο εκ των προτέρων αντί να εγκαταστήσει ένα runtime που δεν μπορεί να ξεκινήσει. Τα wheels μέχρι την 26.1 είχαν ετικέτες `manylinux1_x86_64`, `macosx_10_14_x86_64` και `macosx_11_0_arm64`, και περιελάμβαναν ένα 32‑bit Windows wheel (`win32`); δεν υπάρχει πλέον 32‑bit wheel, οπότε χρησιμοποιήστε Python 64‑bit στα Windows.

Εγκαταστήστε το ληφθέν αρχείο με `pip` (αντικαταστήστε το όνομα του αρχείου με το wheel που κατεβάσατε):

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

Ονομάστε το αρχείο wheel ρητά: Το PowerShell δεν επεκτείνει το σύμβολο μπαλαντέρ `*` για μια εντολή native, έτσι το `pip install groupdocs_signature_net-*.whl` αποτυγχάνει εκεί.

## Verify the Installation

Επιβεβαιώστε ότι το πακέτο είναι εγκατεστημένο και μπορεί να εισαχθεί:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

Μπορείτε επίσης να ελέγξετε την εγκατεστημένη έκδοση με `pip`:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
