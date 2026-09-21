# Agent Instructions

This repository is a genealogy evidence project. Accuracy outranks completeness.

## Non-negotiable rules

1. **Never invent a person, date, spouse, parent, occupation, event, or relationship.**
2. Do not attach someone because the surname and geography look plausible.
3. Family testimony is valuable evidence, but label it as family-confirmed rather than pretending it is a civil record.
4. Online trees and compiled genealogies are leads unless their underlying sources are checked.
5. Keep contradictory records visible.
6. An unresolved parent is better than a guessed parent.
7. Do not silently change a name spelling. Record variants.
8. For living people, keep this public repository minimal and do not add unnecessary private data.
9. Do not attach criminal/legal history from a same-name record without unusually strong identity matching.
10. Do not label an ancestor rich/poor from one clue; preserve economic evidence and historical context.

## Before changing the tree

For any new parent-child relationship:
- identify both people
- cite the source
- state what the source actually proves
- assign an evidence grade
- note conflicts
- update the machine-readable relationship data (`data/relationships.json` for parent → child; `data/connections.json` for spouse/sibling/social/collateral links)
- update the relevant branch research file
- add an entry to RESEARCH_LOG.md

## Before adding a life-dossier claim

For occupations, military, business, property, legal history, wealth/class, hobbies or other biography:
- identify the exact person
- cite the source
- record date/place context
- state whether the claim is direct or inferred
- note identity conflicts
- update LIFE_DOSSIERS.md or the relevant branch file

## Evidence grades

- A — primary/direct
- B — strong secondary
- C — compiled genealogy
- D — hypothesis/lead
- F — disproved/rejected

## Machine-readable graph rule

- `data/relationships.json` is directional and reserved for biological/adoptive parent → child claims.
- `data/connections.json` stores non-parent relationships such as spouse, former spouse, co-parent, sibling, social grandparent and collateral-relative links.
- Never encode a social or marital relationship as a biological parent edge just to make an app draw a connection.
- A person may exist in `people.json` without being attached to the direct pedigree if the relationship is collateral or unresolved.

## Promotion rule

A D-level hypothesis should not appear in the main direct-ancestor chain as fact.

A C-level compiled relationship may appear as a working reconstruction **only if explicitly labeled C**.

## Important known corrections

Do not regress these:
- Macomber is not Masen's biological maternal surname line.
- Anne's birth surname is Hickok, not Herrington.
- The correct great-grandfather is Edwin James Hickok, not Edward James Hickok.
- George Spear is a social/family grandfather, not Masen's biological ancestor.
- The Missouri German Gromer story is not yet connected to Masen's direct Gromer line.
- Robert A. McFadden Jr., DDS is a lead for Robert Jr.; do not use it to claim Robert McFadden Sr. was a dentist.

## Research style

Prefer:
1. civil/vital records
2. census
3. military records
4. church records
5. probate/land/court records
6. contemporary newspapers
7. obituaries
8. cemetery records
9. compiled genealogies / online trees

When possible, triangulate major relationships from two independent records.

The end goal is not only a pedigree. It is a defensible answer to **who these people actually were**.
