---
title: "설치"
linkTitle: "Installation"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "PyPI에서 GroupDocs.Signature for Python via .NET를 설치하고, requirements.txt에 고정하거나 오프라인 환경을 위해 미리 다운로드한 wheel을 설치한 후 설치를 확인하십시오."
type: docs
url: /ko/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET는 포함된 .NET 런타임을 번들링한 자체 포함 wheel로 배포됩니다. 단일 `py3-none-{platform}` wheel은 Windows, Linux, macOS(Intel 및 Apple Silicon)에서 Python **3.5 – 3.14** 전체에 걸쳐 작동합니다. Windows에서는 별도의 것이 필요 없으며, Linux와 macOS는 아래에 나열된 몇 가지 시스템 패키지가 필요합니다.

설치하기 전에, [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/)를 검토하십시오. 휠은 Linux( glibc 2.27 이상) 또는 macOS 12 이상이 필요하며, 설치하려면 pip 20.3 이상이 필요합니다. Linux에서는 ICU, fontconfig, `libgdiplus` 및 Microsoft core fonts를 설치하고, macOS에서는 `mono-libgdiplus`를 설치하십시오.

## Install Package from PyPI

모든 패키지는 [PyPI](https://pypi.org/project/groupdocs-signature-net/)에 호스팅됩니다. 최신 버전은 `pip`으로 설치하십시오:

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

기존 설치를 최신 릴리스로 업그레이드하려면 `--upgrade` 플래그를 추가하십시오:

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

시스템 Python과 격리된 상태를 유지하려면 [virtual environment](https://docs.python.org/3/library/venv.html)를 사용하는 것이 권장됩니다. `venv` 설정 단계는 [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)를 참고하십시오.

## Add the Package to `requirements.txt`

재현 가능한 빌드를 위해 프로젝트의 `requirements.txt`에 버전을 고정하십시오:

```text
groupdocs-signature-net==26.10.0
```

그런 다음 모든 종속성을 한 번에 설치하십시오:

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

PyPI에 접근할 수 없는 환경(예: 에어갭 CI 러너 또는 잠금된 서버)에서는 플랫폼에 맞는 휠을 다운로드하고 로컬 파일에서 설치하십시오.

운영 체제와 CPU 아키텍처에 맞는 휠을 [GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) 페이지에서 다운로드하십시오:

| 플랫폼 | 휠 파일 이름은 다음으로 끝납니다 | 최소 지원 시스템 |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27 (Ubuntu 18.04, Debian 10, RHEL 8) |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

26.10부터 파일 이름에 각 휠이 실행되는 최소 시스템이 표시되므로, pip 20.3 이상은 실행할 수 없는 오래된 휠을 앞서 거부합니다. 26.1까지의 휠은 `manylinux1_x86_64`, `macosx_10_14_x86_64` 및 `macosx_11_0_arm64`로 태그되었으며, 32비트 Windows 휠(`win32`)도 포함되었습니다; 이제는 32비트 휠이 없으므로 Windows에서는 64비트 Python을 사용하십시오.

다운로드한 파일을 `pip`으로 설치하십시오(파일 이름을 다운로드한 휠 이름으로 교체하십시오):

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

휠 파일 이름을 명시적으로 지정하십시오: PowerShell은 기본 명령에 대해 `*` 와일드카드를 확장하지 않으므로 `pip install groupdocs_signature_net-*.whl`이 여기서 실패합니다.

## Verify the Installation

패키지가 설치되고 가져올 수 있는지 확인하십시오:

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

`pip`으로 설치된 버전을 확인할 수도 있습니다:

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
