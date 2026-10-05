---
title: Mailmark2D class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Encodes and decodes the text embedded in the Royal Mail 2D Mailmark."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Encodes and decodes the text embedded in the Royal Mail 2D Mailmark.

The Mailmark2D type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Initializes Royal Mail Mailmark combined data with default primary and secondary data values. |

### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | Returns a copy of this object. |

### Properties
| Property | Description |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | The class of the item. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | The optional space for use by customer. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | The encode mode of the DataMatrix barcode. Default value: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | The 2D Mailmark type defines the size of the Data Matrix barcode. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | The property holds the delivery address postcode with DPS, which for inland addresses consists of an area (1‑2 characters), district (1‑2 characters), sector (1 character), unit (2 characters), and DPS (2 characters), must follow a valid PAF® format, and has a maximum length of 9 characters. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | The identifier of the Royal Mail Mailmark barcode payload for each product type. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | The unique item identifier within the Supply Chain ID, required on every Mailmark barcode for unique identification for at least 90 days (max value: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | The Return to Sender Post Code without DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | The flag which indicates what level of Return to Sender service is being requested. Max length is 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | The unique group of customers involved in the mailing. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | The UPU Country ID (max length: 4 characters). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | The barcode version identifier relevant to each Information Type ID. |

### See Also
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
