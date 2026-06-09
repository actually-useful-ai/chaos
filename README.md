# chaos

Claude Code plugin that mixes things up. One command, three behaviors, picked by reading the room:

- **Inject**: you're mid-build and the work is getting too serious. `/chaos` adds one chaotic element to whatever's in flight.
- **Remix**: point it at something that already shipped (`/chaos html/colors`) and it finds the one place a bit belongs.
- **Deal**: invoke it before you start and it deals 2-3 creative constraints to build under ("the error states are the personality").

## Install

```
/plugin marketplace add actually-useful-ai/chaos
/plugin install chaos@actually-useful-ai-chaos
```

## The taste gate

When the move is clear, additive, and reversible, it just does it. When in doubt about register or blast radius, it pitches 2-3 options and waits. A pitched joke costs nothing; a misjudged one costs trust.

Hard rules: one chaotic element per surface. Never in API references, stress-path error messages, accessibility text, or anything clinical. Moving chaos ships with a pause control and respects `prefers-reduced-motion`. The work stays correct; the joke is never load-bearing.

## The deck

`skills/chaos/DECK.md` holds the cards in two suits: **bits** that shipped somewhere real (an overwhelming bee swarm that chases your cursor, a 404 with a sea monster, a README that insults the reader exactly once) and **constraints** for deal mode. Every time a `/chaos` result ships, the deck gains a card. It starts as a portrait of one person's taste and keeps growing.

Card 25 is "Commit to a bit involving bees." Historically reliable.

## License

MIT. Author: Luke Steuber ([lukesteuber.com](https://lukesteuber.com)).
