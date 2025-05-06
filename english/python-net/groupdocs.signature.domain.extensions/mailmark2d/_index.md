---
title: Mailmark2D class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 170
---

## Mailmark2D class

Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark



The Mailmark2D type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/#) | Creates Royal Mail Mailmark combined data with default primary and secondary data values. |


### Properties
| Property | Description |
| :- | :- |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id) | Identifies the UPU Country ID.Max length: 4 characters. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id) | Identifies the barcode version as relevant to each Information Type ID. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id) | Identifies the unique group of customers involved in the mailing. <br/>Max value: 9999999. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id) | Identifies the unique item within the Supply Chain ID. <br/>Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days.<br/>Max value: 99999999. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps) | Contains the Postcode of the Delivery Address with DPS <br/>If inland the Postcode/DP  contains the following number of characters. <br/>Area (1 or 2 characters) <br/>District(1 or 2 characters)<br/>Sector(1 character) <br/>Unit(2 characters) <br/>DPS (2 characters). <br/>The Postcode and DPS must comply with a valid PAF® format. Max length is 9. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag) | Flag which indicates what level of Return to Sender service is being requested. Max length is 1 |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code) | Contains the Return to Sender Post Code but no DPS.<br/>The PC(without DPS) must comply with a PAF® format. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content) | Optional space for use by customer. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode) | Encode mode of DataMatrix barcode. Default value: DataMatrixEncodeMode.C40. [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode) |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type) | 2D Mailmark Type defines size of Data Matrix barcode. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/#) | Gets a copy of this object. |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode)
