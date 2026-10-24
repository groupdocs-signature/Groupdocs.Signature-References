---
title: "Kurulum"
linkTitle: "Installation"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "GroupDocs.Signature for Python via .NET'i PyPI'dan kurun, requirements.txt içinde sabitleyin veya çevrim dışı ortamlar için önceden indirilmiş bir tekerlek (wheel) kurun — ardından kurulumu doğrulayın."
type: docs
url: /tr/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET, gömülü .NET çalışma zamanını içeren kendi içinde bütünleşik bir tekerlek (wheel) olarak dağıtılır. Tek bir `py3-none-{platform}` tekerleği, Windows, Linux ve macOS (Intel ve Apple Silicon) üzerinde Python **3.5 – 3.14** sürümleriyle çalışır. Windows için başka bir şey gerekmez; Linux ve macOS için aşağıda listelenen birkaç sistem paketi gerekir.

Kurulum yapmadan önce, [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/) sayfasını inceleyin. Tekerleklerin kurulumu için Linux'ta glibc 2.27 veya daha yeni, macOS'ta 12 veya daha yeni ve pip 20.3 veya daha yeni gerekir. Linux'ta ICU, fontconfig, `libgdiplus` ve Microsoft temel yazı tiplerini; macOS'ta ise `mono-libgdiplus` paketini kurun.

## Install Package from PyPI

Tüm paketler [PyPI](https://pypi.org/project/groupdocs-signature-net/) üzerinde barındırılır. En son sürümü `pip` ile kurun:

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

Mevcut kurulumu en yeni sürüme yükseltmek için `--upgrade` bayrağını ekleyin:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

[virtual environment](https://docs.python.org/3/library/venv.html) kullanılması önerilir, böylece paket ve bağımlılıkları sistem Python'unuzdan izole kalır. `venv` kurulum adımları için [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) sayfasına bakın.

## Add the Package to `requirements.txt`

Tekrarlanabilir derlemeler için, projenizin `requirements.txt` dosyasında sürümü sabitleyin:

```text
groupdocs-signature-net==26.10.0
```

Ardından tüm bağımlılıkları bir kerede kurun:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

PyPI'ye erişimi olmayan ortamlarda (örneğin, hava geçidi olmayan bir CI çalıştırıcısı veya kilitli bir sunucu), platformunuz için tekerleği indirin ve yerel bir dosyadan kurun.

İşletim sisteminize ve CPU mimarinize uygun tekerleği [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) sayfasından indirin:

| Platform | Wheel dosya adı şu ile bitiyor | En eski sistem |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

26.10'dan itibaren dosya adları, her wheel'ın çalıştığı en eski sistemi belirtir, bu yüzden pip 20.3 veya daha yenisi, baştan bir eski sürümü reddeder ve başlatılamayan bir çalışma zamanını kurmaz. 26.1'e kadar olan wheel'lar `manylinux1_x86_64`, `macosx_10_14_x86_64` ve `macosx_11_0_arm64` etiketine sahipti ve 32-bit Windows wheel'ı (`win32`) içeriyordu; artık 32-bit wheel yok, bu yüzden Windows'ta 64-bit Python kullanın.

`pip` ile indirilen dosyayı kurun (dosya adını indirdiğiniz wheel ile değiştirin):

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

Wheel dosyasını açıkça adlandırın: PowerShell, yerel bir komut için `*` joker karakterini genişletmez, bu yüzden `pip install groupdocs_signature_net-*.whl` burada başarısız olur.

## Verify the Installation

Paketin kurulu ve içe aktarılabilir olduğunu doğrulayın:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

`pip` ile kurulu sürümü de kontrol edebilirsiniz:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
