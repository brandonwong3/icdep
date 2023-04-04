## How can we send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network, rather than treat them as pass-through intermediaries?

#### To send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network, we can add a “tag” system (/command) on the card that acts as a command message for particular nodes. The node would check to see if card has a command corresponding to the unique ID. If not, it pass the card the next node.
