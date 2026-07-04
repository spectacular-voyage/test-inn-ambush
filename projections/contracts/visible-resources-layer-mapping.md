# visibleResources Layer Mapping

`visibleResources` is the participant-projection response field. It is a resolved read-model list, not the source disclosure relation.

The source disclosure relation in the world-state graph is `sc:visibleTo`, carried by accepted `sc:TemporalRelator` nodes:

```turtle
?visibilityRelator
  a sc:TemporalRelator ;
  sc:subject ?resource ;
  sc:predicate sc:visibleTo ;
  sc:object ?participant ;
  sc:acceptedFrom ?acceptedFrom .
```

Readers derive `visibleResources` by filtering current accepted visibility relators for the authenticated participant, excluding relators whose `sc:acceptedUntil` closes the interval as of the read instant, then joining the resulting `?resource` back to the branch state graph. The response envelope stays resolved-current-state for v1 and does not expose acceptance or applicability axes.
