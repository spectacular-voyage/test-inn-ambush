# inn-intent-stand fixture manifest

Authored 2026-08-14 by product as **the `par:IntentStand` mint's #13-style exercise** (boarded in
the mint's closing act; the stand-design review's amendment ④ is this fixture's spec) — and the
same graph carries the WITNESSED demonstrations of both same-night derivations: the
reconsideration window's derived single-cycle openness, and the accepted-pending-clarification
naive query's FALSE POSITIVE on an ordinary warrant (the missing clarification discriminator,
witnessed rather than fixed).

## The graph and its discriminators
Two otherwise-eligible accepted intents; ONE typed stand event standing exactly one of them; one
ordinary live adjudication warrant on the other. Discriminators, each with its receipt-only
ablation: **class** — `mutants/untyped-stand.ttl` strips only the event's
`cat:instanceOf par:IntentStand`, and the stood answer flips AND the cellar window re-reads OPEN
(the classification is load-bearing for the derivation, not just for the ASK); **relation** —
`mutants/swapped-stand.ttl` retargets `par:standsIntent`, and BOTH windows flip.

## Receipts (2026-08-14, run before landing; asserted-only oxigraph; runner + output preserved
## in the landing drop; every asserted predicate gates the verdict)
| leg | G+ | untyped-stand | swapped-stand |
|---|---|---|---|
| window-open set | {bar-the-door} | {both} | {search-the-cellar} |
| stood (joined class+relation ASK) | true | **false** | **false** |
| apc-naive set | {bar-the-door} | {bar-the-door} | {bar-the-door} |
All nine cells asserted against expectations; quads 26/25/26 strict-parsed with sha256s emitted.

## Honest gaps — what this fixture does NOT prove
- **No SHACL legs**: no par: shapes exist yet — stated, not implied; the singleton-targeting
  convention is NOT promoted to a shape here.
- **Single-cycle scope only**: repeat-cycle pairing needs a ruled identity/pairing contract
  (the landed sg law) and is deliberately not exercised.
- **The APC leg witnesses, never repairs**: the naive query's constant {bar-the-door} across
  all three graphs IS the false-positive demonstration — an ordinary test-resolution warrant
  satisfies it, so the clarification discriminator remains the recorded gap.
- No performer on the stand event, per the labeled authoring convention (auto-stand tier).
