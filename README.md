# test-inn-ambush

`test-inn-ambush` is the canonical Semantic Flow data mesh for the Stagecraft Inn Ambush proof of concept.

Stagecraft owns the experiment code, generators, checks, and provisional ontology. This repository owns the fixture data records, mesh support artifacts, and future HistoricalState/publication evidence for the Inn Ambush test data.

Mesh base:

```text
https://spectacular-voyage.github.io/test-inn-ambush/
```

Use `inn:` for that same base when a prefix is useful.

Initial top-level lanes:

```text
sessions/
world/
events/
authority/
projections/
recommendations/
audit/
```

The current first bundle keeps the original Plan B fixture artifacts intact:

- `authority/journals/plan-b/plan-b.ttl`
- `world/states/inn-ambush-plan-b-state/inn-ambush-plan-b-state.ttl`
- `projections/contracts/inn-ambush-contract.context.jsonld`
- `projections/contracts/inn-ambush-contract.shapes.ttl`
- `projections/notifications/plan-b-projection-ready/plan-b-projection-ready.json`
- `projections/requests/participant-projection-request-alice/participant-projection-request-alice.json`
- `sessions/contributions/chat-contribution-plan-b-suggestion/chat-contribution-plan-b-suggestion.json`
- `sessions/contributions/chat-contribution-plan-b-declaration/chat-contribution-plan-b-declaration.json`
- `authority/operations/authority-operation-request-plan-b-commit/authority-operation-request-plan-b-commit.json`
- `recommendations/actant-intent/plan-b-review-request/actant-intent-recommendation-request-plan-b-review.json`
- `recommendations/actant-intent/plan-b-review-response/actant-intent-recommendation-plan-b-review.json`

Contribution and recommendation `sourceProjection` records use `observedProjectionState` for the shared RDF projection state the contributor saw, plus `participantProjection` for Alice's participant-scoped view identity. Generic `projectionState` remains on notification/request resource pointers where the pointer is to the shared durable projection state.

`events/` and `audit/` are present as top-level lanes, but the first Plan B bundle does not split committed events or validation evidence into standalone files yet.

Do not treat this repository as the Stagecraft runtime event store. It is a fixture/test-data mesh for stable identifiers, snapshots, audit evidence, validation evidence, and publication experiments.
