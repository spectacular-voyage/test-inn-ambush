# Desire-mode WIDEN fixture manifest

Authored 2026-08-12 by product under Dave's ⓑ′ ruling (2026-08-10 16:12; drop 2026-08-10_1612
§ ②) — **rung ① (WIDEN) only**. Cross-vendor initial consult:
`consult-conative-widen-20260812-2306` (codex, effort high). Counts are parsed quads.

## What this fixture is — and is NOT

The estate's **first `psy:Desire` MODE subject** (`desire-mode/elara/old-road-compulsion`),
with its fiction-time lifetime (`cat:hasTimeExtent` → an explicitly classified `tmpo:Interval`
with beginning and end anchors), its founding and discharging acts (`cat:createdIn` /
`cat:terminatedIn` naming the committed suggestion implant and spell-expiry acts), the axis
selection (`tmpo:TemporalQualification` onto the Inn's world-time axis), and the
characterization-revision record `…suggestion-old-road-r2` superseding the committed record.

⛔ **NOT the MIGRATE or NARROW rungs**: the committed record, its `activeFrom`/`activeUntil`,
the `orexis:` spellings, the Inn contract shape and the JSON-LD context are all untouched. *(AS OF THIS RUNG'S LANDING — the MIGRATE rung's orexis half was performed 2026-08-14 under the ambush migration's Slice 2, orexis-first: those spellings, the contract shape and the context now speak `psy:`; the committed records keep their IRIs.)*
⛔ **The committed authority journal is never rewritten**: every act is referenced by IRI;
supersession, evidence edges and family co-classifications are additive assertions in THIS
fixture graph (the ratified explicit-co-classification-at-write regime).
⛔ **Isolated by construction**: nothing in the platform loads `conformance/fixtures/**` —
verified at landing (zero references across stagecraft packages/tools/apps; the Inn is loaded
by exact file paths).

## THE ADJUDICATION (the mint's own fence — adjudicated, not assumed)

**For this wording-revision case, the revision is a revision of the RECORD, not a second
desire**: one implant act founds ONE mode; both records `psy:evidences` the one mode; the
revision rides `cat:supersededBy`. A second founding act (a re-cast spell, a fresh temptation)
would found a second mode; polishing a sentence does not. **Deliberately narrow**: a revision
changing the desire's CONTENT (different act, target or goal) is a different case owed its own
adjudication. Reasons and both worked options are in the landing drop; the rejected NEW-MODE
reading is exactly what receipt W4 witnesses RED.

## Time honesty

The interval's anchors are **ungrounded narrative anchors** naming the two acts. The committed
acts' `dcterms:created` values are table-clock instants and designate no position on the Inn's
world-time axis; no offsets are minted (including the tempting existing 900/1500 pair —
refused as shape-inference). The deferred grounding is an addressable `tmpo:ContinuityDebt` on
the qualification; its discharge is a later grounding act.

## Receipts (2026-08-12, run before landing; oxigraph 0.5.9, stored literals executed)

| # | Leg | Result |
|---|---|---|
| W1 | fixture parses | GREEN — 53 quads |
| W2 | `validation/same-desire-across-revision.rq` (the #13 discriminator) | GREEN — true |
| W3 | `validation/mode-identity.rq` (one founding act, one mode) | GREEN — true |
| W4 | identity mutation (rebind r2's evidence to a second mode — the rejected reading) | GREEN — discriminator RED |
| W5 | lifetime mutation (delete `cat:hasTimeExtent`) | GREEN — discriminator RED |
| W6 | second-mode mutation (same founding act + bearer) | GREEN — uniqueness RED |
| W7 | positive control: the committed journal carries both referenced acts | GREEN |
| W8 | loader isolation: zero platform references to `conformance/fixtures` | GREEN |

Receipts that could have gone the other way (E25): W4/W5/W6 (witnessed red), W7 (can go
positive and did — the acts are real committed subjects, not fixture inventions).

## Boarded, not claimed

- **MIGRATE rung**: the two committed conative records + the belief record, the Inn contract
  shape (`orexis:activeFrom`, now `psy:activeFrom` since the 2026-08-14 orexis migration), the JSON-LD context.
- **NARROW rung**: `active*` retirement behind amendment #11's one absence receipt.
- **Grounding act**: discharge of `continuity-debt/elara-old-road-compulsion-grounding`.
