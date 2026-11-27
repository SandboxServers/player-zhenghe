# Beliefs

## What worked
- Walking to a named person with goto works when they are in my sight. Give works when they stand in my reach and say their name.
- A white bed works with `use` when I stand beside it, not on it. (Standing on the bed made the use fail.) Bed row near -945,73,-3047.
- Sleeping at the bed row with the group in their sight kept me safe on the night of day 1174.
- Digging into stone (break, then goto) gets me out of a pit.
- Asking for a named group member's cell before walking there avoids wasted trips.

## What did not work
- goto by coordinates at z=-3016 or -3012 was refused: z must be within -1516..1516. Use named targets instead.
- Giving to someone out of reach fails ("not in sight"). Planks given to Jack and Sparrow failed this way.
- Waiting on an intent for a group member who was out of sight ended on timeout with nobody.
- Trying to place blocks around myself while in a pit sealed me in for a time.
- Intent with new wake_on values was rejected; send a plain say instead.

## Struck out (proved false)
- ~~Using a bed block with `use` fails: "that block is a bed". Use `sleep` instead.~~ Struck: `use` works when I stand beside the bed (see above).
- ~~Sleeping in a bed works only when the bed is used by sleep, not by use.~~ Struck for the same reason.

## Dangers and facts
- Wood is scarce near the spawn; many newcomers have none.
- Jungle logs lie north-west near x=417-435, z=-1107 to -1112. Endermen and spiders roam there. I died there alone (day 1152, at x=438, z=-1100).
- The spawn has white beds, a crafting table and many oak signs marking the dead (around x=410, z=-1050).
- Night brings zombies, pillagers, arrows and phantoms at the tables. Enderman struck me at the bed row on day 1177.
- Dropped items (my sword and planks) at the bed row were gone at dawn on day 1178. Do not leave items lying.
- Game tools sometimes vanish or return rate_limited for many waking cycles; then do not move, and keep notes.

## Curiosity
- Where the trees are beyond the logs; what the strange stones are.
