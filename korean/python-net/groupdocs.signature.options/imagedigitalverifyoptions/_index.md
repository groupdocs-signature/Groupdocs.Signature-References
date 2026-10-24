---
title: "ImageDigitalVerifyOptions 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "래스터 이미지에서 디지털 서명을 검증하기 위한 옵션을 보관합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

래스터 이미지에서 디지털 서명을 검증하기 위한 옵션을 보관합니다.

ImageDigitalVerifyOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | 래스터 이미지에서 디지털(스테가노그래피) 서명을 검증하기 위해 ImageDigitalVerifyOptions 클래스의 새 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | AnalyzePercentageDigitalSignature가 반환하는 확률(0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | 부분 추출을 위한 감지 임계값 퍼센트(0-100). 기본값은 75입니다. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | 서명을 삽입하는 데 사용된 비밀번호. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | 이 속성은 최대 정확도를 위해 전체 데이터 추출(AnalyzePercentageDigitalSignature)이 수행되는지 여부를 결정합니다. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | 각 문서 페이지를 검증할지 여부를 나타내는 플래그. 기본값은 True입니다. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | 대체 서명 옵션 검증을 위한 추가 확장자. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | 유효한 속성 플래그. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | 검증할 문서 페이지 번호; 설정되지 않으면 문서의 모든 페이지가 첫 번째 발생에 대해 검증됩니다(최소값은 1). (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | 검증할 페이지를 지정하기 위한 페이지 옵션입니다. (상속됨: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | 머리글/바닥글에 서명을 검증하는 데 사용되는 문서 레이아웃의 도형 위치입니다. (상속됨: [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### 또 보기
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
