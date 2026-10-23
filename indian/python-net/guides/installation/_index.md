---
title: "स्थापना"
linkTitle: "Installation"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "PyPI से GroupDocs.Signature for Python via .NET इंस्टॉल करें, इसे requirements.txt में पिन करें, या ऑफ़लाइन वातावरण के लिए पहले से डाउनलोड किया हुआ व्हील इंस्टॉल करें — फिर स्थापना की पुष्टि करें।"
type: docs
url: /hi/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET एक स्व-निहित व्हील के रूप में वितरित किया जाता है जो एम्बेडेड .NET रनटाइम को बंडल करता है। एक ही `py3-none-{platform}` व्हील Windows, Linux, और macOS (Intel और Apple Silicon) पर Python **3.5 – 3.14** के साथ काम करता है। Windows पर कुछ और आवश्यक नहीं है; Linux और macOS को नीचे सूचीबद्ध कुछ सिस्टम पैकेजों की आवश्यकता होती है।

इंस्टॉल करने से पहले, [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/) देखें। व्हील्स को इंस्टॉल करने के लिए Linux (glibc 2.27 या नया) या macOS 12 या नया, और pip 20.3 या नया चाहिए। Linux पर, ICU, fontconfig, `libgdiplus` और Microsoft कोर फ़ॉन्ट्स इंस्टॉल करें; macOS पर, `mono‑libgdiplus` इंस्टॉल करें।

## Install Package from PyPI

सभी पैकेज [PyPI](https://pypi.org/project/groupdocs-signature-net/) पर होस्ट किए गए हैं। नवीनतम संस्करण `pip` के साथ इंस्टॉल करें:

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

मौजूदा इंस्टॉलेशन को नवीनतम रिलीज़ में अपग्रेड करने के लिए, `--upgrade` फ़्लैग जोड़ें:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

[virtual environment](https://docs.python.org/3/library/venv.html) का उपयोग करने की सलाह दी जाती है ताकि पैकेज और उसकी निर्भरताएँ आपके सिस्टम Python से अलग रहें। `venv` सेटअप चरणों के लिए [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) देखें।

## Add the Package to `requirements.txt`

पुनरुत्पादनीय बिल्ड्स के लिए, अपने प्रोजेक्ट की `requirements.txt` में संस्करण पिन करें:

```text
groupdocs-signature-net==26.10.0
```

फिर सभी निर्भरताएँ एक साथ इंस्टॉल करें:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

ऐसे वातावरण में जहाँ PyPI तक पहुँच नहीं है (उदाहरण के लिए, एयर‑गैप्ड CI रनर या लॉक‑डाउन्ड सर्वर), अपने प्लेटफ़ॉर्म के लिए व्हील डाउनलोड करें और उसे स्थानीय फ़ाइल से इंस्टॉल करें।

अपने ऑपरेटिंग सिस्टम और CPU आर्किटेक्चर से मेल खाने वाला व्हील [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) पेज से डाउनलोड करें:

| प्लेटफ़ॉर्म | व्हील फ़ाइल नाम समाप्त होता है | सबसे पुराना सिस्टम |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

26.10 से फ़ाइल नाम यह दर्शाते हैं कि प्रत्येक व्हील किस सबसे पुराने सिस्टम पर चलती है, इसलिए pip 20.3 या उससे नया पहले ही पुराने सिस्टम की व्हील को अस्वीकार कर देता है बजाय ऐसे रनटाइम को स्थापित करने के जो शुरू नहीं हो सकता। 26.1 तक की व्हील को `manylinux1_x86_64`, `macosx_10_14_x86_64` और `macosx_11_0_arm64` टैग किया गया था, और इसमें 32-बिट Windows व्हील (`win32`) शामिल था; अब 32-बिट व्हील नहीं है, इसलिए Windows पर 64-बिट Python का उपयोग करें।

डाउनलोड की गई फ़ाइल को `pip` के साथ स्थापित करें (फ़ाइल नाम को उस व्हील से बदलें जिसे आपने डाउनलोड किया है):

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

व्हील फ़ाइल का नाम स्पष्ट रूप से दें: PowerShell मूल कमांड के लिए `*` वाइल्डकार्ड का विस्तार नहीं करता, इसलिए `pip install groupdocs_signature_net-*.whl` वहाँ विफल हो जाता है।

## Verify the Installation

पैकेज स्थापित और आयात योग्य है यह पुष्टि करें:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

आप `pip` के साथ स्थापित संस्करण भी जांच सकते हैं:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
