---
title: CertificateMetadataSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Contains Certificate Metadata Signature properties."
type: docs
url: /python-net/groupdocs.signature.domain/certificatemetadatasignature/
is_root: false
weight: 70
---


## CertificateMetadataSignature class

Contains Certificate Metadata Signature properties.

The CertificateMetadataSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/__init__/#name) | Initializes a Certificate Metadata Signature with a predefined name and an empty value. |
| [__init__](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/__init__/#name-value) | Initializes a Certificate Metadata Signature with predefined values. |

### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/clone/) | Clone Metadata Signature instance. |
| [clone](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/clone/#value) | Clone Certificate Metadata Signature instance with given value. |
| [clone_object](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/clone_object/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/) | Converts the metadata signature to a string using the overridden ToString method. |
| [to_string](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/#format-provider) | Converts to a string with the specified format. |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string_string/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals/) | Determines whether the specified signature is equal to this instance. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [equals_object](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals_object/) |  (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) |  (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) |  (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_hash_code/) | Returns the hash code for the metadata signature. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_boolean/) | Converts to boolean. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/) | Converts the metadata signature value to a datetime. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time_iformat_provider/) |  (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/) | Converts the metadata signature value to Decimal. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal_iformat_provider/) |  (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double/) | Converts the metadata signature value to a float. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double_iformat_provider/) |  (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_integer](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_integer/) | Converts the metadata signature value to an integer. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single/) | Converts the metadata signature value to a float. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single_iformat_provider/) |  (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### Properties
| Property | Description |
| :- | :- |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | The signature creation date. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | The implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) used to encode and decode signature value properties. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | The flag indicating whether this signature was deleted from the document. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | The height of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | The flag indicating whether this component represents a signature (`True`) or document content (`False`). (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | The left position of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | The signature modification date. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | The unique metadata name. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | The page number where the signature was found. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | The unique identifier of the signature, used to modify the signature in the document via update or delete operations. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | The type of signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | The top position of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | The metadata value type. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | The metadata object. (inherited from [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | The width of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
