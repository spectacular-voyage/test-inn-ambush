# SRD 5.2.1 Spell Rules

This package is a curated extraction from the CC-BY-4.0 SRD 5.2.1 PDF. The permanent authoring surfaces are `spells.csv`, `schools.csv`, `spell-classes.csv`, and `spell-expressions.csv`; `spells.ttl` is generated from those CSVs by `tools/srd-extraction/extract-srd.mjs build-rdf` in the Stagecraft repo.

Spell records, schools, class-list availability rows, and damage or healing expression rows are data only. The package records save abilities and spell-attack flags so consumers can discover likely D20-test surfaces, but it does not wire spell effects into ActionTypes, spell slots, limited-use counters, prepared-spell state, monster stat blocks, or authority-side effect resolution.

Class availability is taken from the SRD class spell-list tables and cross-checked against the class names in spell-description headers. The SRD text has known header/list divergences in this corpus: `Phantasmal Force` appears with Bard, Sorcerer, and Wizard in its spell-description header but is absent from those class spell-list tables; `Mind Spike` appears with Sorcerer in its spell-description header but is absent from the Sorcerer spell-list table; and `Flaming Sphere` is Conjuration in its spell description but appears as Evocation in class spell-list tables. The curated data keeps the spell-description school on `spells.csv` and uses class spell-list tables for `spell-classes.csv`.

Expression rows extract grammar-checked dice expressions or static hit-point amounts from source prose. Rows such as higher-level scaling keep their prose context; they are not effect codification.

Attribution: this package includes material from System Reference Document 5.2.1 by Wizards of the Coast LLC, available under the Creative Commons Attribution 4.0 International License.
