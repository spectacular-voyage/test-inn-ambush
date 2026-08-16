LANDING IDIOM (this clone): ordinary. `main` is checked out here and tracks origin/main —
push with `git push origin main`.

HISTORY, so the old idiom is not re-applied from memory or from a stale note: until
2026-08-15 05:40 this clone had a LINKED WORKTREE sibling (`test-inn-ambush-main`, one
object store, one shared `main` ref — never a second clone) which held `main`, so the
primary sat on a bite branch and every landing had to go `git push origin <branch>:main`.
That pair produced one false "another writer wrote" alarm (2026-08-14 23:01: a naked
`git push origin main` pushed the SHARED, one-behind `main` ref and was correctly
rejected non-fast-forward). The worktree is retired and its bite branch — 0 ahead, 0
behind main — deleted. The `b.29`–`b.33` lane branches STAY: conformance rungs 81–85
reference them as `origin/b.*` toRefs and Accord reads those trees.
