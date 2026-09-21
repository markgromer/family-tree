# Gromer Family Tree Research

A source-controlled genealogy project centered on **Masen Gromer** and his biological ancestry.

This repository exists so the research does not depend on one chat, one family story, or one online tree. Every branch should distinguish between what is documented, what is strongly supported, and what is still only a lead.

## Research goals

1. Build Masen's biological family tree as far back as reliable evidence allows.
2. Identify the immigrant generation for each major surname line.
3. Document notable ancestors and the historical context they lived in.
4. Build **life dossiers**: occupations, military service, property, businesses, economic/class evidence, legal history, migration, hobbies, photographs and contemporary context.
5. Preserve family stories while clearly separating them from proven facts.
6. Track contradictory records instead of silently choosing whichever version looks best.
7. Eventually produce a readable family history, not merely a list of names.

## Current major branches

- **Gromer** — paternal surname line
- **Hickok** — paternal-grandmother line; includes a strong working connection to the colonial Hickok family associated with James Butler "Wild Bill" Hickok
- **Shoenmaker** — Linda Shoenmaker's ancestry; spelling variants need investigation
- **Davison** — maternal-grandfather line; now anchored through Edward H. Davison → Walter M. Davison
- **Hipps** — Betty Louise Hipps line; working chain to Jackson Lee Hipps
- **Rothenberger** — probable maternal line of Edward H. Davison through Julia Rothenberger; primary proof still needed
- **Johnson** — working maternal line of Betty Hipps through Jeanette Ovidia Johnson; reported Swedish ancestry unresolved
- **McFadden** — maternal-grandmother line
- **Handy / related lines** — Robert Dixon Handy is documented as Annabelle McFadden's brother; Annabelle's exact parents remain unresolved

## Evidence grades

- **A — Primary / direct:** vital record, census, military file, contemporary government record, original church record, etc.
- **B — Strong secondary:** obituary, cemetery record, institutional biography, family document with corroboration.
- **C — Compiled genealogy:** published family genealogy, FamilySearch/Ancestry tree, derivative index, etc. Useful but must be checked.
- **D — Hypothesis / lead:** plausible connection not yet established by enough evidence.
- **F — Disproved / rejected:** a lead that has been tested and should not be reintroduced without new evidence.

## Privacy

This repository is public. Living relatives should be represented only with the minimum information required to understand relationships. Do **not** commit private addresses, phone numbers, account information, exact birth dates of living people, or other unnecessary personal data.

If deeper private records are collected later, they should live outside the public repository or the repository should be made private.

## Start here

- [Current Tree](TREE.md)
- [Life Dossiers](LIFE_DOSSIERS.md)
- [Open Questions](OPEN_QUESTIONS.md)
- [Research Log](RESEARCH_LOG.md)
- [Sources](SOURCES.md)
- [Hickok Branch](branches/hickok.md)
- [Gromer Branch](branches/gromer.md)
- [Davison / McFadden Branch](branches/davison-mcfadden.md)
- [Shoenmaker Branch](branches/shoenmaker.md)
- [Machine-readable people](data/people.json)
- [Machine-readable parent/child links](data/relationships.json)
- [Typed spouse/sibling/social/collateral connections](data/connections.json)

## Rule for future research

Do not attach a person merely because the surname, location, or date appears to fit.

The machine-readable graph is intentionally split: `data/relationships.json` is reserved for directional parent → child links; `data/connections.json` stores spouse, former-spouse, co-parent, sibling, social-family, and collateral-relative links so those relationships are not lost or misrepresented.

For every parent-child jump, record:

- person
- proposed parents
- source(s)
- evidence grade
- conflicts
- what would prove or disprove the relationship

For every biographical claim, record:
- which exact person it belongs to
- source
- whether it is direct evidence or inference
- date/place context
- conflicts

The tree is allowed to contain unknowns. An honest blank is better than a confident mistake.
