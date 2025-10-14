Unlinked mentions are the TBD list

```dataview
TABLE filter(file.outlinks,(x)=>startswith(lower(meta(x).display),"tbd")) AS "Link"
FROM "dnd_notes/Strixhaven" AND [[TBD]]
```