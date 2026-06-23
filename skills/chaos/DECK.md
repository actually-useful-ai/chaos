# The Deck

Two suits. **Bits** shipped somewhere real; riff on their mechanism, don't rerun them.
**Constraints** are frames to build under. The deck grows: every /chaos result that
ships gets a card (see the harvest loop in SKILL.md).

## Bits

1. **The overwhelming swarm**: up to 2,200 boids chase the cursor; clicking scatters them and the page shouts BEES!; there is no product. Shipped: bzbzbzbz.bz. Why it lands: total commitment plus escalation; the site believes in bees so you don't have to.
2. **The a11y control is the punchline**: the pause button for the swarm says "shoo bees" / "release the bees." Shipped: bzbzbzbz.bz (v1). Why: the compliance requirement became the best line; nobody expects WCAG to be funny.
3. **The 404 is the best page**: a sea monster lives at the error page; people 404 on purpose. Shipped: dr.eamer.dev (Sea Monster 404, its own service on port 5028). Why: the page nobody designs is the page nobody forgets.
4. **The domain is the entire pitch**: gofuckyourself.mom serves insults; lololololol.lol exists; bzbzbzbz.bz buzzes. Shipped: the domain portfolio. Why: the URL does the marketing before the page loads.
5. **Deadpan receipts**: "Community-submitted. Editor-approved. Screenshots and receipts." Three fragments, no sales pitch. Shipped: fuckthis.tech README. Why: fragments move faster than sentences; deadpan trusts the reader.
6. **Absurd precision**: "~1044 entries, read+written live" instead of "a growing collection." Shipped: insults/CLAUDE.md. Why: a number is a fact; facts are funnier than adjectives.
7. **The sincere twin**: compliments.live runs the same architecture as insults.live, completely earnest. Shipped: compliments/. Why: the pairing is the joke; neither page acknowledges the other.
8. **Product decisions that should have stayed in draft**: a moderated feed of bad LLM launches, framed like serious journalism. Shipped: fuckthis.tech. Why: the editorial seriousness IS the comedy.
9. **A clock that takes you hostage**: the ransomclock tells time in cut-out ransom letters; siblings include an abacus, an hourglass, and a literal burning fuse. Shipped: html/clocks + html/zen. Why: an absurd premise executed with craft reads as art, not error.
10. **Name the tool what it does, regrettably**: screenshat. zoooom (the extra o's are the feature). jankify. Shipped: npm + the web root. Why: the name admits what everyone was thinking.
11. **The judgmental bot**: a bot that checks whether today was, in fact, the day. It usually wasn't. Shipped: Was Today The Day (Bluesky bot). Why: a tiny recurring disappointment is a character.
12. **Insult the reader exactly once**: one unprofessional sentence in an otherwise professional README. Shipped: the insults project family. Why: rule 1 (one per surface) at maximum dosage.

## Constraints

13. **The error states are the personality.** Build the happy path straight; spend all the voice on what goes wrong.
14. **One thing on this page is alive.** It notices the user: follows the cursor, reacts to idle, flinches at clicks.
15. **It keeps getting worse.** Whatever the user does to fix or dismiss it escalates it. Cap the escalation; land the bit.
16. **The empty state tells the truth.** "No data yet. It's been 4 days. We believe in you" beats a gray illustration.
17. **The loading state is a tiny game.** If they must wait, let them do something pointless and pleasant.
18. **An easter egg only keyboard users find.** Reward the tab key. The screen-reader description is in on it.
19. **Deadpan-document something ridiculous.** Full API docs, changelog, and semver for a joke. Never wink.
20. **The settings page has one setting.** It is a strange one, and it works.
21. **Absurd metric, real dashboard.** Track something nobody needed measured, with production-grade rigor.
22. **The cursor is a character.** Predator, prey, or celebrity: the page has an opinion about where you point.
23. **Let the data be the joke.** No gags in the chrome; pick a dataset that's funny and present it completely straight.
24. **The pause button is part of the joke.** Whatever moves, its stop control gets the best label on the page.
25. **Commit to a bit involving bees.** Historically reliable.
- **bitwheel activation ripple** — a soft cyan ring pulses out from each binary node the instant its bit flips 0→1; the seconds wheel gives a constant quiet heartbeat.
  - Landed because it makes a minimalist binary clock feel alive and intentional without adding any noise — the motion *is* the data changing.

26. **The smooshable queen**: a crowned queen ambles through the swarm, fleeing the cursor but never fast enough; smoosh her and the screen reads REGICIDE!, the entire swarm hunts your cursor at 1.5x speed, and a new queen hatches anyway. Shipped: bzbzbzbz.bz. Why: a guilt mechanic with no stakes; the punishment is attention and the consequence is more bees.
27. **Serenity is the setup**: the meadow is genuinely peaceful (dusk sky, pollen, lazy drifting camps) and stays that way until you personally ruin it; the fury is the consequence of one specific choice, and calm returns when a new queen hatches. Shipped: bzbzbzbz.bz (dusk meadow rework). Why: a mood you can ruin is worth ten moods you can't; making the player the villain beats making the page loud.
28. **The honest worker bleps.** The element actually doing the job breaks character on a loose, off-beat timer (never on the read itself), then settles back. (Landed: the googly day-tongue flicks out and waggles between readings without ever moving off the true hour.)
29. **A hand drags its own ghost.** When time is read by a moving light, let the live marker trail a short, fading comet of where it just was — recent seconds linger as dim after-images behind the bright now. (Landed: across the searchlight/beacon/horizon light-clocks, the second-hand lamp leaves a decaying wake, so you *see* time pass rather than just tick.)
30. **The mechanism confesses, in the first person.** When a thing behaves oddly on purpose, let it own up in the console: a short, in-character note only the curious (devtools-openers) ever find. (Landed: the *hesitant* clock, whose second hand reaches the hour early and ticks backward before committing, leaves a wry first-person note admitting exactly that. The voice hesitates the same way the hand does, and it costs the face nothing.)

31. **Move the event from the read to the tension before it.** When something dramatic fires on every tick, it stops reading as dramatic — so spend the interval *building* to it instead. Let stress visibly accumulate across the whole surface, then release it all at once on the real boundary. (Landed: the *shatter* clock stopped popping a digit twice a second; now the hour and minute hold as solid glass while a fracture network creeps across the pane through the minute, and the entire thing shatters and reassembles once, on the minute. The seconds became the spreading cracks.)
