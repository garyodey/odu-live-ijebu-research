# Data Schema

## Entity

Required:
- id
- label
- type
- evidence_state

Recommended:
- source_forms[]
- dates[]
- locations[]
- notes

## Relationship

Required:
- from
- relation
- to
- evidence_state

Recommended:
- source_id
- valid_from
- valid_to
- context
- notes

## Preferred entity types

PERSON, OFFICE, PLACE, QUARTER, COMPOUND, ULE, LINEAGE, RULING_HOUSE, INSTITUTION, STYLE, ADMINISTRATIVE_CLASSIFICATION, DOCUMENT.

## Preferred relationship types

HOLDS_OFFICE, OFFICE_OF, DESCENDS_FROM, MEMBER_OF, HEADS, NOMINATES, SELECTS, CONSENTS_TO, ASSEMBLES_AT, LOCATED_IN, ASSOCIATED_WITH, SOURCE_ASSERTS.

Identity equivalence requires explicit evidence and must not be inferred from SAME_FORM or G_MATCH.
