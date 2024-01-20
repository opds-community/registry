# Reasons

This document serves as the official registry of reasons for the OPDS and ODL specifications. 

Reasons are meant to convey why a particular resource is available/unavailable, either at a publication, link or license level.

| URL | Description | Associated states |
| ---- | ---------- | ----------------- |
| https://registry.opds.io/reason#exhausted | Indicates that a publications and/or all of the usage allowed by its licenses have been exhausted. | `unavailable` |
| https://registry.opds.io/reason#expired | Indicates that a publications and/or all of its licenses have expired. | `unavailable` |
| https://registry.opds.io/reason#onHold | Indicates that a publication is temporarily unavailable because it's on hold. | `unavailable` or `reserved` |
| https://registry.opds.io/reason#preordered | Indicates that a publication is temporarily unavailable because it hasn't been released yet. |  `unavailable` |
| https://registry.opds.io/reason#refunded | Indicates that a publication or one of its licenses has been refunded. | `unavailable` |
| https://registry.opds.io/reason#removed | Indicates that a publication or one of its licenses has been removed from a subscription or from distribution in general. | `unavailable` |
