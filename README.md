# intention-commitment-result

**Mental Caddie**: a mobile web page for the mental side of golf, used *during* the round.

**Try it:** [y4x.com/icr](https://y4x.com/icr/)

Most golf apps track what happened. This one helps with what's going on between your ears:

- **Intention:** set one process goal and a mantra on the first tee.
- **Commitment:** after each shot: were you fully in, half in, or did you doubt it?
- **Result:** judge it the way you already do: *All good*, *Good, but…* (bunker, trees, rough, a bad bounce), or *Not what I wanted*.
- **Reaction:** if it wasn't all good, how are you taking it: accepted, lingered, or lost it?

## Mental score

Like a scorecard, it's shown as a number against par as you play, and it's the only score shown during the round: **Mental −1**. Mental par is a committed, accepted shot. A bad break you accept costs nothing.

| | Mental strokes |
|---|---|
| Fully in + accepted | 0 |
| Half in or doubted | +1 |
| Lingered | +1 |
| Lost it | +2 |
| Kept your rule in trouble | −1 |
| Broke your rule | +2 |

## Preventing the blow-up hole

The damage usually comes from the *next decision* after a bad shot or a bad break: the 5-wood from the rough "just to end the hole." So the app steps in at that moment:

- **My Rules:** if-then rules for your own known traps, written at home while you're calm ("Rough → no woods, 7-iron to the fat part of the fairway").
- **Trouble mode:** a *Good, but…* shot goes straight to your rule for that spot, shown big, with a new target for the hole ("bogey is a good score now") and a choice to commit to the rule or go for it anyway. You can also open it any time with the Trouble button.
- **Reset:** 10 steps, two breaths, "next shot is the only shot."
- **Proof:** over time, the app compares your score on trouble holes when you followed your rule vs when you broke it.

## Use it

Open [y4x.com/icr](https://y4x.com/icr/) on your phone and add it to your Home Screen.

It's one self-contained `index.html` with no build step and no dependencies, and it works offline, so you can also host your own copy anywhere.

Data stays on your device in `localStorage`. A round stays open until you end it, and every finished round is kept. Use **Backup** to export and import a JSON copy.
