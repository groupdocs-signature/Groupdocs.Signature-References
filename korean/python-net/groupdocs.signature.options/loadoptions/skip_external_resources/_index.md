---
title: "skip_external_resources 속성"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서가 외부 리소스를 로드하는 것을 중단하는 플래그입니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

문서가 외부 리소스를 로드하지 않도록 하는 플래그입니다. 기본값은 True이며, [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/)와 일치하는 경우를 제외하고 외부 리소스는 로드되지 않습니다.

문서는 외부에 저장된 리소스를 참조할 수 있습니다. 예를 들어 연결된 이미지, INCLUDEPICTURE 필드로 삽입된 그림, 프레젠테이션 및 스프레드시트의 연결된 그림, SVG 이미지가 참조하는 이미지 및 스타일시트 등이 있습니다. 이러한 리소스를 로드하면 라이브러리가 해당 주소에 요청을 보냅니다. 신뢰할 수 없는 문서를 처리하는 서버에서는 문서가 이를 이용해 서버가 내부 주소로 요청을 보내도록 할 수 있으며(서버 측 요청 위조), UNC 또는 `file://` 경로는 Windows가 계정의 NTLM 자격 증명을 다른 호스트로 전송하게 할 수 있습니다. 오프라인 또는 에어갭 설치 환경에서는 요청이 실패하거나 시간 초과를 기다리게 됩니다.

건너뛴 리소스는 페이지 미리보기나 이미지로 저장된 문서에 그려지지 않으며, 이미지, 바코드 및 QR‑code 검색에서도 표시되지 않습니다. 이 속성을 False로 설정하는 것은 신뢰할 수 있는 문서에만 적용하고, 가능한 경우 [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) 로 특정 주소를 허용하는 것이 좋습니다.

이 설정은 워드 프로세싱 문서, 프레젠테이션, 스프레드시트 및 SVG 이미지에 적용되며, 아카이브 내부의 문서도 포함합니다. SVG 이미지의 경우 허용되지 않은 참조는 읽기 전에 이미지에서 제거되며, 올바른 XML 형식이 아닌 SVG 이미지는 거부됩니다. 이 설정은 인증서 폐기 검증, 타임스탬프 서버 또는 라이선스를 제어하지 않습니다.

이 속성은 반대 의미를 갖는 [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) 를 대체합니다.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### 또 보기
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
