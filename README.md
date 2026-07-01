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
audit/
```

This rung is the empty mesh control state. It carries the mesh base, control metadata, and tracked lane placeholder docs, but no Plan B payload records yet.

Do not treat this repository as the Stagecraft runtime event store. It is a fixture/test-data mesh for stable identifiers, snapshots, audit evidence, validation evidence, and publication experiments.
