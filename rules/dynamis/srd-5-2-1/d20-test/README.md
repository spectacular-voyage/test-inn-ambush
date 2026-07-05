# SRD 5.2.1 D20 Test Rules

This package is a curated extraction from the CC-BY-4.0 SRD 5.2.1 PDF. The permanent authoring surfaces are `d20-test.abilities.csv`, `d20-test.skills.csv`, and `d20-test.test-types.csv`; `d20-test.ttl` is generated from those CSVs by `tools/srd-extraction/extract-srd.mjs build-rdf` in the Stagecraft repo.

The package intentionally stops at the check/save/attack-roll family and ability-to-skill decision rows. It does not include weapons, spells, statblocks, or sheet generation. The `skill-*` rows are enough for a future sheet renderer to discover that Athletics is a Strength ability-check affordance.

Attribution: this package includes material from System Reference Document 5.2.1 by Wizards of the Coast LLC, available under the Creative Commons Attribution 4.0 International License.
