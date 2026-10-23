---
title: "التثبيت"
linkTitle: "Installation"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "قم بتثبيت GroupDocs.Signature for Python via .NET من PyPI، وثبّته في requirements.txt، أو قم بتثبيت حزمة wheel مُحمّلة مسبقًا للبيئات غير المتصلة — ثم تحقق من التثبيت."
type: docs
url: /ar/python-net/guides/installation/
is_root: false
weight: 10
---


يتم توزيع GroupDocs.Signature for Python via .NET كحزمة wheel ذاتية المحتوى تُضمّن بيئة تشغيل .NET المدمجة. تعمل حزمة wheel واحدة `py3-none-{platform}` عبر Python **3.5 – 3.14** على Windows وLinux وmacOS (Intel وApple Silicon). لا يلزم أي شيء آخر على Windows؛ بينما تحتاج Linux وmacOS إلى بعض حزم النظام المذكورة أدناه.

قبل التثبيت، راجع [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). تحتاج الحزم wheel إلى Linux مع glibc 2.27 أو أحدث، أو macOS 12 أو أحدث، وpip 20.3 أو أحدث للتثبيت. على Linux، قم بتثبيت ICU وfontconfig و`libgdiplus` وخطوط Microsoft الأساسية؛ وعلى macOS، قم بتثبيت `mono-libgdiplus`.

## Install Package from PyPI

جميع الحزم مستضافة على [PyPI](https://pypi.org/project/groupdocs-signature-net/). قم بتثبيت أحدث نسخة باستخدام `pip`:

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

لترقية تثبيت موجود إلى أحدث إصدار، أضف العلامة `--upgrade`:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

يُوصى باستخدام [virtual environment](https://docs.python.org/3/library/venv.html) بحيث يبقى الحزمة واعتمادياتها معزولة عن Python النظام الخاص بك. راجع [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) لخطوات إعداد `venv`.

## Add the Package to `requirements.txt`

لضمان بناءات قابلة لإعادة الإنتاج، ثبّت النسخة في ملف `requirements.txt` الخاص بمشروعك:

```text
groupdocs-signature-net==26.10.0
```

ثم قم بتثبيت جميع الاعتماديات مرة واحدة:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

في البيئات التي لا يمكن الوصول إلى PyPI (على سبيل المثال، مُنفّذ CI معزول أو خادم مقفل)، قم بتنزيل حزمة wheel الخاصة بمنصتك وتثبيتها من ملف محلي.

قم بتنزيل حزمة wheel التي تتطابق مع نظام التشغيل ومعمارية المعالج الخاصة بك من صفحة [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) :

| المنصة | اسم ملف العجلة ينتهي بـ | أقدم نظام |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

منذ الإصدار 26.10 تُظهر أسماء الملفات أقدم نظام يعمل عليه كل ملف عجلة، لذا يرفض pip 20.3 أو أحدث ملفًا أقدم مباشرةً بدلاً من تثبيت بيئة تشغيل لا يمكنها البدء. كانت العجلات حتى الإصدار 26.1 مُوسومة بـ `manylinux1_x86_64` و `macosx_10_14_x86_64` و `macosx_11_0_arm64`، وشملت عجلة Windows 32‑بت (`win32`); لم تعد هناك عجلة 32‑بت، لذا استخدم Python 64‑بت على Windows.

قم بتثبيت الملف الذي تم تنزيله باستخدام `pip` (استبدل اسم الملف بالعجلة التي قمت بتنزيلها):

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

حدد اسم ملف العجلة صراحةً: لا يقوم PowerShell بتوسيع حرف البدل `*` لأمر أصلي، لذا فشل `pip install groupdocs_signature_net-*.whl` هناك.

## Verify the Installation

تأكد من أن الحزمة مثبتة ويمكن استيرادها:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

يمكنك أيضًا التحقق من الإصدار المثبت باستخدام `pip`:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
