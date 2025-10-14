Unlinked mentions are the TBD list

```dataview
TABLE filter(file.outlinks, (x) => startswith(link,"TBD")) AS "Link"
FROM "dnd_notes/Strixhaven" AND [[TBD]]
```