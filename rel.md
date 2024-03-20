# Link Relationships

This document serves as the official registry of link relationships for the OPDS and ODL specifications. 

## Acquisition Links

| Value  | Definition | Reference |
| ------ | ---------- | --------- | 
| `http://opds-spec.org/acquisition`  | Fallback acquisition relation when no other relation is a good fit to express the nature of the transaction.  | [OPDS 1.2](https://specs.opds.io/opds-1.2) |
| `http://opds-spec.org/acquisition/open-access`  | Indicates that a publication is freely accessible without any requirement, including authentication.  | [OPDS 1.2](https://specs.opds.io/opds-1.2) |
| `http://opds-spec.org/acquisition/borrow`  | Indicates that a publication can be borrowed for a limited period of time.  | [OPDS 1.2](https://specs.opds.io/opds-1.2) |
| `http://opds-spec.org/acquisition/buy`  | Indicates that a publication can be purchased for a given price. | [OPDS 1.2](https://specs.opds.io/opds-1.2) |
| `http://opds-spec.org/acquisition/sample`  | Indicates that a sub-set of the full publication is freely accessible at a given URI, without any prior requirement. <br />This relationship is deprecated since the release of OPDS 2.0, `preview` should be used instead. | [OPDS 1.2](https://specs.opds.io/opds-1.2) |
| `preview`  | Indicates that a sub-set of the full publication is freely accessible at a given URI, without any prior requirement. | [RFC6903](https://tools.ietf.org/html/rfc6903#section-3) |
| `http://opds-spec.org/acquisition/subscribe`  | Indicates that a publication be subscribed to, usually as part of a purchase and for a limited period of time. | [OPDS 1.2](https://specs.opds.io/opds-1.2) |

## Collection or Feed-level Links

| Value  | Definition | Use Case | Reference |
| ------ | ---------- | -------- | --------- | 
| `first`  | An IRI that refers to the furthest preceding resource in a series of resources.  | Provides a link to the first page when the current feed/collection is paginated. | [RFC5988](https://tools.ietf.org/html/rfc5988) |
| `last`  | An IRI that refers to the furthest following resource in a series of resources. | Provides a link to the last page when the current feed/collection is paginated. |[RFC5988](https://tools.ietf.org/html/rfc5988) |
| `next`  | Refers to the next resource in a ordered series of resources. | Provides a link to the next page when the current feed/collection is paginated. |[HTML4](https://www.w3.org/TR/html4/types.html#type-links) |
| `previous`  | Refers to the previous resource in an ordered series of resources. Synonym for "prev". | Provides a link to the previous page when the current feed/collection is paginated. | [HTML4](https://www.w3.org/TR/html4/types.html#type-links) |
| `start`  | 	Refers to the first resource in a collection of resources. | Provides a link to the homepage of an OPDS Catalog. | [HTML4](https://www.w3.org/TR/html4/types.html#type-links) |
| `http://opds-spec.org/shelf`  | A Resource that includes a user’s existing set of Acquired Content, which may be represented as an OPDS Catalog. | The shelf relationship is fairly widely used in the OPDS ecosystem to list all content acquired by a given user. | [OPDS 1.2](https://specs.opds.io/opds-1.2#61-relations-for-previously-acquired-content) |