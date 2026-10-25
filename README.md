# intention-commitment-result

**Mental Caddie**: a mobile web page for the mental side of golf, used *during* the round.

Most golf apps track what happened. This one helps with what's going on between your ears:

- **Intention:** set one process goal and a mantra on the first tee.
- **Commitment:** after each shot, one tap: were you fully in, half in, or did you doubt it?
- **Reaction:** one more tap: did you accept the result, let it linger, or lose it?

## Preventing the blow-up hole

The damage usually comes from the *next decision* after a bad shot or a bad break: the 5-wood from the rough "just to end the hole." So the app steps in at that moment:

- **My Rules:** if-then rules for your own known traps, written at home while you're calm ("Rough → no woods, 7-iron to the fat part of the fairway").
- **Trouble mode:** what happened → cool down → your rule, shown big → a new target for the hole ("bogey is a good score now") → commit.
- **Reset:** 10 steps, two breaths, "next shot is the only shot."
- **Proof:** over time, the app compares your score on trouble holes when you followed your rule vs when you broke it.

## Use it

One self-contained `index.html` with no build step and no dependencies. It works offline. Host it anywhere (GitHub Pages works), open it on your phone, and add it to your Home Screen.

Data stays on your device in `localStorage`. A round stays open until you end it, and every finished round is kept. Use **Backup** to export and import a JSON copy.
