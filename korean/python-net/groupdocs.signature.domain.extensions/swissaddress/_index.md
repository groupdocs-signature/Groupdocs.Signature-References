---
title: "SwissAddress 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "채권자 또는 채무자의 주소를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

채권자 또는 채무자의 주소를 나타냅니다.

거리, 건물 번호, 우편 번호 및 도시(구조화된 주소 유형)를 설정하거나 주소 라인 1 및 2(결합된 주소 요소 유형)를 설정할 수 있습니다.

SwissAddress 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | 주소 라인 1은 거리 이름, 건물 번호 또는 사서함을 포함하며, 선택 사항이며 결합된 요소 주소에만 사용됩니다. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | 주소 라인 2는 우편 번호와 도시를 포함하며, 결합된 요소 주소에 대해 필수입니다. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | 두 글자의 ISO 국가 코드입니다. 전체 주소에 null 또는 빈 값이 포함되지 않는 한 국가 코드는 필수입니다. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | 건물 번호입니다. 이 필드는 구조화된 주소에만 사용되며 선택 사항입니다. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | 이름으로, 자연인의 이름과 성 또는 법인의 회사명을 의미합니다. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | 우편 번호입니다. 이 필드는 구조화된 주소에만 사용됩니다. 이 유형에서는 필수입니다. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | 건물 번호 없이 주소의 거리이며, 선택 사항이고 구조화된 주소에만 사용됩니다. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | 도시 또는 시이며, 구조화된 주소에만 사용되고 이 유형에서는 필수입니다. |

### 또 보기
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
