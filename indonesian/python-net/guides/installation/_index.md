---
title: "Instalasi"
linkTitle: "Installation"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Instal GroupDocs.Signature for Python via .NET dari PyPI, tetapkan versinya di requirements.txt, atau instal wheel yang sudah diunduh sebelumnya untuk lingkungan offline — kemudian verifikasi instalasinya."
type: docs
url: /id/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET didistribusikan sebagai wheel mandiri yang menyertakan runtime .NET yang terintegrasi. Satu wheel `py3-none-{platform}` dapat bekerja pada Python **3.5 – 3.14** di Windows, Linux, dan macOS (Intel dan Apple Silicon). Tidak ada hal lain yang diperlukan di Windows; Linux dan macOS memerlukan beberapa paket sistem, yang tercantum di bawah.

Sebelum menginstal, tinjau [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Wheel memerlukan Linux dengan glibc 2.27 atau lebih baru, atau macOS 12 atau lebih baru, serta pip 20.3 atau lebih baru untuk instalasi. Di Linux, instal ICU, fontconfig, `libgdiplus`, dan font inti Microsoft; di macOS, instal `mono-libgdiplus`.

## Install Package from PyPI

Semua paket dihosting di [PyPI](https://pypi.org/project/groupdocs-signature-net/). Instal versi terbaru dengan `pip`:

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

Untuk meningkatkan instalasi yang ada ke rilis terbaru, tambahkan flag `--upgrade`:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

Menggunakan [virtual environment](https://docs.python.org/3/library/venv.html) disarankan agar paket dan dependensinya tetap terisolasi dari Python sistem Anda. Lihat [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) untuk langkah-langkah penyiapan `venv`.

## Add the Package to `requirements.txt`

Untuk build yang dapat direproduksi, tetapkan versi di `requirements.txt` proyek Anda:

```text
groupdocs-signature-net==26.10.0
```

Kemudian instal semua dependensi sekaligus:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Di lingkungan yang tidak memiliki akses ke PyPI (misalnya, runner CI yang terisolasi atau server dengan akses terbatas), unduh wheel untuk platform Anda dan instal dari file lokal.

Unduh wheel yang cocok dengan sistem operasi dan arsitektur CPU Anda dari halaman [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/):

| Platform | Nama file wheel berakhir dengan | Sistem tertua |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

Sejak 26.10 nama file menyatakan sistem tertua yang dijalankan oleh setiap wheel, sehingga pip 20.3 atau yang lebih baru menolak yang lebih lama di awal alih-alih menginstal runtime yang tidak dapat dijalankan. Wheel hingga 26.1 ditandai dengan `manylinux1_x86_64`, `macosx_10_14_x86_64`, dan `macosx_11_0_arm64`, serta menyertakan wheel Windows 32-bit (`win32`); tidak ada lagi wheel 32-bit, jadi gunakan Python 64-bit di Windows.

Instal file yang diunduh dengan `pip` (ganti nama file dengan wheel yang Anda unduh):

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

Berikan nama file wheel secara eksplisit: PowerShell tidak memperluas wildcard `*` untuk perintah native, sehingga `pip install groupdocs_signature_net-*.whl` gagal di sana.

## Verify the Installation

Pastikan paket sudah terinstal dan dapat diimpor:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

Anda juga dapat memeriksa versi yang terinstal dengan `pip`:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
