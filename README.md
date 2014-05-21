eqlog mob faction hit parser.

Requires at least faction message, mob slain, and enter zone messages. (As in, running `grep 'faction\|slain\|entered` to clean up the file will work)

Currently can't hand messages from quests (they will ruin the results)

Max faction (max negative or positive) will also cause issues.

Zone limiting assumes PEQ scheme for mob NPC IDs (zone id * 1000 to zone id * 1000 + 999)
