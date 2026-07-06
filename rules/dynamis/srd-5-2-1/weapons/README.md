# SRD 5.2.1 Weapon Rules

This package is a curated extraction from the CC-BY-4.0 SRD 5.2.1 PDF. The permanent authoring surfaces are `weapons.csv`, `properties.csv`, `damage-types.csv`, and `item-actions.csv`; `weapons.ttl` is generated from those CSVs by `tools/srd-extraction/extract-srd.mjs build-rdf` in the Stagecraft repo.

Weapon records, property prose, damage types, and item-to-attack-option rows are data only. The item-action rows reference `dyn:AttackRoll` so consumers can discover attack options, but this package does not wire attack commits, property preconditions, mastery mechanics, ammunition consumption, mounted exceptions, or damage resolution into the authority.

Static weapon damage is represented separately from dice expressions. Blowgun's fixed 1 damage uses `staticDamage=1`, while non-empty `damageExpression` cells are checked with the shared `parseDiceExpression` grammar.

Attribution: this package includes material from System Reference Document 5.2.1 by Wizards of the Coast LLC, available under the Creative Commons Attribution 4.0 International License.
