---
statblock: true
name: Night Hag with Inline Spells
source:
  - Custom
extends: Night Hag
spells:
  - Innate Spellcasting -- The hag's innate spellcasting ability is Charisma (spell save DC 14, +6 to hit with spell attacks). She can innately cast the following spells, requiring no material components
  - At will: detect magic, magic missile
  - 2/day each *: plane shift, ray of enfeeblement, sleep
  - "* Plane shift self only"
  - Shared Spellcasting -- While all three members of a hag coven are within 30 feet of one another, they can each cast the following spells from the wizard's spell list but must share the spell slots among themselves. For casting these spells, each hag is a 12th-level spellcaster that uses Intelligence as her spellcasting ability. The spell save DC is 12+the hag's Intelligence modifier, and the spell attack bonus is 4+the hag's Intelligence modifier.
  - 1st level (4 slots): identify, ray of sickness
  - 2nd level (3 slots): hold person, locate object
  - 3rd level (3 slots): bestow curse, counterspell, lightning bolt
  - 4th level (3 slots): phantasmal killer, polymorph
  - 5th level (2 slots): contact other plane, scrying
  - 6th level (1 slot): eyebite
---

```statblock
extends: Night Hag with Inline Spells
name: Night Hag
```

```dataviewjs
dv.span(dv.current().file.name)
```