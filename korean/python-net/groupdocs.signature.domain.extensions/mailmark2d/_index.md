---
title: "Mailmark2D 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "Royal Mail 2D Mailmark에 삽입된 텍스트를 인코딩하고 디코딩합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Royal Mail 2D Mailmark에 삽입된 텍스트를 인코딩하고 디코딩합니다.

Mailmark2D 타입은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | 기본 기본 및 보조 데이터 값으로 Royal Mail Mailmark 결합 데이터를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | 이 객체의 복사본을 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | 항목의 클래스. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | 고객이 사용할 수 있는 선택적 공간. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | DataMatrix 바코드의 인코드 모드. 기본값: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | 2D Mailmark 타입은 Data Matrix 바코드의 크기를 정의합니다. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | 이 속성은 DPS가 포함된 배송 주소 우편번호를 보유합니다. 내륙 주소의 경우 영역(1‑2자), 구역(1‑2자), 섹터(1자), 유닛(2자), 그리고 DPS(2자)로 구성되며, 유효한 PAF® 형식을 따라야 하고 최대 길이는 9자입니다. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드의 식별자입니다. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | Supply Chain ID 내의 고유 항목 식별자로, 최소 90일 동안 고유 식별을 위해 모든 Mailmark 바코드에 필요합니다 (최대 값: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | DPS 없이 반송자 우편 코드입니다. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | 요청된 반송자 서비스 수준을 나타내는 플래그입니다. 최대 길이는 1입니다. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | 메일링에 포함된 고객의 고유 그룹입니다. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | UPU 국가 ID (최대 길이: 4자)입니다. |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | 각 정보 유형 ID와 관련된 바코드 버전 식별자입니다. |

### 또 보기
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
